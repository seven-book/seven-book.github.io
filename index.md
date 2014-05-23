---
layout: default
title: 首页
---

欢迎光临《FreeSWITCH权威指南》官方网站。新书即将上市，敬请期待。

<br>
<br>
<br>

## 最新动态
<hr>

<ul class="posts">
  {% for post in site.posts limit:30 %}
    <li><span>{{ post.date | date: "%Y-%m-%d" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}

</ul>

<br><br>
