---
layout: default
title: Ammara & Sinawali
permalink: ammara-sinawali
---

{%- for item in site.sinawali -%}
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{%- endfor -%}
