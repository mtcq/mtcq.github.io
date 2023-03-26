---
layout: page
permalink: /publications/
title: publications
description: Publications in reverse chronological order.
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012]
nav: true
---

[comment]: # (List of my scientific publications.)

35 peer-reviewed publications, including 11 PRLs, 1
Nat. Comm., and 1 J. Math. Phys. \
6 preprints under review. \
More than 50 different co-authors. \
[Google Scholar](https://scholar.google.com/citations?user=9S-Jrs4AAAAJ) counts over 1800 citations with 7 papers with more than 100 citations (as of March 2023).

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
