# 京东爬虫

## 抓取评论的关键字

* 用户ID
* 评论内容
* 会员级别
* 点赞数
* 回复数
* 评价星级
* 购买时间
* 手机型号

## 抓取原理

* 分析京东评论界面数据来源及url规律

* 利用requests库访问json格式评论信息

## 运行环境

* Chrome 版本 72.0.3626.109（正式版本） （64 位）
* Python 3.5.2 :: Anaconda 4.2.0 (64-bit)

## 前置库

* requests
* json
* fake_useragent
* numpy
* time
* BeautifulSoup

## 使用方法
### 爬取脚本SpiderScript.py
将文件下载到本地，cmd进入该文件夹

![1551882088853](https://github.com/YuleZhang/JDComment_Spider/blob/master/picture/Snipaste_2019-03-06_22-22-48.PNG) 
(注意：在爬取数据之前，尽量确保网络的稳定，这能提高爬虫的效率，爬完所有数据，会存到data目录下的csv文件中)

### 数据处理脚本JDComment_Processing.ipynb
使用Jupyter notebook/lab打开ipynb文件，随后shift+enter逐步执行，即可看到数据处理过程(每个单元格的执行情况)

## 数据处理

在JDComment_Processing中包含了数据清洗、数据分析的整个过程（附注释与分析），使用的IDE是jupyter。数据规模有限，分析过程仅供参考。