---
layout: page
permalink: /Publications/
title: Publications
description: Preprints, conference papers, and journal articles.
years: [2026, 2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Preprints](#preprint-papers)] | [[Conference Papers](#conference-papers)] | [[Journal Articles](#journal-papers)]

#### Preprints

<div class="publications">

{% for y in page.years %}
  {% bibliography -f preprint -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Conference Papers

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f confs -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Journal Articles

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f journal -q @*[year={{y}}]* %}
{% endfor %}

</div>
