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
<div class="col-sm-7" markdown="1"><!-- left -->
##### 总数比较：五大药房在中国的分布总数相差不大
最少的是同仁堂，有825所；最多的是国大药房，有875所
![总数比较](https://vivianting.github.io/images/pharmacy_2.png)



		
<div class="tiles">
{% for post in site.categories.posts infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>