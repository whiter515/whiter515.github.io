---
layout: page
title: Projects
comments: true
permalink: /projects/
---

* content
{:toc} 

## 云锋金融用户画像展示系统
* Time: 2020.11-2020.12
* Website: 
* 产品功能: 用户标签多级查询、图表展示、辅助数据分析、运营报表。
* 开发过程: 
   * 前后端分离，后端进行跨域配置，token令牌验证； 
   * 前端：Vue + elementUI ，axios发送请求，Echarts进行图表可视化； 
   * 后端：Python Flask框架搭建数据接口，MySQL存储标签数据，Redis实现缓存。


## 有鱼股票新闻热点下发推荐
* Time: 2020.11-2020.12
* Website: 
* 产品功能: 财经新闻feed流热点推荐接口，按时间间隔动态刷新。
* 开发过程: 
   * 数据采集：Python Scrapy框架，请求、解析网页，去重、存储。
   * 文本处理：Bert向量化、DBSCAN热点聚类，NLP话题描述生成。
   * 热点召回：热度排名算法、定时刷新top话题、提供数据接口。


## DCIC 2020-天池智慧海洋建设算法赛
* Time: 2020.01-2020.03
* Website: [tianchi.aliyun.com/competition](https://tianchi.aliyun.com/competition/entrance/231768/introduction)
* 赛题描述: 通过分析渔船北斗设备位置数据，预测渔船的生产作业行为。
* 开发过程: 
   * 特征预处理：纬度坐标、上报时间、速度、航向等进行特征衍生。
   * 时序分类：通过时间划窗统计特征，使用LightGBM分类。
   * 最终结果：使用F1进行评估，在调参+交叉验证后，线上验证集排名66/3551。

## 二手车竞品网站爬虫
* Time: 2020.11-2020.12
* Website: 
* 产品功能: 对竞品网站进行定期的数据采集，辅助运营团队进行数据分析。
* 开发过程: 
   * 基于Python Selenium+Webdriver采集流程。
   * 包括代理IP、断点爬取、网页去重、爬虫监控等功能。
