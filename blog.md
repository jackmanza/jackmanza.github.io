---
layout: default
title: Devlog
permalink: /blog/
---

# Devlog

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
  </li>
{% endfor %}
</ul>

<p><a href="{{ '/' | relative_url }}">&larr; Back home</a></p>
