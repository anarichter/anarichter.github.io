---
layout: page
permalink: /publications/
title: publications
description: academic and other publications
years: [2022, 2015]
# years: [2022, 2019, 2016, 2015]
nav: true
nav_order: 5
category: [academic, policy support, report]
# tags: University-of-Passau AIDMI

#  {%- for c in page.category %}
#    <h2 class="year">{{c}}</h2>
#    {% bibliography -f papers -q @*[category={{c}}]* %}
#  {% endfor %}

---
<!-- _pages/publications.md -->

<div class="publications">
  
  {%- for y in page.years %}
    <h2 class="year">{{y}}</h2>
    {% bibliography -f papers -q @*[year={{y}}]* %}
  {% endfor %}

</div>