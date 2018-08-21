---
layout: default
title: Balintawak
permalink: balintawak
---

{%- for item in site.balintawak -%}
  <a href="{{ item.url }}">{{ item.title }}</a>
{%- endfor -%}
