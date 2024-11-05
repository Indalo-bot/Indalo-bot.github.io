---
layout: home
title: Home
---

# Bienvenido a mi Blog

¡Hola! Este es mi blog donde hablo sobre temas interesantes y comparto mis pensamientos.

## Últimas Publicaciones

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
