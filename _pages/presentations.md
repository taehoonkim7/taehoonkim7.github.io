---
layout: page
permalink: /presentations/
title: presentations
description: Presentations (invited talks, contributed talks, and conference abstracts/posters) in reversed chronological order. 
nav: true
nav_order: 3
---

<!-- _pages/presentations.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="presentations">

{% bibliography --file present --template present --group_by type,year --group_order ascending,descending %}

</div>
