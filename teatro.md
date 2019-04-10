---
title: Teatro
layout: default
---
<ul>
  {% for obras in site.categories.obra %}    
 + <a href="{{site.baseurl}}{{ obras.url }}">{{ obras.title }}</a><br>
  {% endfor %}
</ul>