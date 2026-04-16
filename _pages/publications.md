---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<div class="publications">

<h2 class="bibliography">Current Work</h2>
{% bibliography --query @inproceedings %}

<br>

<h2 class="bibliography">Past Work</h2>
{% bibliography --query @article %}

</div>
