# wdzj_spider

- R语言网贷之家数据爬虫(共抓取18个字段)

- python网贷之家数据爬虫(共抓取18个字段)

----------------------------------------------------------------------------------------------------------------------------------------
# 爬虫目标

抓取网贷之家平台数据，爬虫网站：http://shuju.wdzj.com/

![爬虫网站](https://github.com/laidefa/wdzj_spider/raw/master/resource/web.png)


---------------------------------------------------------------------------------------------------------------------------------------
# 自定义爬虫

- python:可设定按月抓取和按天抓取（灵活）

- R：只能抓取昨日数据（固定）


### 设置按天抓取

- shujuDate <- "2018-01-232018-01-23"


### 设置按月抓取

- shujuDate <- "2018-01-012018-01-31"

----------------------------------------------------------------------------------------------------------------------------------------
# 抓取效果
共18个字段

- 平台名称
- 成交量
- 平均参考收益率
- 平均借款期限
- 资金净流入
- 待还余额
- 满标用时
- 注册资本
- 运营时间
- 借款标数
- 投资人数
- 人均投资金额
- 前十大土豪待收金额占比
- 借款人数
- 人均借款金额
- 前十大借款人待还金额占比
- 平台背景
- 发展指数排名



![数据](https://github.com/laidefa/wdzj_spider/raw/master/resource/result.png)

----------------------------------------------------------------------------------------------------------------------------------------
# R语言需要安装包

- install.packages("XML")

- install.packages("RCurl")

- install.packages("RJSONIO")

----------------------------------------------------------------------------------------------------------------------------------------

# python 需要安装包

- pip install numpy

- pip install pandas

- pip install requests

- pip install json

- pip install xlsxwriter


----------------------------------------------------------------------------------------------------------------------------------------
# R语言需要导入包

- library(XML)

- library(RCurl)

- library(RJSONIO)

----------------------------------------------------------------------------------------------------------------------------------------

# python 需要导入包

- import requests

- import  json

- import xlsxwriter

----------------------------------------------------------------------------------------------------------------------------------------
# R语言主要技术

- R语言如何发送post请求

- R语言如何解析json,fromJSON函数的使用（来自RJSONIO包）

- R语言数据处理，合并数据框，重命名。

- R语言写出excel。

----------------------------------------------------------------------------------------------------------------------------------------
# python 主要技术

- python如何发送post请求

- python如何解析json,json包的使用。

- python 如何指定列写入excel工作簿。



---------------------------------------------------------------------------------------------------------------------------------------



