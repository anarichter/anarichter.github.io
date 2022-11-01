---
layout: page
permalink: /publications/
title: publications
description: academic publications
years: [2022]
# years: [2022, 2019, 2016, 2015]
nav: true
nav_order: 3
# category: [academic, other publications]
# tags: University-of-Passau AIDMI

---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>