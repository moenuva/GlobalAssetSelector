# GlobalAsset

# 项目背景


# 功能需求
| 完成情况 | 编号 | 功能描述 | 备注|
| --- | --- | --- | --- |
| [ ] | 1 | section1 根据用户按钮按类别在数据库中抓取detail表格，传到用户浏览器的js脚本 |
| [ ] | 2 | section2 用Echarts或D3.js 用户在两侧纵轴点击选择风险指标，横轴是收益指标，用脚本在网页上画出散点图，鼠标移动散点上会显示资产point的具体信息，如name,code,收益率，风险指标x2。每一个资产有两个点对应两个风险指标|




# 页面设计
![Alt text](design/GlobalAsset.png?raw=True)

# 数据库设计




# 文档
- sp > 真实样本数据，以供前段可视化测试
  - info > 存放资产的名称，类型等信息
  - raw > 具体的序列文件，包括日期，价格等
  - valid.csv > raw文件夹中的资产始末信息
  - T210331.csv > 提取出来的指标文件
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
 1. 所有.py 文件 indent 默认 2 个 space
