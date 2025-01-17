---
layout: page
permalink: /publications/
title: publications
description: Publications (preprints, journal articles, and book chapters) in reversed chronological order. 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --template bib --group_by type,year --group_order ascending,descending %}

</div>
