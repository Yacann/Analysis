---
permalink: /theorems
layout: page
title: Список теорем
---

<ul>
  {% for th in site.posts %}
    <li>
      <a href=".{{ th.url }}">{{ th.title }}</a>
    </li>
  {% endfor %}
</ul>
