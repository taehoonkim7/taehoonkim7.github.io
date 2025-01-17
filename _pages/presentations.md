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
  
  <div class = "Invited talks">
    {% bibliography --file invited --template present --group_by year --group_order descending %}
  </div>

  <div class = "Contributed talks">
    {% bibliography --file contributed --template present --group_by year --group_order descending %}
  </div>
  
  <div class = "Conference abstracts/posters">
    {% bibliography --file conference --template present --group_by year --group_order descending %}
  </div>
  
</div>
