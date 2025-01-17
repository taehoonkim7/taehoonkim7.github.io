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
  
  <h2>Invited talks</h2>
  {% bibliography --file invited --template present --group_by year --group_order descending %}

  <h2>Contributed talks</h2>
  {% bibliography --file contributed --template present --group_by year --group_order descending %}

  <h2>Conference abstracts/posters</h2>
  {% bibliography --file conference --template present --group_by year --group_order descending %}
  
</div>
