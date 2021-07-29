# GlobalAsset

# 项目背景


# 功能需求
| 完成情况 | 编号 | 功能描述 | 备注|
| --- | --- | --- | --- |
| [ ] | 1 | section1 根据用户按钮按类别在数据库中抓取detail表格，传到用户浏览器的js脚本 |
| [ ] | 2 | section2 用Echarts或D3.js 用户在两侧纵轴点击选择风险指标，横轴是收益指标，用脚本在网页上画出散点图，鼠标移动散点上会显示资产point的具体信息，如name,code,收益率，风险指标x2。每一个资产有两个点对应两个风险指标。用户可以点击选择，或者是框选散点。在section3中显示|
| [ ] | 3 | section3 根据用户在section2中选择的资产，显示更详细的表格。用户可以通过资产名称或者是资产代号搜索，并填入表格，也可以删除。在表内的信息，会用其他颜色在section2中标记，以区别出没有选中的资产，在第一列，可以让用户勾选是否显示，显示的部分会在section 4中显示。每次选择资产会向服务器请求，具体的价格信息以供下一个section画图。|
| [ ] | 4 | section4 三个滑动区域分别对应显示日期区间，log拟合区间，概率横切线日期，按照在右图显示在概率横切线上的概率， 在右图小框中可以选择一些概率指标，这个部分最好是能用用户本地的js写，以减轻服务器的负荷，如果实在写不出来，用后端python算好之后一次性传给传给前端，前端根据用户选择的三个区间来显示|
| [ ] | 5 | section5 用来显示一些时间序列指标如SCI，MACD，滤波，拟合等，section5可以会根据需要建立多个，在每个section中用户可以选择多个指标。|
| [ ] | 6 | section 6 这里的表格用来预览准备购买的资产，并根据用户的投注金额和手续费，自动计算卖多少unit，剩余现金，总计，占比等信息，供section 7的报告使用|
| [ ] | 7 | section 7 具体的报告区域，用户要有按钮去保存section6&7的报告，评估，影响信息，先不要制作，这个报告部分可以拓展，但目前只用显示总资产，旭日图，以及程序根据配比计算的时间序列，并计算各种指标反映在section 1中，如果太麻烦先不做 |
| [ ] | 8 | 管理后台，后台需要能够下载，查看服务器端的数据表格，以及资产价格文件， 可以供管理员下载，管理员可以手动点击让服务器更新相应的资产，记录服务访问的异常提示（这个由用户服务器写入文件，异常提示会有数个文件，占用空间会非常大，管理后台要想办法预处理然后再显示在浏览器上，注意要过滤掉一些不重要的信息），在管理员页面查看，管理员服务器运行程序和用户服务器运行程序分开，但都可以访问相同的数据源，管理后台使用的端口和用户端口分开来。先不用写管理员登录密码，直接访问，等要上线之前再写，方便管理员查看。|


# 页面设计
![Alt text](design/GlobalAsset.png?raw=True)

# 数据库设计




# 文档
- data > 真实样本数据，以供前段可视化测试
  - info > 存放资产的名称，类型等信息
  - raw > 具体的序列文件，包括日期，价格等
  - valid > raw文件夹中的资产始末信息
  - detail > 提取出来的指标文件
 - src > 用来存放python 源码
   - app.py > 在里面写用flask写后端
   - [ ] select.py > 在里面合并抓取资产并返回json文件，共app.py 使用
       ```
       def select(tp2ex, showkey):
         tp2ex : dict: {资产类型: list of 交易所代码}
         showKey: list: [需要展示的key] 
         return: dcit {资产代码：[showKey中的key，在表格中对应的value]}
         使用pandas实现
         步骤：
           1. info_df = merge info文件夹的内容
           2. dt_df = join valid.csv,T210331.csv 
           3. 用pandas，条件筛选
           4. 格式转换成字典，输出
       ```    
 
 # 代码规范：
 1. 所有.py 文件 indent 默认 4 个 space, 可以在pycharm中设置tab = 4 space

 # 指标
Talib

Overlap Studies 重叠研究
Momentum Indicators 动量指标
Volume Indicators 成交量指标
Volatility Indicators 波动性指标
Price Transform 价格指标
Cycle Indicators 周期指标
Pattern Recognition 形态识别
Statistic Functions 统计函数
Math Transform 数学变换
Math Operators 数学运算符
