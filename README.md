# PythonProject_Movie-Data-Clrawler-Visualization-Recommended
Movie-Data-Clrawler-Visualization-Recommended.

项目简介


（1）项目概要：

利用Python，通过爬取豆瓣电影数据，进行数据分析与可视化，并基于分析结果实现电影推荐功能。

（2）主要功能实现情况：

·  数据爬取： 使用Python的Requests库发送HTTP请求获取豆瓣电影Top250页面的HTML内容，通过BeautifulSoup库解析页面，使用fake_useragent生成随机的User-Agent模拟浏览器请求，成功爬取电影数据和用户评分数据。

·  数据分析： 使用Numpy、Pandas和Matplotlib库对获取的电影数据进行去重、统计分析（如上映年份分布、评分分布、电影类别统计）、相关性分析等。

·  数据可视化： 利用Matplotlib绘制各种图表展示数据分析结果，使用Pyecharts同时结合前端技术（HTML, CSS, JavaScript）实现交互式数据可视化。

·  电影推荐：

1.热门推荐 (rec_hot_movies)： 根据电影的评分和上映时间筛选，推荐评分较高且最近上映的电影。

2.个性化推荐： 根据用户历史评分记录，选择用户喜欢的电影（评分大于等于4分），随机选择部分电影作为推荐基础，实现简单的电影推荐功能。

（3）项目的开发环境/运行环境：

开发环境： Python 3.x, Jupyter Notebook 

运行环境： 可在任何支持Python的环境下运行，建议使用Anaconda环境管理工具，推荐Jupyter Notebook 

其他详见项目设计报告
