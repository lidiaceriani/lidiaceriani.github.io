---
layout: page
permalink: /publications/
title: publications
description: journal articles and book chapters, most recent first.
nav: true
nav_order: 2
_styles: >
  .publications h2.bibliography {
    color: var(--global-theme-color);
    font-size: 1.3rem;
    font-weight: 500;
    text-align: left;
    border-top: none;
    padding-top: 0;
    margin: 2.25rem 0 0.75rem;
  }

  .publications h2.bibliography:first-of-type {
    margin-top: 1rem;
  }

  .publications ol.bibliography {
    background-color: var(--global-card-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 0.35rem;
    padding: 0 1.1rem;
    margin-bottom: 0.5rem;
  }

  .publications ol.bibliography > li {
    padding: 1.1rem 0;
    margin-bottom: 0;
    border-top: 1px solid var(--global-divider-color);
  }

  .publications ol.bibliography > li:first-child {
    border-top: none;
  }
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
