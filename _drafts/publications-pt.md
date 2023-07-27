---
layout: page
permalink: /publications/
title: publicações
# description: academic and other publications
lang: en
years: [2022, 2015]
lang: pt-br
# years: [2022, 2019, 2016, 2015]
nav: true
nav_order: 2
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