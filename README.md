# 爬取和分析电影《流浪地球》的猫眼评论（十万条评论告诉你，给《流浪地球》评1星的都是什么心态？）

<h1 text-align="center">这是从其他仓库找到的代码，未经原仓库主任许可请勿复制分发</h1> 

<h1>仅用于学习和参考</h1>

>注意：需要提前安装MonGoDB数据库，方便实用爬虫，因此如果你需要从头到尾直接开始执行，就需要你将数据库安装好，并安装准备相应的数据
>使用过程中如果不需要从爬虫开始，那么就自己修改语句导入数据


项目主要爬取电影《流浪地球》的猫眼评论，把评论保存到mongodb，并且分析该电影出现低分的原因

主要的文件为：
- comment_crawler.py：爬取电影《流浪地球》的猫眼评论的代码（带说明和注释，需要安装MongoDB数据库）
- TheWanderingEarth.ipynb：Jupyter notebook代码，分析该电影的评论和评分
- data.csv: 从MongoDB提取出来的10万条数据
- stopwords.txt: 停用词表

#### 运行环境：

- python3.6
- 本地MongoDB数据库

#### 需要安装的包：
- requests
- pymongo
- pyecharts
- pandas
- numpy
- jieba

**注：具体分析说明可以关注微信公众号：[Alfred数据室](https://wx1.sinaimg.cn/mw690/007yVcwsgy1g03lo67ikoj30u00f0ta0.jpg)，阅读对应文章《[十万条评论告诉你，给<流浪地球>评1星的都是什么心态？](https://mp.weixin.qq.com/s/3d_ycK0D1KfbjQJ3m7FhEQ)》**


## Crawling and analysing MaoYan comments of The Wandering Earth

This project Crawls MaoYan comments of The Wandering Earth, and saves the comments data into MongoDB. It reveals the reason why the movie is getting some bad reputation.
The main files are listed below:
- comment_crawler.py：codes for crawling MaoYan comments of The Wandering Earth(with annotation, MOngoDB
needs to be installed.)
- TheWanderingEarth.ipynb：Jupyter notebook for analysing the comments and scores
- data.csv: 100000+ comment data extracted from MongoDB
- stopwords.txt: list of stop words

#### Python environment
- Python3.6
- MongoDB

#### Packages need to be installed
- requests
- pymongo
- pyecharts
- pandas
- numpy
- jieba

**Notice: you can find the detailed document by following Alfred's wechat official account: [Alfred_Lab](https://wx1.sinaimg.cn/mw690/007yVcwsgy1g03lo67ikoj30u00f0ta0.jpg)**