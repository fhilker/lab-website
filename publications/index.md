---
title: Publications
nav:
  order: 1
  tooltip: List of scientific publications
---

<!-- altmetric, dimensions, and plumx -->
<script type='text/javascript' src='https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js'></script>
<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

# {% include icon.html icon="fa-solid fa-book-open" %}Publications

{% include button.html icon="fa-brands fa-google" text="Google Scholar profile" link="https://scholar.google.com/citations?hl=en&user=fL0h-yIAAAAJ" %}

{% include section.html %}

For a thematic selection, click the corresponding buttons.

{%
  include button.html
  link="publications#journal-articles"
  text="Jump to journal articles"
  icon="fa-solid fa-arrow-right"
  flip=false
  style="bare"
%}

{%
  include button.html
  link="publications#book-chapters-proceedings-and-reports"
  text="Jump to book chapters, Proceedings, and Misc."
  icon="fa-solid fa-arrow-right"
  flip=false
  style="bare"
%}

{% include search-box.html %}

{% include search-info.html %}

## Journal articles

{% include list.html data="citations" component="citation" filter="type == 'article'" style="rich" %}

{% include section.html %}

## Book chapters, Proceedings, and Reports

{% include list.html data="citations" component="citation" filter="type != 'article'" style="rich" %}

