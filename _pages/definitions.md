---
permalink: /definitions
layout: page
title: Список определений
---

<ul>
  {% for def in site.definitions %}
    <li>
      <a href=".{{ def.url }}">{{ def.title }}</a>
    </li>
  {% endfor %}
</ul>
