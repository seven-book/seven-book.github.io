---
layout: tags
title: {{ site.com }}
---

<h1>所有标签</h1>

<div id='tag_cloud'>
{% for tag in site.tags %}
<a href="#{{ tag[0] }}" title="{{ tag[0] }}" rel="{{ tag[1].size }}">{{ tag[0] }}</a>
{% endfor %}
</div>

<br>
<hr>
<br>

<ul id='tag_list'>
{% for tag in site.tags %}
  <li class='tag_item' id='{{ tag[0] }}'>
    <span class='tag_name'>{{ tag[0] }}</span>
    <span>
      <ul>
      {% for post in tag[1] %}
        <li class='tag_post'><a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
      {% endfor %}
      </ul>
    </span>
  </li>
{% endfor %}
</ul>
