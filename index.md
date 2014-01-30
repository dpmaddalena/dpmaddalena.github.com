---
layout: page
title: Made Glorious Summer
tagline: Verbosion
---
{% include JB/setup %}

## David Maddalena on the web
    
## Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


