---
layout: page
title: Scala and Web Development Newsletter
tagline: Supporting tagline
---
{% include JB/setup %}

## Weekly Newsletter

If you are interested [subscribe](http://eepurl.com/bf06MH) to the weekly Newsletter.

The  issues:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


