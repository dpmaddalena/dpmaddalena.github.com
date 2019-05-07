---
layout: page
title: I M B Y
tagline: art with arms contending
---
{% include JB/setup %}

## D.P. Maddalena *Works*
Visit the [category page](http://www.imby.net/categories.html) for a roadmap. Travel through time below.

**Featured**: View the [collected collages](http://www.imby.net/20140223/collected-collages) spanning 2005-2016; if you like your collage with more action, [video collages](http://www.imby.net/categories.html#video-ref) blend audio with video mashups&mdash;[At First The Words](20150801/first-the-words) blends clips from a certain popular 1930s animated film with music by Fol Chen; learn more about the creator at his [ego page](http://maddalena.imby.net). 

&nbsp;

## p o s t s


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
