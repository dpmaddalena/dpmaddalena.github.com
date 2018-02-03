---
layout: page
title: I M B Y
tagline: art with arms contending
---
{% include JB/setup %}

## David Maddalena *Works*
Visit the [category page](http://www.imby.net/categories.html) for a roadmap. Travel through time below.

**Featured**: View the [collected collages](http://www.imby.net/20140223/collected-collages) spanning 2005-2016; if you like your collage with a little bit more action, [video](http://www.imby.net/categories.html#video-ref) collages&mdash;[At First The Words](20150801/first-the-words) blends clips from a certain popular 1930s animated film with music by Fol Chen; [Lost World](20170520/lost-world) samples a new series of works created from full-length silent films and intended for display during a listening session or stage set.

&nbsp;

## p o s t s


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
