---
layout: page
title: 尘世客
---
尘世客博客。

本人略通网络营销与seo，熟悉google搜索技巧，擅与思考总结与自我学习，习惯利用搜索引擎解决问题。

尘世客喻意茫茫尘世中匆匆过客。

#### 最近发布的文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
