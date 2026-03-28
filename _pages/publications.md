---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 3
---


<h3 style="text-align: center; margin-bottom: 60px;">
    <b>International peer-reviewed journals</b>
</h3>

<div class="publications">
    {% bibliography -f papers -q @article %}
</div>

<h3 style="text-align: center; margin-bottom: 60px;">
    <b>Preprints</b>
</h3>

<div class="publications">
    {% bibliography -f papers -q @preprint %}
</div>

<h3 style="text-align: center; margin-bottom: 60px;">
    <b>Peer-reviewed conference proceedings</b>
</h3>

<div class="publications">
    {% bibliography -f papers -q @inproceedings %}
</div>

<h3 style="text-align: center; margin-bottom: 60px;">
    <b>PhD Thesis</b>
</h3>

<div class="publications">
    {% bibliography -f papers -q @phdthesis %}
</div>

