---
layout: default
title: İletişim
permalink: /courselist/
---

<ul>
  {% for course in site.courses %}
  <li>
    <h2><a href="{{ course.url }}">{{ course.title }}</a></h2>
    <p>{{ course.content | markdownify }}</p>
  </li>
  {% endfor %}
</ul>
