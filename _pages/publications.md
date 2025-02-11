---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<h2>Papers</h2>

<div class="publications">
{% bibliography %}
</div>

<h2>Talk history</h2>

<div class="publications">
{% bibliography -f talks %}
</div>