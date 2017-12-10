# 知乎亿级数据的爬虫案例
2017 年 9 月 20 日，知乎宣布个人注册用户总数超过 1 亿，日活跃用户量达 2600 万。    
我学习 Python 差不多半个月时间了，决定做一个有挑战性的项目。通过网上查询信息，发现很多人都在爬知乎网站，其中不乏各种精彩的项目，
看得我心里痒痒的，进而产生了这个初步的想法：尝试抓取知乎亿级用户信息。由于水平有限以及反爬虫机制，肯定会遇到许多困难，
在此做一点儿微小的记录，希望与大家共同交流学习。

## 示例

## 更新日志
* 2017-12-10
  - 使用 Scrapy 单机抓取，存入 MongoDB，遭遇知乎反爬虫。
  - 添加 README
  - ~~模拟知乎登录成功~~
## 思路分析

## 注意事项

## 安装使用

## TODO
* 部署分布式Scrapy，多机器部署。
* 反爬虫机制
  - 使用 Cookie 池
  - 使用代理池
* 模拟登录，下载验证码输入。
