---
layout: page
permalink: /publications/
title: publications
description: academic and other publications
# years: [2022, 2015, 2016]
category: [academic, other publications]
tags: University-of-Passau AIDMI
nav: true
nav_order: 3

---
<!-- _pages/publications.md -->

<!-- 
{%- for y in page.years %} 
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

{%- for y in page.category %}
  <h2 class="category">{{y}}</h2>
  {% bibliography -f papers -q @*[category={{y}}]* %}
{% endfor %}
-->

<div class="publications">

{%- for y in page.category %}
  <h2 class="category">{{y}}</h2>
  {% bibliography -f papers -q @*[category={{y}}]* %}
{% endfor %}

</div>