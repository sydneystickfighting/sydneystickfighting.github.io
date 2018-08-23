---
layout: default
title: Ammara & Sinawali
permalink: ammara-sinawali
---

{% assign listing = site.sinawali | sort: 'order'  %}
{%- for item in listing -%}
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{%- endfor -%}
