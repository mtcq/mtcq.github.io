---
layout: page
permalink: /publications/
title: publications
description: Publications in reverse chronological order.
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012]
nav: true
---

[comment]: # (List of my scientific publications.)

All my scientific papers are publicly available at [arXiv](https://arxiv.org/a/quintino_m_1.html) and some statistics may be found at [Google Scholar](https://scholar.google.com/citations?user=9S-Jrs4AAAAJ). <br>
Here, you also download the journal version of my published papers.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
