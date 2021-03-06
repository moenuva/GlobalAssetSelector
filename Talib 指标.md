- [1 Overlap Studies Functions 重叠研究指标 ](#head1)
	- [1.1 BBANDS - Bollinger Bands](#head2)
	- [1.2 DEMA - Double Exponential Moving Average  双移动平均线](#head3)
	- [1.3 EMA - Exponential Moving Average](#head4)
	- [1.4 HT_TRENDLINE - Hilbert Transform - Instantaneous Trendline](#head5)
	- [1.5 KAMA - Kaufman Adaptive Moving Average 考夫曼的自适应移动平均线](#head6)
	- [1.6 MA - Moving average  移动平均线](#head7)
	- [1.7 MAMA - MESA Adaptive Moving Average](#head8)
	- [1.8 MAVP - Moving average with variable period](#head9)
	- [1.9 MIDPOINT - MidPoint over period](#head10)
	- [1.10 MIDPRICE - Midpoint Price over period](#head11)
	- [1.11 SAR - Parabolic SAR  抛物线指标](#head12)
	- [1.12 SAREXT - Parabolic SAR - Extended](#head13)
	- [1.13 SMA - Simple Moving Average 简单移动平均线](#head14)
	- [1.14 T3 - Triple Exponential Moving Average (T3) 三重指数移动平均线](#head15)
	- [1.15 TEMA - Triple Exponential Moving Average](#head16)
	- [1.16 TRIMA - Triangular Moving Average](#head17)
	- [1.17 WMA - Weighted Moving Average 移动加权平均法](#head18)
- [2 Momentum Indicator Functions 动量指标函数 ](#head19)
	- [2.1 ADX - Average Directional Movement Index](#head20)
		- [ 公式：](#head21)
		- [特点：  ](#head22)
		- [ 指标应用：](#head23)
	- [2.2  ADXR- Average Directional Movement Index Rating](#head24)
	- [2.3 APO - Absolute Price Oscillator](#head25)
	- [2.4 AROON - Aroon](#head26)
		- [ 计算公式：](#head27)
		- [ 指数应用](#head28)
	- [2.5 AROONOSC - Aroon Oscillator](#head29)
	- [2.6 BOP - Balance Of Power 均势](#head30)
	- [2.7 CCI - Commodity Channel Index](#head31)
		- [ 指标应用](#head32)
	- [2.8 CMO - Chande Momentum Oscillator 钱德动量摆动指标](#head33)
		- [ 指标应用](#head34)
	- [2.9 DX - Directional Movement Index DMI指标又叫动向指标或趋向指标](#head35)
	- [2.10 MACD - Moving Average Convergence/Divergence](#head36)
	- [2.11 MACDEXT - MACD with controllable MA type](#head37)
	- [2.12 MACDFIX - Moving Average Convergence/Divergence Fix 12/26](#head38)
	- [2.13 MFI - Money Flow Index 资金流量指标](#head39)
	- [2.14 MINUS_DI - Minus Directional Indicator](#head40)
	- [2.15 MINUS_DM - Minus Directional Movement](#head41)
	- [2.16 MOM - Momentum  动量](#head42)
	- [2.17 PLUS_DI - Plus Directional Indicator](#head43)
	- [2.18 PLUS_DM - Plus Directional Movement](#head44)
	- [2.19 PPO - Percentage Price Oscillator 价格震荡百分比指数](#head45)
	- [2.20 ROC - Rate of change : ((price/prevPrice)-1)*100  变动率指标](#head46)
	- [2.21 ROCP - Rate of change Percentage: (price-prevPrice)/prevPrice](#head47)
	- [2.22 ROCR - Rate of change ratio: (price/prevPrice)](#head48)
	- [2.23 ROCR100 - Rate of change ratio 100 scale: (price/prevPrice)*100](#head49)
	- [2.24 RSI - Relative Strength Index  相对强弱指数](#head50)
	- [2.25 STOCH - Stochastic 随机指标,俗称KD ](#head51)
	- [2.26 STOCHF - Stochastic Fast](#head52)
	- [2.27 STOCHRSI - Stochastic Relative Strength Index](#head53)
	- [2.28 TRIX - 1-day Rate-Of-Change (ROC) of a Triple Smooth EMA](#head54)
	- [2.29 ULTOSC - Ultimate Oscillator 终极波动指标 ](#head55)
	- [2.30 WILLR - Williams' %R 威廉指标](#head56)
- [Volume Indicators 成交量指标](#head57)
	- [2.31 AD - Chaikin A/D Line 量价指标](#head58)
- [3 Volatility Indicator Functions 波动率指标函数  ](#head59)
	- [3.1 ATR - Average True Range](#head60)
	- [3.2 NATR - Normalized Average True Range](#head61)
	- [3.3 TRANGE - True Range](#head62)
- [4 Volume Indicators 成交量指标](#head63)
	- [4.1 AD - Chaikin A/D Line 量价指标](#head64)
- [5 Price Transform Functions 价格指标](#head65)
	- [5.1 AVGPRICE - Average Price](#head66)
	- [5.2 MEDPRICE - Median Price](#head67)
	- [5.3 TYPPRICE - Typical Price](#head68)
	- [5.4 WCLPRICE - Weighted Close Price](#head69)
- [6 Cycle Indicator Functionsc 周期指标](#head70)
	- [6.1 HT_DCPERIOD - Hilbert Transform - Dominant Cycle Period](#head71)
	- [6.2 HT_DCPHASE - Hilbert Transform - Dominant Cycle Phase](#head72)
	- [6.3 HT_PHASOR - Hilbert Transform - Phasor Components](#head73)
	- [6.4 HT_SINE - Hilbert Transform - SineWave](#head74)
	- [6.5 HT_TRENDMODE - Hilbert Transform - Trend vs Cycle Mode](#head75)
- [7 Pattern Recognition Functions 形态识别指标](#head76)
	- [7.1 CDL2CROWS - Two Crows](#head77)
	- [7.2 CDL3BLACKCROWS - Three Black Crows](#head78)
	- [7.3 CDL3INSIDE - Three Inside Up/Down](#head79)
	- [7.4 CDL3LINESTRIKE - Three-Line Strike ](#head80)
	- [7.5 CDL3OUTSIDE - Three Outside Up/Down](#head81)
	- [7.6 CDL3STARSINSOUTH - Three Stars In The South](#head82)
	- [7.7 CDL3WHITESOLDIERS - Three Advancing White Soldiers](#head83)
	- [7.8 CDLABANDONEDBABY - Abandoned Baby](#head84)
	- [7.9 CDLADVANCEBLOCK - Advance Block](#head85)
	- [7.10 CDLBELTHOLD - Belt-hold](#head86)
	- [7.11 CDLBREAKAWAY - Breakaway](#head87)
	- [7.12 CDLCLOSINGMARUBOZU - Closing Marubozu](#head88)
	- [7.13 CDLCONCEALBABYSWALL - Concealing Baby Swallow](#head89)
	- [7.14 CDLCOUNTERATTACK - Counterattack](#head90)
	- [7.15 CDLDARKCLOUDCOVER - Dark Cloud Cover](#head91)
	- [7.16 CDLDOJI - Doji](#head92)
	- [7.17 CDLDOJISTAR - Doji Star](#head93)
	- [7.18 CDLDRAGONFLYDOJI - Dragonfly Doji](#head94)
	- [7.19 CDLENGULFING - Engulfing Pattern](#head95)
	- [7.20 CDLEVENINGDOJISTAR - Evening Doji Star](#head96)
	- [7.21 CDLEVENINGSTAR - Evening Star](#head97)
	- [7.22 CDLGAPSIDESIDEWHITE - Up/Down-gap side-by-side white lines](#head98)
	- [7.23 CDLGRAVESTONEDOJI - Gravestone Doji](#head99)
	- [7.24 CDLHAMMER - Hammer](#head100)
	- [7.25 CDLHANGINGMAN - Hanging Man](#head101)
	- [7.26 CDLHARAMI - Harami Pattern](#head102)
	- [7.27 CDLHARAMICROSS - Harami Cross Pattern](#head103)
	- [7.28 CDLHIGHWAVE - High-Wave Candle](#head104)
	- [7.29 CDLHIKKAKE - Hikkake Pattern](#head105)
	- [7.30 CDLHIKKAKEMOD - Modified Hikkake Pattern](#head106)
	- [7.31 CDLHOMINGPIGEON - Homing Pigeon](#head107)
	- [7.32 CDLIDENTICAL3CROWS - Identical Three Crows](#head108)
	- [7.33 CDLINNECK - In-Neck Pattern](#head109)
	- [7.34 CDLINVERTEDHAMMER - Inverted Hammer](#head110)
	- [7.36 CDLKICKINGBYLENGTH - Kicking - bull/bear determined by the longer marubozu](#head111)
	- [7.37 CDLLADDERBOTTOM - Ladder Bottom ](#head112)
	- [7.38 CDLLONGLEGGEDDOJI - Long Legged Doji](#head113)
	- [7.39 CDLLONGLINE - Long Line Candle](#head114)
	- [7.40 CDLMARUBOZU - Marubozu](#head115)
	- [7.41 CDLMATCHINGLOW - Matching Low](#head116)
	- [7.42 CDLMATHOLD - Mat Hold](#head117)
	- [7.43 CDLMORNINGDOJISTAR - Morning Doji Star](#head118)
	- [7.44 CDLMORNINGSTAR - Morning Star](#head119)
	- [7.45 CDLONNECK - On-Neck Pattern](#head120)
	- [7.46 CDLPIERCING - Piercing Pattern](#head121)
	- [7.47 CDLRICKSHAWMAN - Rickshaw Man](#head122)
	- [7.48 CDLRISEFALL3METHODS - Rising/Falling Three Methods](#head123)
	- [7.49 CDLSEPARATINGLINES - Separating Lines](#head124)
	- [7.50 CDLSHOOTINGSTAR - Shooting Star](#head125)
	- [7.51 CDLSHORTLINE - Short Line Candle](#head126)
	- [7.52 CDLSPINNINGTOP - Spinning Top](#head127)
	- [7.53 CDLSTALLEDPATTERN - Stalled Pattern](#head128)
	- [7.54 CDLSTICKSANDWICH - Stick Sandwich](#head129)
	- [7.55 CDLTAKURI - Takuri (Dragonfly Doji with very long lower shadow)](#head130)
	- [7.56 CDLTASUKIGAP - Tasuki Gap](#head131)
	- [7.57 CDLTHRUSTING - Thrusting Pattern](#head132)
	- [7.58 CDLTRISTAR - Tristar Pattern](#head133)
	- [7.59 CDLUNIQUE3RIVER - Unique 3 River](#head134)
	- [7.60 CDLUPSIDEGAP2CROWS - Upside Gap Two Crows](#head135)
	- [7.61 CDLXSIDEGAP3METHODS - Upside/Downside Gap Three Methods](#head136)
- [8 Statistic Functions 统计学指标](#head137)
	- [8.1 BETA - Beta](#head138)
	- [8.2 CORREL - Pearson's Correlation Coefficient (r)](#head139)
	- [8.3 LINEARREG - Linear Regression](#head140)
	- [8.4 LINEARREG_ANGLE - Linear Regression Angle](#head141)
	- [8.5 LINEARREG_INTERCEPT - Linear Regression Intercept](#head142)
	- [8.6 LINEARREG_SLOPE - Linear Regression Slope](#head143)
	- [8.7 STDDEV - Standard Deviation](#head144)
	- [8.8 TSF - Time Series Forecast](#head145)
	- [8.9 VAR - VAR](#head146)
- [9 Math Functions 数学运算](#head147)
	- [9.1 ACOS - Vector Trigonometric ACos](#head148)
	- [9.2 ASIN - Vector Trigonometric ASin](#head149)
	- [9.3 ATAN - Vector Trigonometric ATan](#head150)
	- [9.4 CEIL - Vector Ceil](#head151)
	- [9.5 COS - Vector Trigonometric Cos](#head152)
	- [9.6 COSH - Vector Trigonometric Cosh](#head153)
	- [9.7 EXP - Vector Arithmetic Exp](#head154)
	- [9.8 FLOOR - Vector Floor](#head155)
	- [9.9 LN - Vector Log Natural](#head156)
	- [9.10 LOG10 - Vector Log10](#head157)
	- [9.11 SIN - Vector Trigonometric Sin](#head158)
	- [9.12 SINH - Vector Trigonometric Sinh](#head159)
	- [9.13 SQRT - Vector Square Root](#head160)
	- [9.14 TAN - Vector Trigonometric Tan](#head161)
	- [9.15 TANH - Vector Trigonometric Tanh](#head162)
	- [9.16 ADD - Vector Arithmetic Add](#head163)
	- [9.17 DIV - Vector Arithmetic Div](#head164)
	- [9.18 MAX - Highest value over a specified period](#head165)
	- [9.19 MAXINDEX - Index of highest value over a specified period](#head166)
	- [9.20 MIN - Lowest value over a specified period](#head167)
	- [9.21 MININDEX - Index of lowest value over a specified period](#head168)
	- [9.22 MINMAX - Lowest and highest values over a specified period](#head169)
	- [9.23 MINMAXINDEX - Indexes of lowest and highest values over a specified period](#head170)
	- [9.24 MULT - Vector Arithmetic Mult](#head171)
	- [9.25 SUB - Vector Arithmetic Substraction](#head172)
	- [9.26 SUM - Summation](#head173)

```
安装 
pip install talib
使用
import talib
print(talib.get_functions())
print(talib.get_function_groups())
```

# <span id="head1">1 Overlap Studies Functions 重叠研究指标 </span>

## <span id="head2">1.1 BBANDS - Bollinger Bands</span>

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
## <span id="head3">1.2 DEMA - Double Exponential Moving Average  双移动平均线</span>

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
## <span id="head4">1.3 EMA - Exponential Moving Average</span>

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
## <span id="head5">1.4 HT_TRENDLINE - Hilbert Transform - Instantaneous Trendline</span>
NOTE: The ``HT_TRENDLINE`` function has an unstable period.  

> 函数名：HT_TRENDLINE   
名称： 希尔伯特瞬时变换  
简介：是一种趋向类指标，其构造原理是仍然对价格收盘价进行算术平均，并根据计算结果来进行分析，用于判断价格未来走势的变动趋势。  
[百度文库](https://wenku.baidu.com/view/0e35f6eead51f01dc281f18e.html) 

```python
real = HT_TRENDLINE(close)
```

Learn more about the Hilbert Transform - Instantaneous Trendline at [tadoc.org](http://www.tadoc.org/indicator/HT_TRENDLINE.htm).  
## <span id="head6">1.5 KAMA - Kaufman Adaptive Moving Average 考夫曼的自适应移动平均线</span>

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
## <span id="head7">1.6 MA - Moving average  移动平均线</span>

> 函数名：MA   
名称： 移动平均线  
简介：移动平均线，Moving Average，简称MA，原本的意思是移动平均，由于我们将其制作成线形，所以一般称之为移动平均线，简称均线。它是将某一段时间的收盘价之和除以该周期。 比如日线MA5指5天内的收盘价除以5 。  
[百度百科](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF/217887?fromtitle=MA&fromid=1511750#viewPageContent) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/a04d723659318237?rid=96)   


```python
real = MA(close, timeperiod=30, matype=0)
```

## <span id="head8">1.7 MAMA - MESA Adaptive Moving Average</span>
NOTE: The ``MAMA`` function has an unstable period.  
```python
mama, fama = MAMA(close, fastlimit=0, slowlimit=0)
```

Learn more about the MESA Adaptive Moving Average at [tadoc.org](http://www.tadoc.org/indicator/MAMA.htm).  
## <span id="head9">1.8 MAVP - Moving average with variable period</span>
```python
real = MAVP(close, periods, minperiod=2, maxperiod=30, matype=0)
```

## <span id="head10">1.9 MIDPOINT - MidPoint over period</span>
```python
real = MIDPOINT(close, timeperiod=14)
```

Learn more about the MidPoint over period at [tadoc.org](http://www.tadoc.org/indicator/MIDPOINT.htm).  
## <span id="head11">1.10 MIDPRICE - Midpoint Price over period</span>
```python
real = MIDPRICE(high, low, timeperiod=14)
```

Learn more about the Midpoint Price over period at [tadoc.org](http://www.tadoc.org/indicator/MIDPRICE.htm).  
## <span id="head12">1.11 SAR - Parabolic SAR  抛物线指标</span>

> 函数名：SAR   
名称： 抛物线指标  
简介：抛物线转向也称停损点转向，是利用抛物线方式，随时调整停损点位置以观察买卖点。由于停损点（又称转向点SAR）以弧形的方式移动，故称之为抛物线转向指标    。  
[百度百科](https://baike.baidu.com/item/SAR/2771135#viewPageContent) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/d9d94e65be7f6b5e)   


```python
real = SAR(high, low, acceleration=0, maximum=0)
```

Learn more about the Parabolic SAR at [tadoc.org](http://www.tadoc.org/indicator/SAR.htm).  
## <span id="head13">1.12 SAREXT - Parabolic SAR - Extended</span>
```python
real = SAREXT(high, low, startvalue=0, offsetonreverse=0, accelerationinitlong=0, accelerationlong=0, accelerationmaxlong=0, accelerationinitshort=0, accelerationshort=0, accelerationmaxshort=0)
```

## <span id="head14">1.13 SMA - Simple Moving Average 简单移动平均线</span>

> 函数名：SMA  
名称： 简单移动平均线  
简介：移动平均线，Moving Average，简称MA，原本的意思是移动平均，由于我们将其制作成线形，所以一般称之为移动平均线，简称均线。它是将某一段时间的收盘价之和除以该周期。 比如日线MA5指5天内的收盘价除以5 。  
[百度百科](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF/217887?fromtitle=MA&fromid=1511750#viewPageContent) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/a04d723659318237?rid=96)   


```python
real = SMA(close, timeperiod=30)
```

Learn more about the Simple Moving Average at [tadoc.org](http://www.tadoc.org/indicator/SMA.htm).  
## <span id="head15">1.14 T3 - Triple Exponential Moving Average (T3) 三重指数移动平均线</span>

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
## <span id="head16">1.15 TEMA - Triple Exponential Moving Average</span>

> 函数名：TEMA（T3 区别？）
名称：三重指数移动平均线  


```python
real = TEMA(close, timeperiod=30)
```

Learn more about the Triple Exponential Moving Average at [tadoc.org](http://www.tadoc.org/indicator/TEMA.htm).  
## <span id="head17">1.16 TRIMA - Triangular Moving Average</span>
```python
real = TRIMA(close, timeperiod=30)
```

Learn more about the Triangular Moving Average at [tadoc.org](http://www.tadoc.org/indicator/TRIMA.htm).  
## <span id="head18">1.17 WMA - Weighted Moving Average 移动加权平均法</span>

> 函数名：WMA  
名称：加权移动平均线  
简介：移动加权平均法是指以每次进货的成本加上原有库存存货的成本，除以每次进货数量与原有库存存货的数量之和，据以计算加权平均单位成本，以此为基础计算当月发出存货的成本和期末存货的成本的一种方法。  
[百度百科](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%8A%A0%E6%9D%83%E5%B9%B3%E5%9D%87%E6%B3%95/10056490?fr=aladdin&fromid=16799870&fromtitle=%E5%8A%A0%E6%9D%83%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/262b1dfd1c68ee30)   


```python
real = WMA(close, timeperiod=30)
```

Learn more about the Weighted Moving Average at [tadoc.org](http://www.tadoc.org/indicator/WMA.htm).  


# <span id="head19">2 Momentum Indicator Functions 动量指标函数 </span>
## <span id="head20">2.1 ADX - Average Directional Movement Index</span>
> 函数名：ADX  
名称：平均趋向指数  
简介：使用ADX指标，指标判断盘整、振荡和单边趋势。
### <span id="head21"> 公式：</span>
一、先决定股价趋势（Directional Movement，DM）是上涨或下跌：   
“所谓DM值，今日股价波动幅度大于昨日股价波动幅部分的最大值，可能是创高价的部分或创低价的部分；如果今日股价波动幅度较前一日小，则DM = 0。”   
若股价高点持续走高，为上涨趋势，记作 +DM。   
若为下跌趋势，记作 -DM。-DM的负号（–）是表示反向趋势（下跌），并非数值为负数。   
其他状况：DM = 0。   
二、寻找股价的真实波幅（True Range，TR）：   
所谓真实波幅（TR）是以最高价，最低价，及前一日收盘价三个价格做比较，求出当日股价波动的最大幅度。   
三、趋势方向需经由一段时间来观察，研判上才有意义。一般以14天为指标的观察周期：   
先计算出 +DM、–DM及TR的14日算术平均数，得到 +DM14、–DM14及TR14三组数据作为起始值，再计算各自的移动平均值（EMA）。   
```
    +DI14 = +DM/TR14*100
    -DI14 = +DM/TR14*100
    
    DX = |(+DI14)-(-DI14)| / |(+DI14)+(-DI14)|
    
    DX运算结果取其绝对值，再将DX作移动平均，得到ADX。
```

### <span id="head22">特点：  </span>
* ADX无法告诉你趋势的发展方向。
* 如果趋势存在，ADX可以衡量趋势的强度。不论上升趋势或下降趋势，ADX看起来都一样。
* ADX的读数越大，趋势越明显。衡量趋势强度时，需要比较几天的ADX 读数，观察ADX究竟是上升或下降。ADX读数上升，代表趋势转强；如果ADX读数下降，意味着趋势转弱。
* 当ADX曲线向上攀升，趋势越来越强，应该会持续发展。如果ADX曲线下滑，代表趋势开始转弱，反转的可能性增加。
* 单就ADX本身来说，由于指标落后价格走势，所以算不上是很好的指标，不适合单就ADX进行操作。可是，如果与其他指标配合运用，ADX可以确认市场是否存在趋势，并衡量趋势的强度。

### <span id="head23"> 指标应用：</span>
* +DI与–DI表示多空相反的二个动向，当据此绘出的两条曲线彼此纠结相缠时，代表上涨力道与下跌力道相当，多空势均力敌。当 +DI与–DI彼此穿越时，由下往上的一方其力道开始压过由上往下的另一方，此时出现买卖讯号。
* ADX可作为趋势行情的判断依据，当行情明显朝多空任一方向进行时，ADX数值都会显著上升，趋势走强。若行情呈现盘整格局时，ADX会低于 +DI与–DI二条线。若ADX数值低于20，则不论DI表现如何，均显示市场没有明显趋势。
* ADX持续偏高时，代表“超买”（Overbought）或“超卖”（Oversold）的现象，行情反转的机会将增加，此时则不适宜顺势操作。当ADX数值从上升趋势转为下跌时，则代表行情即将反转；若ADX数值由下跌趋势转为上升时，行情将止跌回升。
* 总言之，DMI指标包含4条线：+DI、-DI、ADX和ADXR。+DI代表买盘的强度、-DI代表卖盘的强度；ADX代表趋势的强度、ADXR则为ADX的移动平均。

NOTE: The ``ADX`` function has an unstable period.  
```python
real = ADX(high, low, close, timeperiod=14)
```

Learn more about the Average Directional Movement Index at [tadoc.org](http://www.tadoc.org/indicator/ADX.htm).  
## <span id="head24">2.2  ADXR- Average Directional Movement Index Rating</span>
> 函数名：ADXR  
名称：平均趋向指数的趋向指数  
简介：使用ADXR指标，指标判断ADX趋势。
NOTE: The ``ADXR`` function has an unstable period.  
```python
real = ADXR(high, low, close, timeperiod=14)
```

Learn more about the Average Directional Movement Index Rating at [tadoc.org](http://www.tadoc.org/indicator/ADXR.htm).  
## <span id="head25">2.3 APO - Absolute Price Oscillator</span>
```python
real = APO(close, fastperiod=12, slowperiod=26, matype=0)
```

Learn more about the Absolute Price Oscillator at [tadoc.org](http://www.tadoc.org/indicator/APO.htm).  
## <span id="head26">2.4 AROON - Aroon</span>
> 函数名：AROON  
名称：阿隆指标  
简介：该指标是通过计算自价格达到近期最高值和最低值以来所经过的期间数，阿隆指标帮助你预测价格趋势到趋势区域（或者反过来，从趋势区域到趋势）的变化。  
#### <span id="head27"> 计算公式：</span>
``` 
Aroon(上升)=[(计算期天数-最高价后的天数)/计算期天数]*100
Aroon(下降)=[(计算期天数-最低价后的天数)/计算期天数]*100
```
#### <span id="head28"> 指数应用</span>
1、极值0和100  
当UP线达到100时，市场处于强势；如果维持在70~100之间，表示一个上升趋势。同样，如果Down线达到0，表示处于弱势，如果维持在0~30之间，表示处于下跌趋势。如果两条线同处于极值水平，则表明一个更强的趋势。  
2、平行运动  
如果两条线平行运动时，表明市场趋势被打破。可以预期该状况将持续下去，只到由极值水平或交叉穿行西安市出方向性运动为止。  
3、交叉穿行  
当下行线上穿上行线时，表明潜在弱势，预期价格开始趋于下跌。反之，表明潜在强势，预期价格趋于走高。  

```python
aroondown, aroonup = AROON(high, low, timeperiod=14)
```

Learn more about the Aroon at [tadoc.org](http://www.tadoc.org/indicator/AROON.htm).  
## <span id="head29">2.5 AROONOSC - Aroon Oscillator</span>
> 函数名：AROONOSC  
名称：阿隆振荡  
简介：
```python
real = AROONOSC(high, low, timeperiod=14)
```

Learn more about the Aroon Oscillator at [tadoc.org](http://www.tadoc.org/indicator/AROONOSC.htm).  
## <span id="head30">2.6 BOP - Balance Of Power 均势</span>
> 函数名：BOP  
名称：均势指标  
简介
```python
real = BOP(open, high, low, close)
```

Learn more about the Balance Of Power at [tadoc.org](http://www.tadoc.org/indicator/BOP.htm).  
## <span id="head31">2.7 CCI - Commodity Channel Index</span>
> 函数名：CCI  
名称：顺势指标  
简介：CCI指标专门测量股价是否已超出常态分布范围

#### <span id="head32"> 指标应用</span>
* 1.当CCI指标曲线在+100线～-100线的常态区间里运行时,CCI指标参考意义不大，可以用KDJ等其它技术指标进行研判。
* 2.当CCI指标曲线从上向下突破+100线而重新进入常态区间时，表明市场价格的上涨阶段可能结束，将进入一个比较长时间的震荡整理阶段，应及时平多做空。
* 3.当CCI指标曲线从上向下突破-100线而进入另一个非常态区间（超卖区）时，表明市场价格的弱势状态已经形成，将进入一个比较长的寻底过程，可以持有空单等待更高利润。如果CCI指标曲线在超卖区运行了相当长的一段时间后开始掉头向上，表明价格的短期底部初步探明，可以少量建仓。CCI指标曲线在超卖区运行的时间越长，确认短期的底部的准确度越高。
* 4.CCI指标曲线从下向上突破-100线而重新进入常态区间时，表明市场价格的探底阶段可能结束，有可能进入一个盘整阶段，可以逢低少量做多。
* 5.CCI指标曲线从下向上突破+100线而进入非常态区间(超买区)时，表明市场价格已经脱离常态而进入强势状态，如果伴随较大的市场交投，应及时介入成功率将很大。
* 6.CCI指标曲线从下向上突破+100线而进入非常态区间(超买区)后，只要CCI指标曲线一直朝上运行，表明价格依然保持强势可以继续持有待涨。但是，如果在远离+100线的地方开始掉头向下时，则表明市场价格的强势状态将可能难以维持，涨势可能转弱，应考虑卖出。如果前期的短期涨幅过高同时价格回落时交投活跃，则应该果断逢高卖出或做空。
* CCI主要是在超买和超卖区域发生作用，对急涨急跌的行情检测性相对准确。非常适用于股票、外汇、贵金属等市场的短期操作。[1] 

```python
real = CCI(high, low, close, timeperiod=14)
```

Learn more about the Commodity Channel Index at [tadoc.org](http://www.tadoc.org/indicator/CCI.htm).  
## <span id="head33">2.8 CMO - Chande Momentum Oscillator 钱德动量摆动指标</span>

> 函数名：CMO  
名称：钱德动量摆动指标  
简介：与其他动量指标摆动指标如相对强弱指标（RSI）和随机指标（KDJ）不同，钱德动量指标在计算公式的分子中采用上涨日和下跌日的数据。
计算公式：CMO=（Su－Sd）*100/（Su+Sd）  
其中：Su是今日收盘价与昨日收盘价（上涨日）差值加总。若当日下跌，则增加值为0；Sd是今日收盘价与做日收盘价（下跌日）差值的绝对值加总。若当日上涨，则增加值为0；


#### <span id="head34"> 指标应用</span>
* 本指标类似RSI指标。  
* 当本指标下穿-50水平时是买入信号，上穿+50水平是卖出信号。  
* 钱德动量摆动指标的取值介于-100和100之间。  
* 本指标也能给出良好的背离信号。  
* 当股票价格创出新低而本指标未能创出新低时，出现牛市背离；  
* 当股票价格创出新高而本指标未能创出新高时，当出现熊市背离时。
* 我们可以用移动均值对该指标进行平滑。

NOTE: The ``CMO`` function has an unstable period.  
```python
real = CMO(close, timeperiod=14)
```

Learn more about the Chande Momentum Oscillator at [tadoc.org](http://www.tadoc.org/indicator/CMO.htm).
## <span id="head35">2.9 DX - Directional Movement Index DMI指标又叫动向指标或趋向指标</span>

> 函数名：DX  
名称：动向指标或趋向指标  
简介：通过分析股票价格在涨跌过程中买卖双方力量均衡点的变化情况，即多空双方的力量的变化受价格波动的影响而发生由均衡到失衡的循环过程，从而提供对趋势判断依据的一种技术指标。  
分析和应用：[百度百科](https://baike.baidu.com/item/DMI%E6%8C%87%E6%A0%87/3423254?fr=aladdin) 
[维基百科](https://zh.wikipedia.org/wiki/%E5%8B%95%E5%90%91%E6%8C%87%E6%95%B8) 
[同花顺学院](http://www.iwencai.com/school/search?cg=100&w=DMI)   

NOTE: The ``DX`` function has an unstable period.  
```python
real = DX(high, low, close, timeperiod=14)
```

Learn more about the Directional Movement Index at [tadoc.org](http://www.tadoc.org/indicator/DX.htm).  
## <span id="head36">2.10 MACD - Moving Average Convergence/Divergence</span>
> 函数名：MACD  
名称：平滑异同移动平均线  
简介：利用收盘价的短期（常用为12日）指数移动平均线与长期（常用为26日）指数移动平均线之间的聚合与分离状况，对买进、卖出时机作出研判的技术指标。  
分析和应用：[百度百科](https://baike.baidu.com/item/MACD%E6%8C%87%E6%A0%87?fromtitle=MACD&fromid=3334786)
[维基百科](https://zh.wikipedia.org/wiki/MACD)
[同花顺学院](http://www.iwencai.com/school/search?cg=100&w=MACD)  
```python
dif, dem, histogram = MACD(close, fastperiod=12, slowperiod=26, signalperiod=9)
```

Learn more about the Moving Average Convergence/Divergence at [tadoc.org](http://www.tadoc.org/indicator/MACD.htm).  
## <span id="head37">2.11 MACDEXT - MACD with controllable MA type</span>

> 函数名：MACDEXT  
名称：平滑异同移动平均线(可控制移动平均算法)  
简介：同MACD函数(固定使用EMA作为matype),并提供参数控制计算DIF, DEM时使用的移动平均算法。计算DIF时使用fastmatype与slowmatype，计算DEM时使用signalmatype，`Histogram = DIF - DEM`。matype参数详见`talib.MA_Type`与`Overlap Studies Functions 重叠研究指标`文档。  
分析和应用：[百度百科](https://baike.baidu.com/item/MACD%E6%8C%87%E6%A0%87?fromtitle=MACD&fromid=3334786)
[维基百科](https://zh.wikipedia.org/wiki/MACD)
[同花顺学院](http://www.iwencai.com/school/search?cg=100&w=MACD)  
```python
dif, dem, histogram = MACDEXT(close, fastperiod=12, fastmatype=0, slowperiod=26, slowmatype=0, signalperiod=9, signalmatype=0)
```

## <span id="head38">2.12 MACDFIX - Moving Average Convergence/Divergence Fix 12/26</span>

> 函数名：MFI  
名称：平滑异同移动平均线(固定快慢均线周期为12/26)  
简介：同MACD函数, 固定快均线周期fastperiod=12, 慢均线周期slowperiod=26.  
```python
dif, dem, histogram = MACDFIX(close, signalperiod=9)
```

## <span id="head39">2.13 MFI - Money Flow Index 资金流量指标</span>

> 函数名：MFI  
名称：资金流量指标    
简介：属于量价类指标，反映市场的运行趋势  
分析和应用：[百度百科](https://baike.baidu.com/item/mfi/7429225?fr=aladdin) 
[同花顺学院](http://www.iwencai.com/school/search?cg=100&w=MFI)  
NOTE: The ``MFI`` function has an unstable period.  
```python
real = MFI(high, low, close, volume, timeperiod=14)
```

Learn more about the Money Flow Index at [tadoc.org](http://www.tadoc.org/indicator/MFI.htm).  
## <span id="head40">2.14 MINUS_DI - Minus Directional Indicator</span>
> 函数名：DMI 中的DI指标 负方向指标    
名称：下升动向值  
简介：通过分析股票价格在涨跌过程中买卖双方力量均衡点的变化情况，即多空双方的力量的变化受价格波动的影响而发生由均衡到失衡的循环过程，从而提供对趋势判断依据的一种技术指标。  
分析和应用：[百度百科](https://baike.baidu.com/item/DMI%E6%8C%87%E6%A0%87/3423254?fr=aladdin) 
[维基百科](https://zh.wikipedia.org/wiki/%E5%8B%95%E5%90%91%E6%8C%87%E6%95%B8) 
[同花顺学院](http://www.iwencai.com/school/search?cg=100&w=DMI) 
NOTE: The ``MINUS_DI`` function has an unstable period.  
```python
real = MINUS_DI(high, low, close, timeperiod=14)
```

Learn more about the Minus Directional Indicator at [tadoc.org](http://www.tadoc.org/indicator/MINUS_DI.htm).  
## <span id="head41">2.15 MINUS_DM - Minus Directional Movement</span>

> 函数名：MINUS_DM   
名称： 上升动向值 DMI中的DM代表正趋向变动值即上升动向值  
简介：通过分析股票价格在涨跌过程中买卖双方力量均衡点的变化情况，即多空双方的力量的变化受价格波动的影响而发生由均衡到失衡的循环过程，从而提供对趋势判断依据的一种技术指标。  
分析和应用：[百度百科](https://baike.baidu.com/item/DMI%E6%8C%87%E6%A0%87/3423254?fr=aladdin) 
[维基百科](https://zh.wikipedia.org/wiki/%E5%8B%95%E5%90%91%E6%8C%87%E6%95%B8) 
[同花顺学院](http://www.iwencai.com/school/search?cg=100&w=DMI)   

NOTE: The ``MINUS_DM`` function has an unstable period.  
```python
real = MINUS_DM(high, low, timeperiod=14)
```

Learn more about the Minus Directional Movement at [tadoc.org](http://www.tadoc.org/indicator/MINUS_DM.htm).  
## <span id="head42">2.16 MOM - Momentum  动量</span>

> 函数名：MOM  
名称： 上升动向值  
简介：投资学中意思为续航，指股票(或经济指数)持续增长的能力。研究发现，赢家组合在牛市中存在着正的动量效应，输家组合在熊市中存在着负的动量效应。   
分析和应用： 
[维基百科](https://zh.wikipedia.org/wiki/%E5%8B%95%E9%87%8F%E6%8C%87%E6%A8%99) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/cb18b2dbe2f455e6)  

```python
real = MOM(close, timeperiod=10)
```

Learn more about the Momentum at [tadoc.org](http://www.tadoc.org/indicator/MOM.htm).  
## <span id="head43">2.17 PLUS_DI - Plus Directional Indicator</span>
NOTE: The ``PLUS_DI`` function has an unstable period.  
```python
real = PLUS_DI(high, low, close, timeperiod=14)
```

Learn more about the Plus Directional Indicator at [tadoc.org](http://www.tadoc.org/indicator/PLUS_DI.htm).  
## <span id="head44">2.18 PLUS_DM - Plus Directional Movement</span>
NOTE: The ``PLUS_DM`` function has an unstable period.  
```python
real = PLUS_DM(high, low, timeperiod=14)
```

Learn more about the Plus Directional Movement at [tadoc.org](http://www.tadoc.org/indicator/PLUS_DM.htm).  
## <span id="head45">2.19 PPO - Percentage Price Oscillator 价格震荡百分比指数</span>

> 函数名：PPO
名称： 价格震荡百分比指数  
简介：价格震荡百分比指标（PPO）是一个和MACD指标非常接近的指标。  
PPO标准设定和MACD设定非常相似：12,26,9和PPO，和MACD一样说明了两条移动平均线的差距，但是它们有一个差别是PPO是用百分比说明。   
分析和应用： 
[参考](http://blog.sina.com.cn/s/blog_7542a31c0101aux9.html) 

```python
real = PPO(close, fastperiod=12, slowperiod=26, matype=0)
```

Learn more about the Percentage Price Oscillator at [tadoc.org](http://www.tadoc.org/indicator/PPO.htm).  
## <span id="head46">2.20 ROC - Rate of change : ((price/prevPrice)-1)*100  变动率指标</span>

> 函数名：ROC   
名称： 变动率指标  
简介：ROC是由当天的股价与一定的天数之前的某一天股价比较，其变动速度的大小,来反映股票市变动的快慢程度  
分析和应用：[百度百科](https://baike.baidu.com/item/ROC%E6%8C%87%E6%A0%87/3081705?fr=aladdin) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/6ac184fdb20d2f59)   

```python
real = ROC(close, timeperiod=10)
```

Learn more about the Rate of change : ((price/prevPrice)-1)*100 at [tadoc.org](http://www.tadoc.org/indicator/ROC.htm).  
## <span id="head47">2.21 ROCP - Rate of change Percentage: (price-prevPrice)/prevPrice</span>
```python
real = ROCP(close, timeperiod=10)
```

Learn more about the Rate of change Percentage: (price-prevPrice)/prevPrice at [tadoc.org](http://www.tadoc.org/indicator/ROCP.htm).  
## <span id="head48">2.22 ROCR - Rate of change ratio: (price/prevPrice)</span>
```python
real = ROCR(close, timeperiod=10)
```

Learn more about the Rate of change ratio: (price/prevPrice) at [tadoc.org](http://www.tadoc.org/indicator/ROCR.htm).  
## <span id="head49">2.23 ROCR100 - Rate of change ratio 100 scale: (price/prevPrice)*100</span>
```python
real = ROCR100(close, timeperiod=10)
```

Learn more about the Rate of change ratio 100 scale: (price/prevPrice)*100 at [tadoc.org](http://www.tadoc.org/indicator/ROCR100.htm).  
## <span id="head50">2.24 RSI - Relative Strength Index  相对强弱指数</span>

> 函数名：RSI  
名称：相对强弱指数     
简介：是通过比较一段时期内的平均收盘涨数和平均收盘跌数来分析市场买沽盘的意向和实力，从而作出未来市场的走势。   
分析和应用：[百度百科](https://baike.baidu.com/item/RSI/6130115) 
[维基百科](https://zh.wikipedia.org/wiki/%E7%9B%B8%E5%B0%8D%E5%BC%B7%E5%BC%B1%E6%8C%87%E6%95%B8) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/6a280c6cebcf140a) 

NOTE: The ``RSI`` function has an unstable period.  
```python
real = RSI(close, timeperiod=14)
```

Learn more about the Relative Strength Index at [tadoc.org](http://www.tadoc.org/indicator/RSI.htm).  
## <span id="head51">2.25 STOCH - Stochastic 随机指标,俗称KD </span>

> 函数名：STOCH  
名称：随机指标,俗称KD 
```python
slowk, slowd = STOCH(high, low, close, fastk_period=5, slowk_period=3, slowk_matype=0, slowd_period=3, slowd_matype=0)
```

Learn more about the Stochastic at [tadoc.org](http://www.tadoc.org/indicator/STOCH.htm).  
## <span id="head52">2.26 STOCHF - Stochastic Fast</span>
```python
fastk, fastd = STOCHF(high, low, close, fastk_period=5, fastd_period=3, fastd_matype=0)
```

Learn more about the Stochastic Fast at [tadoc.org](http://www.tadoc.org/indicator/STOCHF.htm).  
## <span id="head53">2.27 STOCHRSI - Stochastic Relative Strength Index</span>
NOTE: The ``STOCHRSI`` function has an unstable period.  
```python
fastk, fastd = STOCHRSI(close, timeperiod=14, fastk_period=5, fastd_period=3, fastd_matype=0)
```

Learn more about the Stochastic Relative Strength Index at [tadoc.org](http://www.tadoc.org/indicator/STOCHRSI.htm).  
## <span id="head54">2.28 TRIX - 1-day Rate-Of-Change (ROC) of a Triple Smooth EMA</span>
```python
real = TRIX(close, timeperiod=30)
```

Learn more about the 1-day Rate-Of-Change (ROC) of a Triple Smooth EMA at [tadoc.org](http://www.tadoc.org/indicator/TRIX.htm).  
## <span id="head55">2.29 ULTOSC - Ultimate Oscillator 终极波动指标 </span>

> 函数名：ULTOSC  
名称：终极波动指标      
简介：UOS是一种多方位功能的指标，除了趋势确认及超买超卖方面的作用之外，它的“突破”讯号不仅可以提供最适当的交易时机之外，更可以进一步加强指标的可靠度。   
分析和应用：[百度百科](https://baike.baidu.com/item/%E7%BB%88%E6%9E%81%E6%B3%A2%E5%8A%A8%E6%8C%87%E6%A0%87/1982936?fr=aladdin&fromid=12610066&fromtitle=%E7%BB%88%E6%9E%81%E6%8C%87%E6%A0%87) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/e89b98d39da975e4) 

```python
real = ULTOSC(high, low, close, timeperiod1=7, timeperiod2=14, timeperiod3=28)
```

Learn more about the Ultimate Oscillator at [tadoc.org](http://www.tadoc.org/indicator/ULTOSC.htm).  
## <span id="head56">2.30 WILLR - Williams' %R 威廉指标</span>

> 函数名：WILLR  
名称：威廉指标    
简介：WMS表示的是市场处于超买还是超卖状态。股票投资分析方法主要有如下三种：基本分析、技术分析、演化分析。在实际应用中，它们既相互联系，又有重要区别。   
分析和应用：[百度百科](https://baike.baidu.com/item/%E5%A8%81%E5%BB%89%E6%8C%87%E6%A0%87?fr=aladdin) 
[维基百科](https://zh.wikipedia.org/wiki/%E5%A8%81%E5%BB%89%E6%8C%87%E6%A8%99) 
[同花顺学院](http://www.iwencai.com/yike/detail/auid/967febb0316c57c1) 

```python
real = WILLR(high, low, close, timeperiod=14)
```

# <span id="head57">Volume Indicators 成交量指标</span>

## <span id="head58">2.31 AD - Chaikin A/D Line 量价指标</span>
> 函数名：AD  
名称：Chaikin A/D Line 累积/派发线（Accumulation/Distribution Line）  
简介：Marc Chaikin提出的一种平衡交易量指标，以当日的收盘价位来估算成交流量，用于估定一段时间内该证券累积的资金流量。  
计算公式：   
``` A/D = 昨日A/D + 多空对比 * 今日成交量    
多空对比 = [（收盘价- 最低价） - （最高价 - 收盘价）] / （最高价 - 最低价)
 ```
若最高价等于最低价： 多空对比 = （收盘价 / 昨收盘） - 1  
研判：    
1、A/D测量资金流向，向上的A/D表明买方占优势，而向下的A/D表明卖方占优势   
2、A/D与价格的背离可视为买卖信号，即底背离考虑买入，顶背离考虑卖出   
3、应当注意A/D忽略了缺口的影响，事实上，跳空缺口的意义是不能轻易忽略的   
A/D指标无需设置参数，但在应用时，可结合指标的均线进行分析

```python
real = AD(high, low, close, volume)
```

## 2.32 ADOSC - Chaikin A/D Oscillator
> 函数名：ADOSC   
名称：Chaikin A/D Oscillator Chaikin震荡指标   
简介：将资金流动情况与价格行为相对比，检测市场中资金流入和流出的情况   
计算公式：fastperiod A/D - slowperiod A/D   
研判：   
1、交易信号是背离：看涨背离做多，看跌背离做空   
2、股价与90天移动平均结合，与其他指标结合   
3、由正变负卖出，由负变正买进   

```python
real = ADOSC(high, low, close, volume, fastperiod=3, slowperiod=10)
```

## 2.33 OBV - On Balance Volume

> 函数名：OBV   
名称：On Balance Volume 能量潮   
简介：Joe Granville提出，通过统计成交量变动的趋势推测股价趋势   
计算公式：以某日为基期，逐日累计每日上市股票总成交量，若隔日指数或股票上涨
，则基期OBV加上本日成交量为本日OBV。隔日指数或股票下跌，
则基期OBV减去本日成交量为本日OBV   
研判：   
1、以“N”字型为波动单位，一浪高于一浪称“上升潮”，下跌称“跌潮”；上升潮买进，跌潮卖出   
2、须配合K线图走势   
3、用多空比率净额法进行修正，但不知TA-Lib采用哪种方法   
```计算公式： 多空比率净额= [（收盘价－最低价）－（最高价-收盘价）] ÷（ 最高价－最低价）×成交量```  
```python
real = OBV(close, volume)
```

# <span id="head59">3 Volatility Indicator Functions 波动率指标函数  </span>

## <span id="head60">3.1 ATR - Average True Range</span>

> 函数名：ATR  
名称：真实波动幅度均值   
简介：真实波动幅度均值（ATR)是
以 N 天的指数移动平均数平均後的交易波动幅度。 
计算公式：一天的交易幅度只是单纯地 最大值 - 最小值。  
而真实波动幅度则包含昨天的收盘价，若其在今天的幅度之外：  
真实波动幅度 = max(最大值,昨日收盘价) − min(最小值,昨日收盘价) 真实波动幅度均值便是「真实波动幅度」的 N 日 指数移动平均数。  

特性：：  
* 波动幅度的概念表示可以显示出交易者的期望和热情。  
* 大幅的或增加中的波动幅度表示交易者在当天可能准备持续买进或卖出股票。  
* 波动幅度的减少则表示交易者对股市没有太大的兴趣。  

NOTE: The ``ATR`` function has an unstable period.  

```python
real = ATR(high, low, close, timeperiod=14)
```

Learn more about the Average True Range at [tadoc.org](http://www.tadoc.org/indicator/ATR.htm).  
## <span id="head61">3.2 NATR - Normalized Average True Range</span>
> 函数名：NATR  
名称：归一化波动幅度均值   
简介：归一化波动幅度均值（NATR)是

NOTE: The ``NATR`` function has an unstable period.  
```python
real = NATR(high, low, close, timeperiod=14)
```

Learn more about the Normalized Average True Range at [tadoc.org](http://www.tadoc.org/indicator/NATR.htm).  
## <span id="head62">3.3 TRANGE - True Range</span>

> 函数名：TRANGE  
名称：真正的范围   

```python
real = TRANGE(high, low, close)
```


# <span id="head63">4 Volume Indicators 成交量指标</span>

## <span id="head64">4.1 AD - Chaikin A/D Line 量价指标</span>
> 函数名：AD  
名称：Chaikin A/D Line 累积/派发线（Accumulation/Distribution Line）  
简介：Marc Chaikin提出的一种平衡交易量指标，以当日的收盘价位来估算成交流量，用于估定一段时间内该证券累积的资金流量。  
计算公式：   
``` A/D = 昨日A/D + 多空对比 * 今日成交量    
多空对比 = [（收盘价- 最低价） - （最高价 - 收盘价）] / （最高价 - 最低价)
 ```
若最高价等于最低价： 多空对比 = （收盘价 / 昨收盘） - 1  
研判：    
1、A/D测量资金流向，向上的A/D表明买方占优势，而向下的A/D表明卖方占优势   
2、A/D与价格的背离可视为买卖信号，即底背离考虑买入，顶背离考虑卖出   
3、应当注意A/D忽略了缺口的影响，事实上，跳空缺口的意义是不能轻易忽略的   
A/D指标无需设置参数，但在应用时，可结合指标的均线进行分析

```python
real = AD(high, low, close, volume)
```

## 4.2 ADOSC - Chaikin A/D Oscillator
> 函数名：ADOSC   
名称：Chaikin A/D Oscillator Chaikin震荡指标   
简介：将资金流动情况与价格行为相对比，检测市场中资金流入和流出的情况   
计算公式：fastperiod A/D - slowperiod A/D   
研判：   
1、交易信号是背离：看涨背离做多，看跌背离做空   
2、股价与90天移动平均结合，与其他指标结合   
3、由正变负卖出，由负变正买进   

```python
real = ADOSC(high, low, close, volume, fastperiod=3, slowperiod=10)
```

## 4.3 OBV - On Balance Volume

> 函数名：OBV   
名称：On Balance Volume 能量潮   
简介：Joe Granville提出，通过统计成交量变动的趋势推测股价趋势   
计算公式：以某日为基期，逐日累计每日上市股票总成交量，若隔日指数或股票上涨
，则基期OBV加上本日成交量为本日OBV。隔日指数或股票下跌，
则基期OBV减去本日成交量为本日OBV   
研判：   
1、以“N”字型为波动单位，一浪高于一浪称“上升潮”，下跌称“跌潮”；上升潮买进，跌潮卖出   
2、须配合K线图走势   
3、用多空比率净额法进行修正，但不知TA-Lib采用哪种方法   
```计算公式： 多空比率净额= [（收盘价－最低价）－（最高价-收盘价）] ÷（ 最高价－最低价）×成交量```  
```python
real = OBV(close, volume)
```

# <span id="head65">5 Price Transform Functions 价格指标</span>

## <span id="head66">5.1 AVGPRICE - Average Price</span>
> 函数名：AVGPRICE   
名称：平均价格函数
```python
real = AVGPRICE(open, high, low, close)
```

Learn more about the Average Price at [tadoc.org](http://www.tadoc.org/indicator/AVGPRICE.htm).  

## <span id="head67">5.2 MEDPRICE - Median Price</span>
> 函数名：MEDPRICE   
名称：中位数价格
```python
real = MEDPRICE(high, low)
```

Learn more about the Median Price at [tadoc.org](http://www.tadoc.org/indicator/MEDPRICE.htm).  
## <span id="head68">5.3 TYPPRICE - Typical Price</span>
> 函数名：TYPPRICE   
名称：代表性价格

```python
real = TYPPRICE(high, low, close)
```

Learn more about the Typical Price at [tadoc.org](http://www.tadoc.org/indicator/TYPPRICE.htm).  
## <span id="head69">5.4 WCLPRICE - Weighted Close Price</span>
> 函数名：WCLPRICE   
名称：加权收盘价

```python
real = WCLPRICE(high, low, close)
```


# <span id="head70">6 Cycle Indicator Functionsc 周期指标</span>

## <span id="head71">6.1 HT_DCPERIOD - Hilbert Transform - Dominant Cycle Period</span>
> 函数名：HT_DCPERIOD   
名称： 希尔伯特变换-主导周期   
简介：将价格作为信息信号，计算价格处在的周期的位置，作为择时的依据。   

[文库文档](https://wenku.baidu.com/view/0e35f6eead51f01dc281f18e.md)  

NOTE: The ``HT_DCPERIOD`` function has an unstable period.  
```python
real = HT_DCPERIOD(close)
```

Learn more about the Hilbert Transform - Dominant Cycle Period at [tadoc.org](http://www.tadoc.org/indicator/HT_DCPERIOD.htm).  
## <span id="head72">6.2 HT_DCPHASE - Hilbert Transform - Dominant Cycle Phase</span>

> 函数名：HT_DCPHASE   
名称： 希尔伯特变换-主导循环阶段 


NOTE: The ``HT_DCPHASE`` function has an unstable period.  
```python
real = HT_DCPHASE(close)
```

Learn more about the Hilbert Transform - Dominant Cycle Phase at [tadoc.org](http://www.tadoc.org/indicator/HT_DCPHASE.htm).  
## <span id="head73">6.3 HT_PHASOR - Hilbert Transform - Phasor Components</span>
> 函数名：HT_DCPHASE   
名称： 希尔伯特变换-希尔伯特变换相量分量 

NOTE: The ``HT_PHASOR`` function has an unstable period.  
```python
inphase, quadrature = HT_PHASOR(close)
```

Learn more about the Hilbert Transform - Phasor Components at [tadoc.org](http://www.tadoc.org/indicator/HT_PHASOR.htm).  
## <span id="head74">6.4 HT_SINE - Hilbert Transform - SineWave</span>

> 函数名：HT_DCPHASE   
名称： 希尔伯特变换-正弦波 
NOTE: The ``HT_SINE`` function has an unstable period.  
```python
sine, leadsine = HT_SINE(close)
```

Learn more about the Hilbert Transform - SineWave at [tadoc.org](http://www.tadoc.org/indicator/HT_SINE.htm).  

## <span id="head75">6.5 HT_TRENDMODE - Hilbert Transform - Trend vs Cycle Mode</span>

> 函数名：HT_DCPHASE   
名称： 希尔伯特变换-趋势与周期模式  
NOTE: The ``HT_TRENDMODE`` function has an unstable period. 

```python
integer = HT_TRENDMODE(close)
```

# <span id="head76">7 Pattern Recognition Functions 形态识别指标</span>
   
## <span id="head77">7.1 CDL2CROWS - Two Crows</span>
> 函数名：CDL2CROWS   
名称：Two Crows 两只乌鸦   
简介：三日K线模式，第一天长阳，第二天高开收阴，第三天再次高开继续收阴，
收盘比前一日收盘价低，预示股价下跌。

```python
integer = CDL2CROWS(open, high, low, close)
```

## <span id="head78">7.2 CDL3BLACKCROWS - Three Black Crows</span>
> 函数名：CDL3BLACKCROWS   
名称：Three Black Crows 三只乌鸦   
简介：三日K线模式，连续三根阴线，每日收盘价都下跌且接近最低价，
每日开盘价都在上根K线实体内，预示股价下跌。   

```python
integer = CDL3BLACKCROWS(open, high, low, close)
```

## <span id="head79">7.3 CDL3INSIDE - Three Inside Up/Down</span>
> 函数名：CDL3INSIDE   
名称： Three Inside Up/Down 三内部上涨和下跌   
简介：三日K线模式，母子信号+长K线，以三内部上涨为例，K线为阴阳阳，
第三天收盘价高于第一天开盘价，第二天K线在第一天K线内部，预示着股价上涨。
   
```python
integer = CDL3INSIDE(open, high, low, close)
```

## <span id="head80">7.4 CDL3LINESTRIKE - Three-Line Strike </span>
> 函数名：CDL3LINESTRIKE   
名称： Three-Line Strike 三线打击   
简介：四日K线模式，前三根阳线，每日收盘价都比前一日高，
开盘价在前一日实体内，第四日市场高开，收盘价低于第一日开盘价，预示股价下跌。
   
```python
integer = CDL3LINESTRIKE(open, high, low, close)
```

## <span id="head81">7.5 CDL3OUTSIDE - Three Outside Up/Down</span>
> 函数名：CDL3OUTSIDE  
名称：Three Outside Up/Down 三外部上涨和下跌   
简介：三日K线模式，与三内部上涨和下跌类似，K线为阴阳阳，但第一日与第二日的K线形态相反，
以三外部上涨为例，第一日K线在第二日K线内部，预示着股价上涨。  

```python
integer = CDL3OUTSIDE(open, high, low, close)
```

## <span id="head82">7.6 CDL3STARSINSOUTH - Three Stars In The South</span>
> 函数名：CDL3STARSINSOUTH  
名称：Three Stars In The South 南方三星  
简介：三日K线模式，与大敌当前相反，三日K线皆阴，第一日有长下影线，
第二日与第一日类似，K线整体小于第一日，第三日无下影线实体信号，
成交价格都在第一日振幅之内，预示下跌趋势反转，股价上升。  

```python
integer = CDL3STARSINSOUTH(open, high, low, close)
```

## <span id="head83">7.7 CDL3WHITESOLDIERS - Three Advancing White Soldiers</span>
> 函数名：CDL3WHITESOLDIERS   
名称：Three Advancing White Soldiers 三个白兵  
简介：三日K线模式，三日K线皆阳，
每日收盘价变高且接近最高价，开盘价在前一日实体上半部，预示股价上升。

```python
integer = CDL3WHITESOLDIERS(open, high, low, close)
```

## <span id="head84">7.8 CDLABANDONEDBABY - Abandoned Baby</span>
> 函数名：CDLABANDONEDBABY  
名称：Abandoned Baby 弃婴  
简介：三日K线模式，第二日价格跳空且收十字星（开盘价与收盘价接近，
最高价最低价相差不大），预示趋势反转，发生在顶部下跌，底部上涨。  

```python
integer = CDLABANDONEDBABY(open, high, low, close, penetration=0)
```

## <span id="head85">7.9 CDLADVANCEBLOCK - Advance Block</span>
> 函数名：CDLADVANCEBLOCK   
名称：Advance Block 大敌当前   
简介：三日K线模式，三日都收阳，每日收盘价都比前一日高，
开盘价都在前一日实体以内，实体变短，上影线变长。   

```python
integer = CDLADVANCEBLOCK(open, high, low, close)
```

## <span id="head86">7.10 CDLBELTHOLD - Belt-hold</span>
> 函数名：CDLBELTHOLD   
名称：Belt-hold 捉腰带线   
简介：两日K线模式，下跌趋势中，第一日阴线，
第二日开盘价为最低价，阳线，收盘价接近最高价，预示价格上涨。   

```python
integer = CDLBELTHOLD(open, high, low, close)
```

## <span id="head87">7.11 CDLBREAKAWAY - Breakaway</span>
> 函数名：CDLBREAKAWAY  
名称：Breakaway 脱离  
简介：五日K线模式，以看涨脱离为例，下跌趋势中，第一日长阴线，第二日跳空阴线，延续趋势开始震荡，
第五日长阳线，收盘价在第一天收盘价与第二天开盘价之间，预示价格上涨。   

```python
integer = CDLBREAKAWAY(open, high, low, close)
```

## <span id="head88">7.12 CDLCLOSINGMARUBOZU - Closing Marubozu</span>
> 函数名：CDLCLOSINGMARUBOZU   
名称：Closing Marubozu 收盘缺影线  
简介：一日K线模式，以阳线为例，最低价低于开盘价，收盘价等于最高价，
预示着趋势持续。

```python
integer = CDLCLOSINGMARUBOZU(open, high, low, close)
```

## <span id="head89">7.13 CDLCONCEALBABYSWALL - Concealing Baby Swallow</span>
> 函数名：CDLCONCEALBABYSWALL   
名称： Concealing Baby Swallow 藏婴吞没   
简介：四日K线模式，下跌趋势中，前两日阴线无影线
，第二日开盘、收盘价皆低于第二日，第三日倒锤头，
第四日开盘价高于前一日最高价，收盘价低于前一日最低价，预示着底部反转。   

```python
integer = CDLCONCEALBABYSWALL(open, high, low, close)
```

## <span id="head90">7.14 CDLCOUNTERATTACK - Counterattack</span>
> 函数名：CDLCOUNTERATTACK  
名称：Counterattack 反击线  
简介：二日K线模式，与分离线类似。  

```python
integer = CDLCOUNTERATTACK(open, high, low, close)
```

## <span id="head91">7.15 CDLDARKCLOUDCOVER - Dark Cloud Cover</span>
> 函数名：CDLDARKCLOUDCOVER  
名称：Dark Cloud Cover 乌云压顶  
简介：二日K线模式，第一日长阳，第二日开盘价高于前一日最高价，
收盘价处于前一日实体中部以下，预示着股价下跌。  

```python
integer = CDLDARKCLOUDCOVER(open, high, low, close, penetration=0)
```

## <span id="head92">7.16 CDLDOJI - Doji</span>
> 函数名：CDLDOJI  
名称：Doji 十字  
简介：一日K线模式，开盘价与收盘价基本相同。  

```python
integer = CDLDOJI(open, high, low, close)
```

## <span id="head93">7.17 CDLDOJISTAR - Doji Star</span>
> 函数名：CDLDOJISTAR  
名称：Doji Star 十字星  
简介：一日K线模式，开盘价与收盘价基本相同，上下影线不会很长，预示着当前趋势反转。  

```python
integer = CDLDOJISTAR(open, high, low, close)
```

## <span id="head94">7.18 CDLDRAGONFLYDOJI - Dragonfly Doji</span>
> 函数名：CDLDRAGONFLYDOJI  
名称：Dragonfly Doji 蜻蜓十字/T形十字  
简介：一日K线模式，开盘后价格一路走低，
之后收复，收盘价与开盘价相同，预示趋势反转。  

```python
integer = CDLDRAGONFLYDOJI(open, high, low, close)
```

## <span id="head95">7.19 CDLENGULFING - Engulfing Pattern</span>
> 函数名：CDLENGULFING  
名称：Engulfing Pattern 吞噬模式  
简介：两日K线模式，分多头吞噬和空头吞噬，以多头吞噬为例，第一日为阴线，
第二日阳线，第一日的开盘价和收盘价在第二日开盘价收盘价之内，但不能完全相同。  

```python
integer = CDLENGULFING(open, high, low, close)
```

## <span id="head96">7.20 CDLEVENINGDOJISTAR - Evening Doji Star</span>
> 函数名：CDLEVENINGDOJISTAR  
名称：Evening Doji Star 十字暮星  
简介：三日K线模式，基本模式为暮星，第二日收盘价和开盘价相同，预示顶部反转。  

```python
integer = CDLEVENINGDOJISTAR(open, high, low, close, penetration=0)
```

## <span id="head97">7.21 CDLEVENINGSTAR - Evening Star</span>
> 函数名：CDLEVENINGSTAR  
名称：Evening Star 暮星  
简介：三日K线模式，与晨星相反，上升趋势中,
第一日阳线，第二日价格振幅较小，第三日阴线，预示顶部反转。  

```python
integer = CDLEVENINGSTAR(open, high, low, close, penetration=0)
```

## <span id="head98">7.22 CDLGAPSIDESIDEWHITE - Up/Down-gap side-by-side white lines</span>
>函数名：CDLGAPSIDESIDEWHITE  
名称：Up/Down-gap side-by-side white lines 向上/下跳空并列阳线  
简介：二日K线模式，上升趋势向上跳空，下跌趋势向下跳空,
第一日与第二日有相同开盘价，实体长度差不多，则趋势持续。  

```python
integer = CDLGAPSIDESIDEWHITE(open, high, low, close)
```

## <span id="head99">7.23 CDLGRAVESTONEDOJI - Gravestone Doji</span>
> 函数名：CDLGRAVESTONEDOJI  
名称：Gravestone Doji 墓碑十字/倒T十字  
简介：一日K线模式，开盘价与收盘价相同，上影线长，无下影线，预示底部反转。  

```python
integer = CDLGRAVESTONEDOJI(open, high, low, close)
```

## <span id="head100">7.24 CDLHAMMER - Hammer</span>
> 函数名：CDLHAMMER  
名称：Hammer 锤头  
简介：一日K线模式，实体较短，无上影线，
下影线大于实体长度两倍，处于下跌趋势底部，预示反转。  

```python
integer = CDLHAMMER(open, high, low, close)
```

## <span id="head101">7.25 CDLHANGINGMAN - Hanging Man</span>
> 函数名：CDLHANGINGMAN  
名称：Hanging Man 上吊线  
简介：一日K线模式，形状与锤子类似，处于上升趋势的顶部，预示着趋势反转。  

```python
integer = CDLHANGINGMAN(open, high, low, close)
```

## <span id="head102">7.26 CDLHARAMI - Harami Pattern</span>
> 函数名：CDLHARAMI  
名称：Harami Pattern 母子线  
简介：二日K线模式，分多头母子与空头母子，两者相反，以多头母子为例，在下跌趋势中，第一日K线长阴，
第二日开盘价收盘价在第一日价格振幅之内，为阳线，预示趋势反转，股价上升。  

```python
integer = CDLHARAMI(open, high, low, close)
```

## <span id="head103">7.27 CDLHARAMICROSS - Harami Cross Pattern</span>
> 函数名：CDLHARAMICROSS  
名称：Harami Cross Pattern 十字孕线  
简介：二日K线模式，与母子县类似，若第二日K线是十字线，
便称为十字孕线，预示着趋势反转。  

```python
integer = CDLHARAMICROSS(open, high, low, close)
```

## <span id="head104">7.28 CDLHIGHWAVE - High-Wave Candle</span>
> 函数名：CDLHIGHWAVE  
名称：High-Wave Candle 风高浪大线  
简介：三日K线模式，具有极长的上/下影线与短的实体，预示着趋势反转。  

```python
integer = CDLHIGHWAVE(open, high, low, close)
```

## <span id="head105">7.29 CDLHIKKAKE - Hikkake Pattern</span>
> 函数名：CDLHIKKAKE  
名称：Hikkake Pattern 陷阱  
简介：三日K线模式，与母子类似，第二日价格在前一日实体范围内,
第三日收盘价高于前两日，反转失败，趋势继续。  
```python
integer = CDLHIKKAKE(open, high, low, close)
```

## <span id="head106">7.30 CDLHIKKAKEMOD - Modified Hikkake Pattern</span>
> 函数名：CDLHIKKAKEMOD  
名称：Modified Hikkake Pattern 修正陷阱  
简介：三日K线模式，与陷阱类似，上升趋势中，第三日跳空高开；
下跌趋势中，第三日跳空低开，反转失败，趋势继续。
```python
integer = CDLHIKKAKEMOD(open, high, low, close)
```

## <span id="head107">7.31 CDLHOMINGPIGEON - Homing Pigeon</span>
> 函数名：CDLHOMINGPIGEON  
名称：Homing Pigeon 家鸽  
简介：二日K线模式，与母子线类似，不同的的是二日K线颜色相同，
第二日最高价、最低价都在第一日实体之内，预示着趋势反转。  

```python
integer = CDLHOMINGPIGEON(open, high, low, close)
```

## <span id="head108">7.32 CDLIDENTICAL3CROWS - Identical Three Crows</span>
> 函数名：CDLIDENTICAL3CROWS  
名称：Identical Three Crows 三胞胎乌鸦  
简介：三日K线模式，上涨趋势中，三日都为阴线，长度大致相等，
每日开盘价等于前一日收盘价，收盘价接近当日最低价，预示价格下跌。  

```python
integer = CDLIDENTICAL3CROWS(open, high, low, close)
```

## <span id="head109">7.33 CDLINNECK - In-Neck Pattern</span>
>函数名：CDLINNECK  
名称：In-Neck Pattern 颈内线  
简介：二日K线模式，下跌趋势中，第一日长阴线，
第二日开盘价较低，收盘价略高于第一日收盘价，阳线，实体较短，预示着下跌继续。  

```python
integer = CDLINNECK(open, high, low, close)
```

## <span id="head110">7.34 CDLINVERTEDHAMMER - Inverted Hammer</span>
> 函数名：CDLINVERTEDHAMMER  
名称：Inverted Hammer 倒锤头  
简介：一日K线模式，上影线较长，长度为实体2倍以上，
无下影线，在下跌趋势底部，预示着趋势反转。  

```python
integer = CDLINVERTEDHAMMER(open, high, low, close)
```

##7.35 CDLKICKING - Kicking
> 函数名：CDLKICKING  
名称：Kicking 反冲形态  
简介：二日K线模式，与分离线类似，两日K线为秃线，颜色相反，存在跳空缺口。  

```python
integer = CDLKICKING(open, high, low, close)
```

## <span id="head111">7.36 CDLKICKINGBYLENGTH - Kicking - bull/bear determined by the longer marubozu</span>
> 函数名：CDLKICKINGBYLENGTH  
名称：Kicking - bull/bear determined by the longer marubozu 由较长缺影线决定的反冲形态  
简介：二日K线模式，与反冲形态类似，较长缺影线决定价格的涨跌。  

```python
integer = CDLKICKINGBYLENGTH(open, high, low, close)
```

## <span id="head112">7.37 CDLLADDERBOTTOM - Ladder Bottom </span>
> 函数名：CDLLADDERBOTTOM  
名称：Ladder Bottom 梯底  
简介：五日K线模式，下跌趋势中，前三日阴线，
开盘价与收盘价皆低于前一日开盘、收盘价，第四日倒锤头，第五日开盘价高于前一日开盘价，
阳线，收盘价高于前几日价格振幅，预示着底部反转。  

```python
integer = CDLLADDERBOTTOM(open, high, low, close)
```

## <span id="head113">7.38 CDLLONGLEGGEDDOJI - Long Legged Doji</span>

> 函数名：CDLLONGLEGGEDDOJI  
名称：Long Legged Doji 长脚十字  
简介：一日K线模式，开盘价与收盘价相同居当日价格中部，上下影线长，
表达市场不确定性。  

```python
integer = CDLLONGLEGGEDDOJI(open, high, low, close)
```

## <span id="head114">7.39 CDLLONGLINE - Long Line Candle</span>
> 函数名：CDLLONGLINE  
名称：Long Line Candle 长蜡烛  
简介：一日K线模式，K线实体长，无上下影线。  

```python
integer = CDLLONGLINE(open, high, low, close)
```

## <span id="head115">7.40 CDLMARUBOZU - Marubozu</span>
函数名：CDLMARUBOZU   
名称：Marubozu 光头光脚/缺影线  
简介：一日K线模式，上下两头都没有影线的实体，
阴线预示着熊市持续或者牛市反转，阳线相反。  

```python
integer = CDLMARUBOZU(open, high, low, close)
```

## <span id="head116">7.41 CDLMATCHINGLOW - Matching Low</span>
> 函数名：CDLMATCHINGLOW  
名称：Matching Low 相同低价  
简介：二日K线模式，下跌趋势中，第一日长阴线，
第二日阴线，收盘价与前一日相同，预示底部确认，该价格为支撑位。  

```python
integer = CDLMATCHINGLOW(open, high, low, close)
```

## <span id="head117">7.42 CDLMATHOLD - Mat Hold</span>
> 函数名：CDLMATHOLD  
名称：Mat Hold 铺垫  
简介：五日K线模式，上涨趋势中，第一日阳线，第二日跳空高开影线，
第三、四日短实体影线，第五日阳线，收盘价高于前四日，预示趋势持续。  

```python
integer = CDLMATHOLD(open, high, low, close, penetration=0)
```

## <span id="head118">7.43 CDLMORNINGDOJISTAR - Morning Doji Star</span>
>函数名：CDLMORNINGDOJISTAR  
名称：Morning Doji Star 十字晨星  
简介：三日K线模式，
基本模式为晨星，第二日K线为十字星，预示底部反转。  


```python
integer = CDLMORNINGDOJISTAR(open, high, low, close, penetration=0)
```

## <span id="head119">7.44 CDLMORNINGSTAR - Morning Star</span>
> 函数名：CDLMORNINGSTAR  
名称：Morning Star 晨星  
简介：三日K线模式，下跌趋势，第一日阴线，
第二日价格振幅较小，第三天阳线，预示底部反转。  

```python
integer = CDLMORNINGSTAR(open, high, low, close, penetration=0)
```

## <span id="head120">7.45 CDLONNECK - On-Neck Pattern</span>
> 函数名：CDLONNECK  
名称：On-Neck Pattern 颈上线  
简介：二日K线模式，下跌趋势中，第一日长阴线，第二日开盘价较低，
收盘价与前一日最低价相同，阳线，实体较短，预示着延续下跌趋势。  

```python
integer = CDLONNECK(open, high, low, close)
```

## <span id="head121">7.46 CDLPIERCING - Piercing Pattern</span>
> 函数名：CDLPIERCING  
名称：Piercing Pattern 刺透形态  
简介：两日K线模式，下跌趋势中，第一日阴线，第二日收盘价低于前一日最低价，
收盘价处在第一日实体上部，预示着底部反转。
```python
integer = CDLPIERCING(open, high, low, close)
```

## <span id="head122">7.47 CDLRICKSHAWMAN - Rickshaw Man</span>
> 函数名：CDLRICKSHAWMAN  
名称：Rickshaw Man 黄包车夫  
简介：一日K线模式，与长腿十字线类似，
若实体正好处于价格振幅中点，称为黄包车夫。  

```python
integer = CDLRICKSHAWMAN(open, high, low, close)
```

## <span id="head123">7.48 CDLRISEFALL3METHODS - Rising/Falling Three Methods</span>
> 函数名：CDLRISEFALL3METHODS
名称：Rising/Falling Three Methods 上升/下降三法  
简介： 五日K线模式，以上升三法为例，上涨趋势中，
第一日长阳线，中间三日价格在第一日范围内小幅震荡，
第五日长阳线，收盘价高于第一日收盘价，预示股价上升。  

```python
integer = CDLRISEFALL3METHODS(open, high, low, close)
```

## <span id="head124">7.49 CDLSEPARATINGLINES - Separating Lines</span>
> 函数名：CDLSEPARATINGLINES  
名称：Separating Lines 分离线  
简介：二日K线模式，上涨趋势中，第一日阴线，第二日阳线，
第二日开盘价与第一日相同且为最低价，预示着趋势继续。  

```python
integer = CDLSEPARATINGLINES(open, high, low, close)
```

## <span id="head125">7.50 CDLSHOOTINGSTAR - Shooting Star</span>
> 函数名：CDLSHOOTINGSTAR  
名称：Shooting Star 射击之星  
简介：一日K线模式，上影线至少为实体长度两倍，
没有下影线，预示着股价下跌  
```python
integer = CDLSHOOTINGSTAR(open, high, low, close)
```

## <span id="head126">7.51 CDLSHORTLINE - Short Line Candle</span>
> 函数名：CDLSHORTLINE  
名称：Short Line Candle 短蜡烛  
简介：一日K线模式，实体短，无上下影线  

```python
integer = CDLSHORTLINE(open, high, low, close)
```

## <span id="head127">7.52 CDLSPINNINGTOP - Spinning Top</span>
> 函数名：CDLSPINNINGTOP  
名称：Spinning Top 纺锤  
简介：一日K线，实体小。  

```python
integer = CDLSPINNINGTOP(open, high, low, close)
```

## <span id="head128">7.53 CDLSTALLEDPATTERN - Stalled Pattern</span>
> 函数名：CDLSTALLEDPATTERN  
名称：Stalled Pattern 停顿形态  
简介：三日K线模式，上涨趋势中，第二日长阳线，
第三日开盘于前一日收盘价附近，短阳线，预示着上涨结束  

```python
integer = CDLSTALLEDPATTERN(open, high, low, close)
```

## <span id="head129">7.54 CDLSTICKSANDWICH - Stick Sandwich</span>
> 函数名：CDLSTICKSANDWICH  
名称：Stick Sandwich 条形三明治  
简介：三日K线模式，第一日长阴线，第二日阳线，开盘价高于前一日收盘价，
第三日开盘价高于前两日最高价，收盘价于第一日收盘价相同。  

```python
integer = CDLSTICKSANDWICH(open, high, low, close)
```

## <span id="head130">7.55 CDLTAKURI - Takuri (Dragonfly Doji with very long lower shadow)</span>
> 函数名：CDLTAKURI  
名称：Takuri (Dragonfly Doji with very long lower shadow) 
探水竿  
简介：一日K线模式，大致与蜻蜓十字相同，下影线长度长。  

```python
integer = CDLTAKURI(open, high, low, close)
```

## <span id="head131">7.56 CDLTASUKIGAP - Tasuki Gap</span>
> 函数名：CDLTASUKIGAP  
名称：Tasuki Gap 跳空并列阴阳线  
简介：三日K线模式，分上涨和下跌，以上升为例，
前两日阳线，第二日跳空，第三日阴线，收盘价于缺口中，上升趋势持续。  

```python
integer = CDLTASUKIGAP(open, high, low, close)
```

## <span id="head132">7.57 CDLTHRUSTING - Thrusting Pattern</span>
> 函数名：CDLTHRUSTING  
名称：Thrusting Pattern 插入  
简介：二日K线模式，与颈上线类似，下跌趋势中，第一日长阴线，第二日开盘价跳空，
收盘价略低于前一日实体中部，与颈上线相比实体较长，预示着趋势持续。  

```python
integer = CDLTHRUSTING(open, high, low, close)
```

## <span id="head133">7.58 CDLTRISTAR - Tristar Pattern</span>
> 函数名：CDLTRISTAR  
名称：Tristar Pattern 三星  
简介：三日K线模式，由三个十字组成，
第二日十字必须高于或者低于第一日和第三日，预示着反转。  

```python
integer = CDLTRISTAR(open, high, low, close)
```

## <span id="head134">7.59 CDLUNIQUE3RIVER - Unique 3 River</span>
> 函数名：CDLUNIQUE3RIVER  
名称：Unique 3 River 奇特三河床  
简介：三日K线模式，下跌趋势中，第一日长阴线，第二日为锤头，最低价创新低，第三日开盘价低于第二日收盘价，收阳线，
收盘价不高于第二日收盘价，预示着反转，第二日下影线越长可能性越大。  

```python
integer = CDLUNIQUE3RIVER(open, high, low, close)
```

## <span id="head135">7.60 CDLUPSIDEGAP2CROWS - Upside Gap Two Crows</span>
> 函数名：CDLUPSIDEGAP2CROWS  
名称：Upside Gap Two Crows 向上跳空的两只乌鸦  
简介：三日K线模式，第一日阳线，第二日跳空以高于第一日最高价开盘，
收阴线，第三日开盘价高于第二日，收阴线，与第一日比仍有缺口。  

```python
integer = CDLUPSIDEGAP2CROWS(open, high, low, close)
```

## <span id="head136">7.61 CDLXSIDEGAP3METHODS - Upside/Downside Gap Three Methods</span>
> 函数名：CDLXSIDEGAP3METHODS  
名称：Upside/Downside Gap Three Methods 上升/下降跳空三法  
简介：五日K线模式，以上升跳空三法为例，上涨趋势中，第一日长阳线，第二日短阳线，第三日跳空阳线，第四日阴线，开盘价与收盘价于前两日实体内，
第五日长阳线，收盘价高于第一日收盘价，预示股价上升。  

```python
integer = CDLXSIDEGAP3METHODS(open, high, low, close)
```


# <span id="head137">8 Statistic Functions 统计学指标</span>
## <span id="head138">8.1 BETA - Beta</span>
> 函数名：BETA  
名称：β系数也称为贝塔系数   
简介：一种风险指数，用来衡量个别股票或
股票基金相对于整个股市的价格波动情况
贝塔系数衡量股票收益相对于业绩评价基准收益的总体波动性，是一个相对指标。 β 越高，意味着股票相对于业绩评价基准的波动性越大。 β 大于 1 ，
则股票的波动性大于业绩评价基准的波动性。反之亦然。
用途：   
1）计算资本成本，做出投资决策（只有回报率高于资本成本的项目才应投资）；   
2）计算资本成本，制定业绩考核及激励标准；   
3）计算资本成本，进行资产估值（Beta是现金流贴现模型的基础）；   
4）确定单个资产或组合的系统风险，用于资产组合的投资管理，特别是股指期货或其他金融衍生品的避险（或投机）     

```python
real = BETA(high, low, timeperiod=5)
```

Learn more about the Beta at [tadoc.org](http://www.tadoc.org/indicator/BETA.htm).  
## <span id="head139">8.2 CORREL - Pearson's Correlation Coefficient (r)</span>
> 函数名：CORREL  
名称：皮尔逊相关系数   
简介：用于度量两个变量X和Y之间的相关（线性相关），其值介于-1与1之间  
皮尔逊相关系数是一种度量两个变量间相关程度的方法。它是一个介于 1 和 -1 之间的值，
其中，1 表示变量完全正相关， 0 表示无关，-1 表示完全负相关。
```python
real = CORREL(high, low, timeperiod=30)
```

Learn more about the Pearson's Correlation Coefficient (r) at [tadoc.org](http://www.tadoc.org/indicator/CORREL.htm).  
## <span id="head140">8.3 LINEARREG - Linear Regression</span>
>直线回归方程：当两个变量x与y之间达到显著地线性相关关系时,应用最小二乘法原理确定一条最优直线的直线方程y=a+bx,这条回归直线与个相关点的距离比任何其他直线与相关点的距离都小,是最佳的理想直线.
回归截距a：表示直线在y轴上的截距,代表直线的起点.  
回归系数b：表示直线的斜率,他的实际意义是说明x每变化一个单位时,影响y平均变动的数量.
即x每增加1单位,y变化b个单位.  


> 函数名：LINEARREG  
名称：线性回归   
简介：来确定两种或两种以上变量间相互依赖的定量关系的一种统计分析方法  
其表达形式为y = w'x+e，e为误差服从均值为0的正态分布。

```python
real = LINEARREG(close, timeperiod=14)
```

Learn more about the Linear Regression at [tadoc.org](http://www.tadoc.org/indicator/LINEARREG.htm).  
## <span id="head141">8.4 LINEARREG_ANGLE - Linear Regression Angle</span>
> 函数名：LINEARREG_ANGLE  
名称：线性回归的角度   
简介：来确定价格的角度变化. 
[参考](http://blog.sina.com.cn/s/blog_14c9f45b20102vv8p.md)
```python
real = LINEARREG_ANGLE(close, timeperiod=14)
```

Learn more about the Linear Regression Angle at [tadoc.org](http://www.tadoc.org/indicator/LINEARREG_ANGLE.htm).  
## <span id="head142">8.5 LINEARREG_INTERCEPT - Linear Regression Intercept</span>
> 函数名：LINEARREG_INTERCEPT  
名称：线性回归截距  
```python
real = LINEARREG_INTERCEPT(close, timeperiod=14)
```

Learn more about the Linear Regression Intercept at [tadoc.org](http://www.tadoc.org/indicator/LINEARREG_INTERCEPT.htm).  
## <span id="head143">8.6 LINEARREG_SLOPE - Linear Regression Slope</span>
> 函数名：LINEARREG_SLOPE  
名称：线性回归斜率指标

```python
real = LINEARREG_SLOPE(close, timeperiod=14)
```

Learn more about the Linear Regression Slope at [tadoc.org](http://www.tadoc.org/indicator/LINEARREG_SLOPE.htm).  
## <span id="head144">8.7 STDDEV - Standard Deviation</span>
> 函数名：STDDEV  
名称：标准偏差   
简介：种量度数据分布的分散程度之标准，用以衡量数据值偏离算术平均值的程度。标准偏差越小，这些值偏离平均值就越少，反之亦然。标准偏差的大小可通过标准偏差与平均值的倍率关系来衡量。

```python
real = STDDEV(close, timeperiod=5, nbdev=1)
```

Learn more about the Standard Deviation at [tadoc.org](http://www.tadoc.org/indicator/STDDEV.htm).  
## <span id="head145">8.8 TSF - Time Series Forecast</span>

> 函数名：TSF  
名称：时间序列预测   
简介：一种历史资料延伸预测，也称历史引伸预测法。是以时间数列所能反映的社会经济现象的发展过程和规律性，进行引伸外推，预测其发展趋势的方法


```python
real = TSF(close, timeperiod=14)
```

Learn more about the Time Series Forecast at [tadoc.org](http://www.tadoc.org/indicator/TSF.htm).  
## <span id="head146">8.9 VAR - VAR</span>
> 函数名：  VAR
名称：方差   
简介：方差用来计算每一个变量（观察值）与总体均数之间的差异。为避免出现离均差总和为零，离均差平方和受样本含量的影响，统计学采用平均离均差平方和来描述变量的变异程度

```python
real = VAR(close, timeperiod=5, nbdev=1)
```


# <span id="head147">9 Math Functions 数学运算</span>
## <span id="head148">9.1 ACOS - Vector Trigonometric ACos</span>
> 函数名：ACOS 
名称：acos函数是反余弦函数，三角函数   
  
  
```python
real = ACOS(close)
```

## <span id="head149">9.2 ASIN - Vector Trigonometric ASin</span>
> 函数名：ASIN 
名称：反正弦函数，三角函数
  
```python
real = ASIN(close)
```

## <span id="head150">9.3 ATAN - Vector Trigonometric ATan</span>
> 函数名：ASIN 
名称：数字的反正切值，三角函数

```python
real = ATAN(close)
```

## <span id="head151">9.4 CEIL - Vector Ceil</span>
> 函数名：CEIL 
简介：向上取整数

```python
real = CEIL(close)
```

## <span id="head152">9.5 COS - Vector Trigonometric Cos</span>
> 函数名：COS 
名称：余弦函数，三角函数
```python
real = COS(close)
```

## <span id="head153">9.6 COSH - Vector Trigonometric Cosh</span>
> 函数名：COSH 
名称：双曲正弦函数，三角函数
```python
real = COSH(close)
```

## <span id="head154">9.7 EXP - Vector Arithmetic Exp</span>
> 函数名：EXP 
名称：指数曲线，三角函数

```python
real = EXP(close)
```

## <span id="head155">9.8 FLOOR - Vector Floor</span>
> 函数名：FLOOR   
名称：向下取整数

```python
real = FLOOR(close)
```

## <span id="head156">9.9 LN - Vector Log Natural</span>
> 函数名：LN   
名称：自然对数

```python
real = LN(close)
```

## <span id="head157">9.10 LOG10 - Vector Log10</span>
> 函数名：LOG10   
名称：对数函数log

```python
real = LOG10(close)
```

## <span id="head158">9.11 SIN - Vector Trigonometric Sin</span>
> 函数名：SIN 
名称：正弦函数，三角函数
```python
real = SIN(close)
```

## <span id="head159">9.12 SINH - Vector Trigonometric Sinh</span>
> 函数名：SINH 
名称：双曲正弦函数，三角函数

```python
real = SINH(close)
```

## <span id="head160">9.13 SQRT - Vector Square Root</span>
> 函数名：SQRT 
名称：非负实数的平方根

```python
real = SQRT(close)
```

## <span id="head161">9.14 TAN - Vector Trigonometric Tan</span>
> 函数名：TAN 
名称：正切函数，三角函数
```python
real = TAN(close)
```

## <span id="head162">9.15 TANH - Vector Trigonometric Tanh</span>
> 函数名：TANH 
名称：双曲正切函数，三角函数
```python
real = TANH(close)
```

## <span id="head163">9.16 ADD - Vector Arithmetic Add</span>
> 函数名：ADD   
名称：向量加法运算

```python
real = ADD(high, low)
```

## <span id="head164">9.17 DIV - Vector Arithmetic Div</span>
> 函数名：DIV   
名称：向量除法运算
```python
real = DIV(high, low)
```

## <span id="head165">9.18 MAX - Highest value over a specified period</span>
> 函数名：MAX   
名称：周期内最大值（未满足周期返回nan）
```python
real = MAX(close, timeperiod=30)
```

## <span id="head166">9.19 MAXINDEX - Index of highest value over a specified period</span>
> 函数名：MAXINDEX   
名称：周期内最大值的索引   
```python
integer = MAXINDEX(close, timeperiod=30)
```

## <span id="head167">9.20 MIN - Lowest value over a specified period</span>
> 函数名：MIN   
名称：周期内最小值 （未满足周期返回nan）
```python
real = MIN(close, timeperiod=30)
```

## <span id="head168">9.21 MININDEX - Index of lowest value over a specified period</span>
> 函数名：MININDEX   
名称：周期内最小值的索引 
```python
integer = MININDEX(close, timeperiod=30)
```

## <span id="head169">9.22 MINMAX - Lowest and highest values over a specified period</span>
> 函数名：MINMAX   
名称：周期内最小值和最大值(返回元组````元组（array【最小】，array【最大】）```)
```python
min, max = MINMAX(close, timeperiod=30)
```

## <span id="head170">9.23 MINMAXINDEX - Indexes of lowest and highest values over a specified period</span>
> 函数名：MINMAX   
名称：周期内最小值和最大值索引(返回元组````元组（array【最小】，array【最大】）```)
```python
minidx, maxidx = MINMAXINDEX(close, timeperiod=30)
```

## <span id="head171">9.24 MULT - Vector Arithmetic Mult</span>
> 函数名：MULT   
名称：向量乘法运算
```python
real = MULT(high, low)
```

## <span id="head172">9.25 SUB - Vector Arithmetic Substraction</span>
> 函数名：SUB   
名称：向量减法运算
```python
real = SUB(high, low)
```
## <span id="head173">9.26 SUM - Summation</span>
> 函数名：SUM   
名称：周期内求和
```python
real = SUM(close, timeperiod=30)
```
