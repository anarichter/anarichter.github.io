---
layout: page
permalink: /publications/
title: publications
description: academic and other publications
years: [2022, 2015, 2016]
categories: [academic, other publications]
tags: University-of-Passau AIDMI
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

<div class="publications">

{%- for y in page.categories %}
  <h2 class="categories">{{y}}</h2>
  {% bibliography -f papers -q @*[categories={{y}}]* %}
{% endfor %}

</div>