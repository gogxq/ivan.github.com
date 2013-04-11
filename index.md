---
layout: page
title: Not Just One
tagline: About reading,thinking,travel and all trip of my life
---
{% include JB/setup %}


## ×îĞÂÕÂ£º

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
