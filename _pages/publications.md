---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @*[journal != Submitted] %}

<h2 class="bibliography">Submitted and Working Papers</h2>
{% bibliography --query @*[journal = Submitted] --group_by none %}

</div>
