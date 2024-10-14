---
permalink: /theorems
layout: page
title: Список теорем
---

<ul>
  {% for th in site.theorems %}
    <li>
      <a href=".{{ th.url }}">{{ th.title }}</a>
    </li>
  {% endfor %}
</ul>
