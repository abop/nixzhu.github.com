---
layout: page
title: I'm NIX
tagline: 
---
{% include JB/setup %}

开始使用Jekyll+Markdown+git+GitHub写博客。

###Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

