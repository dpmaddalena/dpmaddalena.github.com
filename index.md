---
layout: page
title: I M B Y
tagline: art with arms contending
---
{% include JB/setup %}

## David Maddalena *Works*
Visit the [category page](http://www.imby.net/categories.html) for a roadmap. Everything is below, newest at the top. 

Featured: [audio](http://www.imby.net/categories.html#audio-ref) and [video](http://www.imby.net/categories.html#video-ref) collages 

&nbsp;

## p o s t s


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
