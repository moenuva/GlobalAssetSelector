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

 # Talib指标

# Overlap Studies Functions 重叠研究指标
### BBANDS - Bollinger Bands

> 函数名：BBANDS   
名称： 布林线指标  
简介：其利用统计原理，求出股价的标准差及其信赖区间，从而确定股价的波动范围及未来走势，利用波带显示股价的安全高低价位，因而也被称为布林带。    
分析和应用：
[百度百科](https://baike.baidu.com/item/bollinger%20bands/1612394?fr=aladdin) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/56d0d9be66b4f7a0?rid=53)   

```python
upperband, middleband, lowerband = BBANDS(close, timeperiod=5, nbdevup=2, nbdevdn=2, matype=0)
```

Learn more about the Bollinger Bands at [tadoc.org](http://www.tadoc.org/indicator/BBANDS.htm).  
### DEMA - Double Exponential Moving Average  双移动平均线

> 函数名：DEMA   
名称： 双移动平均线  
简介：两条移动平均线来产生趋势信号，较长期者用来识别趋势，较短期者用来选择时机。正是两条平均线及价格三者的相互作用，才共同产生了趋势信号。    
分析和应用：
[百度百科](https://baike.baidu.com/item/%E5%8F%8C%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF/1831921?fr=aladdin) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/a04d723659318237)   

```python
real = DEMA(close, timeperiod=30)
```

Learn more about the Double Exponential Moving Average at [tadoc.org](http://www.tadoc.org/indicator/DEMA.htm).  
### EMA - Exponential Moving Average

> 函数名：EMA   
名称： 指数平均数  
简介：是一种趋向类指标，其构造原理是仍然对价格收盘价进行算术平均，并根据计算结果来进行分析，用于判断价格未来走势的变动趋势。  
[百度百科](https://baike.baidu.com/item/EMA/12646151) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/b7a39d74783ad689?rid=589)   


NOTE: The ``EMA`` function has an unstable period.  
```python
real = EMA(close, timeperiod=30)
```

Learn more about the Exponential Moving Average at [tadoc.org](http://www.tadoc.org/indicator/EMA.htm).  
### HT_TRENDLINE - Hilbert Transform - Instantaneous Trendline
NOTE: The ``HT_TRENDLINE`` function has an unstable period.  

> 函数名：HT_TRENDLINE   
名称： 希尔伯特瞬时变换  
简介：是一种趋向类指标，其构造原理是仍然对价格收盘价进行算术平均，并根据计算结果来进行分析，用于判断价格未来走势的变动趋势。  
[百度文库](https://wenku.baidu.com/view/0e35f6eead51f01dc281f18e.html) 

```python
real = HT_TRENDLINE(close)
```

Learn more about the Hilbert Transform - Instantaneous Trendline at [tadoc.org](http://www.tadoc.org/indicator/HT_TRENDLINE.htm).  
### KAMA - Kaufman Adaptive Moving Average 考夫曼的自适应移动平均线

> 函数名：KAMA   
名称： 考夫曼的自适应移动平均线  
简介：短期均线贴近价格走势，灵敏度高，但会有很多噪声，产生虚假信号；长期均线在判断趋势上一般比较准确
，但是长期均线有着严重滞后的问题。我们想得到这样的均线，当价格沿一个方向快速移动时，短期的移动
平均线是最合适的；当价格在横盘的过程中，长期移动平均线是合适的。  
[参考1](http://blog.sina.com.cn/s/blog_62d0bbc701010p7d.html) 
[参考2](https://wenku.baidu.com/view/bc4bc9c59ec3d5bbfd0a7454.html?from=search)

NOTE: The ``KAMA`` function has an unstable period.  
```python
real = KAMA(close, timeperiod=30)
```

Learn more about the Kaufman Adaptive Moving Average at [tadoc.org](http://www.tadoc.org/indicator/KAMA.htm).  
### MA - Moving average  移动平均线

> 函数名：MA   
名称： 移动平均线  
简介：移动平均线，Moving Average，简称MA，原本的意思是移动平均，由于我们将其制作成线形，所以一般称之为移动平均线，简称均线。它是将某一段时间的收盘价之和除以该周期。 比如日线MA5指5天内的收盘价除以5 。  
[百度百科](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF/217887?fromtitle=MA&fromid=1511750#viewPageContent) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/a04d723659318237?rid=96)   


```python
real = MA(close, timeperiod=30, matype=0)
```

### MAMA - MESA Adaptive Moving Average
NOTE: The ``MAMA`` function has an unstable period.  
```python
mama, fama = MAMA(close, fastlimit=0, slowlimit=0)
```

Learn more about the MESA Adaptive Moving Average at [tadoc.org](http://www.tadoc.org/indicator/MAMA.htm).  
### MAVP - Moving average with variable period
```python
real = MAVP(close, periods, minperiod=2, maxperiod=30, matype=0)
```

### MIDPOINT - MidPoint over period
```python
real = MIDPOINT(close, timeperiod=14)
```

Learn more about the MidPoint over period at [tadoc.org](http://www.tadoc.org/indicator/MIDPOINT.htm).  
### MIDPRICE - Midpoint Price over period
```python
real = MIDPRICE(high, low, timeperiod=14)
```

Learn more about the Midpoint Price over period at [tadoc.org](http://www.tadoc.org/indicator/MIDPRICE.htm).  
### SAR - Parabolic SAR  抛物线指标

> 函数名：SAR   
名称： 抛物线指标  
简介：抛物线转向也称停损点转向，是利用抛物线方式，随时调整停损点位置以观察买卖点。由于停损点（又称转向点SAR）以弧形的方式移动，故称之为抛物线转向指标    。  
[百度百科](https://baike.baidu.com/item/SAR/2771135#viewPageContent) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/d9d94e65be7f6b5e)   


```python
real = SAR(high, low, acceleration=0, maximum=0)
```

Learn more about the Parabolic SAR at [tadoc.org](http://www.tadoc.org/indicator/SAR.htm).  
### SAREXT - Parabolic SAR - Extended
```python
real = SAREXT(high, low, startvalue=0, offsetonreverse=0, accelerationinitlong=0, accelerationlong=0, accelerationmaxlong=0, accelerationinitshort=0, accelerationshort=0, accelerationmaxshort=0)
```

### SMA - Simple Moving Average 简单移动平均线

> 函数名：SMA  
名称： 简单移动平均线  
简介：移动平均线，Moving Average，简称MA，原本的意思是移动平均，由于我们将其制作成线形，所以一般称之为移动平均线，简称均线。它是将某一段时间的收盘价之和除以该周期。 比如日线MA5指5天内的收盘价除以5 。  
[百度百科](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF/217887?fromtitle=MA&fromid=1511750#viewPageContent) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/a04d723659318237?rid=96)   


```python
real = SMA(close, timeperiod=30)
```

Learn more about the Simple Moving Average at [tadoc.org](http://www.tadoc.org/indicator/SMA.htm).  
### T3 - Triple Exponential Moving Average (T3) 三重指数移动平均线

> 函数名：T3  
名称：三重指数移动平均线  
简介：TRIX长线操作时采用本指标的讯号，长时间按照本指标讯号交易，获利百分比大于损失百分比，利润相当可观。 比如日线MA5指5天内的收盘价除以5 。  
[百度百科](https://baike.baidu.com/item/%E4%B8%89%E9%87%8D%E6%8C%87%E6%95%B0%E5%B9%B3%E6%BB%91%E5%B9%B3%E5%9D%87%E7%BA%BF/15749345?fr=aladdin) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/6c22c15ccbf24e64?rid=80)   



NOTE: The ``T3`` function has an unstable period.  
```python
real = T3(close, timeperiod=5, vfactor=0)
```

Learn more about the Triple Exponential Moving Average (T3) at [tadoc.org](http://www.tadoc.org/indicator/T3.htm).  
### TEMA - Triple Exponential Moving Average

> 函数名：TEMA（T3 区别？）
名称：三重指数移动平均线  


```python
real = TEMA(close, timeperiod=30)
```

Learn more about the Triple Exponential Moving Average at [tadoc.org](http://www.tadoc.org/indicator/TEMA.htm).  
### TRIMA - Triangular Moving Average
```python
real = TRIMA(close, timeperiod=30)
```

Learn more about the Triangular Moving Average at [tadoc.org](http://www.tadoc.org/indicator/TRIMA.htm).  
### WMA - Weighted Moving Average 移动加权平均法

> 函数名：WMA  
名称：加权移动平均线  
简介：移动加权平均法是指以每次进货的成本加上原有库存存货的成本，除以每次进货数量与原有库存存货的数量之和，据以计算加权平均单位成本，以此为基础计算当月发出存货的成本和期末存货的成本的一种方法。  
[百度百科](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%8A%A0%E6%9D%83%E5%B9%B3%E5%9D%87%E6%B3%95/10056490?fr=aladdin&fromid=16799870&fromtitle=%E5%8A%A0%E6%9D%83%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/262b1dfd1c68ee30)   


Momentum Indicators 动量指标  
Volume Indicators 成交量指标  
Volatility Indicators 波动性指标  
Price Transform 价格指标  
Cycle Indicators 周期指标  
Pattern Recognition 形态识别  
Statistic Functions 统计函数  
Math Transform 数学变换  
Math Operators 数学运算符  
