---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 1
---
<p>An up-to-date list is available on <a href="https://scholar.google.com/citations?user=YmHEJCoAAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a>.</p>

<div class="publications">

<h1>Journal Articles</h1>
{% bibliography -f papers -q @article %}

<h1>Theses</h1>
{% bibliography -f papers -q @thesis%}

</div>