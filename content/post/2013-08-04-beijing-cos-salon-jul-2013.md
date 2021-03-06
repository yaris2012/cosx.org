---
title: COS数据分析沙龙第十二期（北京）
date: '2013-08-04T21:58:23+00:00'
author: COS编辑部
categories:
  - 新闻通知
  - 统计之都
  - 职业事业
tags:
  - COS沙龙
slug: beijing-cos-salon-jul-2013
---

&nbsp;

<p style="text-align: center;">
  <em><strong>by <a href="http://weibo.com/xzhman">肖展航</a></strong></em><a href="https://cos.name/wp-content/uploads/2013/08/cos101.jpg"><img class="aligncenter size-large wp-image-8088" alt="cos101" src="https://cos.name/wp-content/uploads/2013/08/cos101-500x362.jpg" width="500" height="362" srcset="https://cos.name/wp-content/uploads/2013/08/cos101-500x362.jpg 500w, https://cos.name/wp-content/uploads/2013/08/cos101-300x217.jpg 300w, https://cos.name/wp-content/uploads/2013/08/cos101-413x300.jpg 413w, https://cos.name/wp-content/uploads/2013/08/cos101.jpg 854w" sizes="(max-width: 500px) 100vw, 500px" /></a>
</p>

&nbsp;

2013年7月28日，第十二期COS数据分析沙龙（北京站）在明德主楼1016如期举行。顶着这个夏天第二个高温橙色预警，本次嘉宾，来自中科院地理资源所的王江浩先生（@沐洲）为大家呈现了主题为“时空统计和时空数据可视化”的精彩讲座。

**王江浩先生**现为中国科学院地理科学与资源资源研究所，资源与环境信息系统国家重点实验室在读博士生；他的专业为遥感与地理信息系统，博士期间主要从事时空地统计学（Spatio-temporal Geostatistics）的相关研究工作；他现已发表学术论文10余篇，其中SCI收录6篇（第一作者2篇），EI检索2篇。他是GIS开源社区（OSGeo）的爱好者和推动者，熟练掌握R、Python、Javascript、IDL等开发语言；他长期关注遥感与地理空间大数据分析与可视化，乐于交流推崇开源与共享；雅安地震时，他第一时间制作了 四川雅安地震信息的可视化，方便关心雅安的网民及时了解[雅安地震信息](http://jianghao.github.io/earthquake/index.htm)。
  
<!--more-->


  
本次嘉宾站在时空统计学发展演进路径的角度，从以概率论为基础，以独立同分布为假设的“经典统计学”到存在空间自相关、空间异质性和各向异性的“空间统计学”，再到更为复杂的“时空统计学”，依次呈现开来。

在与会者了解了基本的时空统计特征之后，嘉宾着重介绍了R中的时空数据分析。按照类型上讲，有三类：第一类是R中的时间序列分析，R中的基础包涉及到关于许多时间序列的函数，例如：stat包里定义了时间和日期的数据结构，forecast和tseries包里包含了预测和单变量建模等等。自动安装所有的时序相关的包的指令如下：

    
    install.packages("ctv") 
    library("ctv")
    install.views(”TimeSeries") 
    update.views("TimeSeries")
    

第二类是R中的空间数据分析，安装环境的指令如下：

    
    install.views(“Spatial”)
    

在R中，空间统计核心包可以分成三类：输入输出数据（rgdal，maptools，maps等）；空间数据清理和操作（sp，maptools，raster）以及空间统计分析（Spatstat，gstat，geoR等）。

值得注意的是，空间数据结构在sp基础包下定义为点、线、面、栅格。读入和写出空间数据，以rgdal为例，需要调用readGDAL() / writeGDAL() ，readOGR() / writeOGR() 函数。很多地理信息系统（GIS）软件可以跟R交互，例如：spgrass6包则为R和 GRASS GIS提供了接口，RPyGeo包则在R中通过Python和ArcGIS提供了借口。

&nbsp;

第三类是R中的空间统计分析。嘉宾向大家讲述了地统计分析、点模式分析、格数据分析和轨迹数据分析这四类以及对应的R语言中的包的操作。

嘉宾对时空可视化钻研之深刻，从给大家带来了视觉上和思想上的冲击波可以窥见。

嘉宾在分享了自己专业方面的收获后，向大家展示了课余娱乐时间开发的可视化项目。R中的时序图、日历图和栅格数据、矢量数据、时空数据可视化，D3、Rchart等十八般武艺信手拈来。其中，mvtsplot包下的mvtsplot()函数更是让大家感受到可视化对于提取时空数据信息的重要作用。Web下的可视化主要利用到了网络地图，利用谷歌地图和R展示了H7N9和雅安地震的热力图ggmap{heatmap()}，不禁让人想起了第六届R语言会议上萌主（@Yummy_zhou）为大家展示的动态交互图。

[幻灯片下载](https://cos.name/wp-content/uploads/2013/08/时空统计与时空数据可视化_COS.pdf)

来自百度、新浪、豆瓣、微软、中航工业集团、京东商城、新华网、6City、友盟、随视传媒、中国统计信息咨询中心、际恒集团、博识教育、中科院、北京邮电大学、北京大学、清华大学、中国人民大学、北京理工大学、华中科技大学的业界人士和高校学生以及创业者逾30余人报名参与了此次活动，席间与嘉宾积极互动，围绕主题展开了深入精彩的讨论。

报名嘉宾中填写的报名理由如下图：

[<img class="aligncenter size-full wp-image-8089" alt="cos102" src="https://cos.name/wp-content/uploads/2013/08/cos102.jpg" width="239" height="217" />](https://cos.name/wp-content/uploads/2013/08/cos102.jpg)

&nbsp;

[<img class="aligncenter size-large wp-image-8090" alt="cos103" src="https://cos.name/wp-content/uploads/2013/08/cos103-364x500.jpg" width="364" height="500" srcset="https://cos.name/wp-content/uploads/2013/08/cos103-364x500.jpg 364w, https://cos.name/wp-content/uploads/2013/08/cos103-218x300.jpg 218w, https://cos.name/wp-content/uploads/2013/08/cos103.jpg 687w" sizes="(max-width: 364px) 100vw, 364px" />](https://cos.name/wp-content/uploads/2013/08/cos103.jpg)
  
[更多沙龙信息](https://cos.name/salon)
