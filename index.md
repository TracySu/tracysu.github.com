---
layout: page
title: Post List
tagline: 
---
{% include JB/setup %}


The site is not finished yet, will be finished after my exams

Here are my articles finished ages ago, will put something new soon...

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



