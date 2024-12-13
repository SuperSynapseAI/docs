---
layout: default
permalink: /sp2pwhitepaper/
title: sp2P WhitePaper
---

<ul>
  {% for post in site.posts %}
    {% if post.categories contains 'sp2PWhitePaper' %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span>{{ post.date | date: "%Y-%m-%d" }}</span>
      </li>
    {% endif %}
  {% endfor %}
</ul>
