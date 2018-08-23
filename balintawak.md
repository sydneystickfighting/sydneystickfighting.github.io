---
layout: default
title: Balintawak
permalink: balintawak
---

{% assign listing = site.balintawak | sort: 'order'  %}
{%- for item in listing -%}
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{%- endfor -%}
