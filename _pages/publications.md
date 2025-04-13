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

<div class="publications">

{% assign bib_entries = site.scholar.bibliography %}

{% if bib_entries and bib_entries != empty %}
  {% bibliography %}
{% else %}
  <p><em>No publications found.</em></p>
{% endif %}

</div>
