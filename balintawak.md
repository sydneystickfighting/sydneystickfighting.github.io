---
layout: default
title: Balintawak
permalink: balintawak
---

{%- for item in site.balintawak -%}
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{%- endfor -%}
