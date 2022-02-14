---
layout: page
title: I M B Y
tagline: art with arms contending
---
{% include JB/setup %}

## D.P. Maddalena *Works*

David Maddalena is a technologist by virtue of his location and occasional occupation, and an artist in spirit and vocation; he works with pictures, paragraphs, and people. Visit the [category page](http://www.imby.net/categories.html) for a roadmap; track [tags](http://www.imby.net/tags.html) to drill down; or travel through time below.

&nbsp;

<table cellpadding='5'>
  <tr>
    <td width='175' valign='top'>
      <h2>f e a t u r e d</h2>
      <p><strong>Read</strong> <a href='http://www.imby.net/tags.html#Echoes%20of%20a%20Future%20Truth-ref'>selections</a> from my fiction project, <em>Echoes of a Future Truth</em></p>
      <p><strong>View</strong> <a href='http://www.imby.net/20140223/collected-collages'>collected collages</a> spanning 2005-2016. If you like your collage with more action, <a href='http://www.imby.net/categories.html#video-ref'>video collages</a> blend audio with video clips&mdash;<a href='20150801/first-the-words'>At First The Words</a> blends clips from a certain popular 1930s animated film with music by Fol Chen.</p>
      <p><strong>Listen</strong> to <a href='http://www.imby.net/categories.html#audio-ref'>audio collages</a>, especially my poetic interpretation of a virtual assistant that interrupts your drive-time tunes with a little wisdom energy to give you <em>real</em> <a href='20140520/Starting-Directions-To'>directions</a>.</p>
     <p> <strong>learn more</strong> about what other things the creator <a href='http://maddalena.imby.net'>gets up to</a>. </p>
    </td>
    <td>
      <h2>&nbsp; &nbsp; &nbsp; p o s t s</h2> 

      <ul class="posts">
     {% for post in site.posts %}
     <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
     {% endfor %}
      </ul>
    </td>
  </tr>
 </table>

