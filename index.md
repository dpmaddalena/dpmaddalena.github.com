---
layout: page
title: I M B Y
tagline: art with arms contending
---
{% include JB/setup %}

## David Maddalena *Works*
Visit the [category page](http://www.imby.net/categories.html) for a roadmap. Travel through time below.

**Featured**: [video](http://www.imby.net/categories.html#video-ref) collages&mdash;[At First The Words](www.imby.net/20150801/first-the-words) blends clips from a certain popular 1930s animated film with music by Fol Chen; [Stage Videos](www.imby.net/20160109/picture-atlantic-convenient-lovers/) are video collages made to be projected behind a band on stage, like for example *Picture Atlantic*.

&nbsp;

## p o s t s


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
