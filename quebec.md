---
layout: default
title: Quebec Serrada
permalink: quebec
---

{% assign listing = site.quebec | sort: 'order'  %}
{%- for item in listing -%}
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{%- endfor -%}
