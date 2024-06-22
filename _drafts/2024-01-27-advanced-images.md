---
layout: post
title: a post with advanced image components
date: 2024-01-27 11:46:00
description: this is what advanced image components could look like
tags: formatting images
categories: sample-posts
thumbnail: assets/img/9.jpg
images:
  compare: true
  slider: true
---

BLABLA 


<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/9.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/7.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/8.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/10.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/12.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>


<!-- 
<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/images-slider/DSC_2968.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/images-slider/f18439360.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/images-slider/f20114752.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.html loading="eager" path="assets/img/images-slider/DSC_9329.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>
<br>
<br>
<hr>
<br>
<br> -->