---
layout: page
permalink: /publications/
title: Publications
description: Publications grouped by type and ordered chronologically.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

## Journal Articles
{% bibliography --query @article %}

## Conference Papers
{% bibliography --query @inproceedings %}

## Technical Reports
{% bibliography --query @techreport %}

## Thesis
{% bibliography --query @phdthesis %}

</div>
