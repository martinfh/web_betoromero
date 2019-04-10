---
title: Teatro
layout: default
---
<ul>
  {% for obras in site.categories.obra %}    
 + <a href="{{ obras.url }}">{{ obras.title }}</a><br>
  {% endfor %}
</ul>