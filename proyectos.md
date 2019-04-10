---
title: Proyectos
layout: biobeto
---

<ul>
  {% for proyectos in site.categories.proyectos %}
    
+ <a href="{{ proyectos.url }}">{{ proyectos.title }}</a><br>
  
  {% endfor %}
 
</ul>