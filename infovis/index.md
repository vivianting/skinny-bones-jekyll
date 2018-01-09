---
layout: archive
title: "可视化作品集"
date: 2018-1-7T15:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature:
  teaser:
  
---
<style>
h4{background: #ff4d4d; color:white; border-radius:6px; padding:6px;}
h5{background: #1a8dff; color:white; border-radius:3px; padding:3px;}
</style>

<h4>五大药房在中国的分布情况</h4>
大参林_国大药房_老百姓_同仁堂_一心堂

此研究根据高德地图搜索结果得出<b>4271笔</b>数据

<div class="row">
<div class="col-sm-4" markdown="1"><!-- left -->
##### 总数比较：五大药房在中国的分布总数相差不大
最少的是同仁堂，有825所；

最多的是国大药房，有875所。
![总数比较](https://vivianting.github.io/images/pharmacy_2.png)


##### 地图：上海市居冠

大参林主要分布在两广地区，一心堂大多分布在我国西南部，在云南省最为集中
老百姓、同仁堂的分布范围较广，在新疆、甘肃也有分布


- 大参林、一心堂的分布显示为集中性。大参林主要分布在两广地区，一心堂大多分布在我国西南部，在云南省最为集中
- 老百姓、同仁堂的分布范围较广，在新疆、甘肃也有分布
- 同仁堂主要分布在中部和东部地区
- 国大药房的分布也体现出了聚集分布的特征，体现为在各个省份的某一块区域的聚集分布
![地图](https://vivianting.github.io/images/pharmacy_map.png)

</div> 
<div class="col-sm-7" markdown="1" ><!-- right -->



<hr>

<br/>
		
<div class="tiles">
{% for post in site.categories.posts infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>