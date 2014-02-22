---
layout: page
title: Made Glorious Summer
tagline: art with arms contending
---
{% include JB/setup %}

## David Maddalena *Works*  
Writing and poetry from 25 years of putting down heavy words, punctuated with an ongoing pretence to the visual arts by the systematic cutting up of other people's images and gluing them together into ostensibly original works.
    
## p o s t s


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
