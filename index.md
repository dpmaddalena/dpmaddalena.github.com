---
layout: page
title: Made Glorious Summer
tagline: Made Glorious Summer
---
{% include JB/setup %}

## David Maddalena *Works*  
Writings and poetry from 25-plus years of putting down heavy words.
    
## Pieces


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
