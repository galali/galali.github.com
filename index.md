---
layout: page
title: 旮旯里
tagline: 
---
 {% include JB/setup %}

这里是旮旯里的主页。
<br>

旮旯里的涵义，既是尘封，也是积淀，更是回忆与见证。
<br>
<br>

### 以下是旮旯里的一些文章
<br>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



