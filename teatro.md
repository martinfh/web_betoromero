---
title: Teatro
layout: default
---
<ul>
  {% for obras in site.categories.obra %}    
 + <a href="web_betoromero{{ obras.url }}">{{ obras.title }}</a><br>
  {% endfor %}
</ul>