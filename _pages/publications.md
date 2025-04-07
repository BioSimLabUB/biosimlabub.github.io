---
layout: page
permalink: /publications/
title: publications
description: our interesting findings 🕵️
years: [2025, 2024, 2023, 2022, 2020, 2019, 2016, 2014, 2010, 2009]
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
