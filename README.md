# wordpress-operations

网站名称| umasou's Blog!-探寻电影的世界
---|---
域名地址 | http://huangj0830.me/
IP地址 | 13.58.92.30
站长 | 黄婧 161013041


### 一. 策划文档
##### 1. 网站建设目标
提供一个给学生发表影评的平台，有影评作品的学生可以在这个平台展示自己的影评作品，其他对电影感兴趣的同学也可以在影评文章下方评论自己的其他看法。

##### 2. 目标用户画像
（1）同学A，喜欢电影，对电影有自己的一些见解，想过要分享出来  
（2）同学B，喜欢电影但理解不深，想通过别人的看法加深自己对电影的理解  
（3）同学C，喜欢浏览影评，并作为爱好来日常阅读

##### 3. 网站规划
第一阶段：建立平台后，上传已有的影评  
第二阶段：收集更多学生写的的影评上传，每周更新3篇文章，更新内容为文章形式。  
第三阶段：向学生们推广网站，鼓励学生多表达，根据阅读数据设置奖励机制，激励学生写出更多的作品。


##### 6. DVF模型分析
**可行性**  
1. 看电影作为同学们日常娱乐消遣活动，在聚餐闲聊得知，许多同学希望获得最新的电影资讯，平时也会在公众号阅读影评的推文  
2. 有些同学会自己写影评，但学校暂时没有一个平台让学生发表自己的影评作品  
3. 使用wordpress建立影评分享平台，不需要花很多的成本，运营方法简单易上手    

**可持续性**  
1. 现在校内征集影评稿件后，保证网站能按计划更新，于是就可以在校内推广网站，让学生知道有这个平台，就能收到更多影评作品  
2. 根据阅读数据设置奖励机制，可以激励学生写出更多的作品，网站浏览人数达到一定流量后可以跟商家合作，利用网站流量优势适当增添广告位  
3. 定期进行用户调研，调整优化用户体验，巩固用户黏度，增加用户忠实度  
  
**用户需求**  
1. 获取当下热门电影咨询，征集与这些电影有关的影评稿件  
2. 希望作者能及时回复评论区优质评论，增加优质用户存在感  
  

##### 网站地图  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/sitemap.png)

## 用户研究
#### 一、用户研究成果
##### 用户采访
采访对象：16级网络与新媒体5名学生  
采访内容设计：主要是针对网站的视觉界面设计与功能设计进行问题设计与提问。  

**采访结果总结如下**  
1. 页面部分：只有文字式目录太过单调  
2. 文章部分：文章内容的图片下方文字加粗效果显得太过于不和谐
3. 侧边栏部分：文章的侧边栏的分类目录与菜单栏内容重复，可将侧边栏改为标签

##### AB texting
测试对象：16级网络与新媒体5名学生，其中一名同学同时接受AB两个方案的测试  
测试内容设计：针对首页是一个列表式静态页面好，还是一个轮播图式动态页面好，是否存在不同需求的问题进行AB测试。  
测试结果总结：通过测试发现，用户对页面是一个列表式静态页面还是轮播图式动态页面页面并没有什么需求，只要页面排版整齐合理即可。  
用户采访与AB测试音频文件链接：  

#### 二、设计改进
以下的设计改进均是根据上述用户研究成果中得出的总结进行的
1. 页面部分  
根据用户采访反馈的页面中文章标题展示太单调的问题，进行了改进，用SiteOrigin Page Builder插件对页面进行了分栏处理，把页面每行等分成3部分，分别添加每篇文章特色图片和说明并加上超链接。改进后用户可直观地看到有哪些文章及文章主题，增加可读性  
页面改进前  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/page1.png)  
页面改进后  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/page2.png)

2. 文章部分  
根据用户采访反馈的文章内容的图片下方文字加粗效果显得太过于单调的问题，进行了改进，取消加粗效果，增加斜体效果，在不显得突兀的同时也区分了与文章内容主题的部分  
文章内容的图片下方文字改进前  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/word%20blod.png)  
文章内容的图片下方文字改进后  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/word%20no%20blod.png)

3. 侧边栏部分  
根据用户采访反馈的侧边栏的分类目录与菜单栏内容重复，进行了改进，将其换成了标签  
侧边栏的功能设计改进前    
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/tag1.png)  
侧边栏的功能设计改进后  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/tag2.png)

4. AB测试的改进
根据AB测试的结果，用户对页面是一个列表式静态页面还是轮播图式动态页面页面并没有什么需求，只要页面排版整齐即可的结论，为了不显单调，首页采用了渐变式轮播图式的动态页面  
AB测试的设计改前  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/home1.png)  
AB测试的设计改后  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/home2.png)

#### 三、定制化
1. 安装插件对原创内容安全保护  
安装了WP Content Copy Protection & No Right Click插件，该插件可以对网站内容进行保护，设置完成后网站访客无法使用右键复制，此操作对作品的保护起到一定的作用  
插件设置证明图  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/nocopy.png)  
![image](https://github.com/Huangj0830/wordpress-operations/blob/master/img/nocopy2.png)
