---
layout: page
permalink: /publications/
title: research
description: 
years: [2020,2019,2018,2017,2016,2015,2014,2013,2012,2011,2010,2009]
order: 2

nav: true
---
#### Current Research 

- Energy Effecient Computing
- Embedded Systems
- Stochastic Computing
- Emerging workloads and platforms
- Secure Infrastructures


#### Publications

<div class="publications">

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
