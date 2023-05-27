---
layout: page
permalink: /publications/
title: publications
description: 
years: [2023, 2022, 2021, 2020] # Add bib to papers.bib then add year here
nav: true # set it to enable/disable the pages
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
