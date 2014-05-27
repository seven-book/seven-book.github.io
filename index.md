---
layout: default
title: 首页
---

欢迎光临《FreeSWITCH权威指南》官方网站。新书即将上市，敬请期待。关注右侧的FreeSWITCH-CN微信公众账号获取更多内容更新。&rarr;

<br>
<br>
由于本书 太“厚”了，因此将一部分附录以电子版形式发布，请在此下载<a href="/download/FSDG-Appendix.pdf" target="_blank" onclick=”_gaq.push(['_trackEvent','Download','PDF',this.href]);”>电子版附录</a>。
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
