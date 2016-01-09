---
layout: page
title: I M B Y
tagline: art with arms contending
---
{% include JB/setup %}

## David Maddalena *Works*
Visit the [category page](http://www.imby.net/categories.html) for a roadmap. Travel through time below.

Featured: [audio](http://www.imby.net/categories.html#audio-ref) and [video](http://www.imby.net/categories.html#video-ref) collages&mdash;[At First The Words](http://www.imby.net/20151107/first-the-words/) blends clips from a popular animated film with a song by Fol Chen ...

&nbsp;

## p o s t s


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
