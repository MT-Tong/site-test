---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
.paper-list {
  counter-reset: paper-counter;
  list-style: none;
  padding-left: 0;
}

.paper-item {
  counter-increment: paper-counter;
  margin-bottom: 1.6em;
  padding-left: 2.4em;
  position: relative;
}

.paper-item::before {
  content: counter(paper-counter) ".";
  position: absolute;
  left: 0;
  font-weight: bold;
}

.paper-title {
  font-weight: 700;
  font-size: 1.05em;
  line-height: 1.35;
}

.paper-authors {
  margin-top: 0.25em;
  font-size: 0.95em;
}

.paper-venue {
  margin-top: 0.25em;
  font-size: 0.95em;
  font-style: italic;
}

.paper-links {
  margin-top: 0.25em;
  font-size: 0.9em;
}

.paper-abstract {
  margin-top: 0.5em;
  font-size: 0.88em;
  line-height: 1.45;
  color: #555;
}
</style>

## Publication and Conference Proceedings

<ol class="paper-list">

  <li class="paper-item">
    <div class="paper-title">Title of Published Paper or Conference Proceeding</div>
    <div class="paper-authors">Your Name, Coauthor Name, and Coauthor Name</div>
    <div class="paper-venue">Journal Name / Conference Name, Year</div>
    <div class="paper-links">
      <a href="{{ base_path }}/files/paper1.pdf" target="_blank">PDF</a>
      |
      <a href="https://arxiv.org/abs/XXXX.XXXXX" target="_blank">arXiv</a>
    </div>
  </li>

  <li class="paper-item">
    <div class="paper-title">Another Published Paper Title</div>
    <div class="paper-authors">Your Name and Coauthor Name</div>
    <div class="paper-venue">Journal Name / Conference Name, Year</div>
    <div class="paper-links">
      <a href="{{ base_path }}/files/paper2.pdf" target="_blank">PDF</a>
      |
      <a href="https://arxiv.org/abs/XXXX.XXXXX" target="_blank">arXiv</a>
    </div>
  </li>

</ol>

## Working Papers

<ol class="paper-list">

  <li class="paper-item">
    <div class="paper-title">Estimating Higher-order SV Model with Moving Average Component</div>
    <div class="paper-authors">Your Name and Coauthor Name</div>
    <div class="paper-venue">Working paper</div>
    <div class="paper-links">
      <a href="{{ base_path }}/files/higher_order_sv_ma.pdf" target="_blank">PDF</a>
      |
      <a href="https://arxiv.org/abs/XXXX.XXXXX" target="_blank">arXiv</a>
    </div>
    <div class="paper-abstract">
      <strong>Abstract.</strong> Paste abstract here later.
    </div>
  </li>

  <li class="paper-item">
    <div class="paper-title">From Micro-slices to Macro Effects</div>
    <div class="paper-authors">Your Name and Coauthor Name</div>
    <div class="paper-venue">Working paper</div>
    <div class="paper-links">
      <a href="{{ base_path }}/files/micro_slices_macro_effects.pdf" target="_blank">PDF</a>
      |
      <a href="https://arxiv.org/abs/XXXX.XXXXX" target="_blank">arXiv</a>
    </div>
    <div class="paper-abstract">
      <strong>Abstract.</strong> Paste abstract here later.
    </div>
  </li>

</ol>

## Work in Progress

<ol class="paper-list">

  <li class="paper-item">
    <div class="paper-title">High-dimensional Stochastic Variance Estimation</div>
    <div class="paper-authors">Your Name and Coauthor Name</div>
    <div class="paper-venue">Work in progress</div>
    <div class="paper-abstract">
      <strong>Abstract.</strong> Optional. You can keep this short or remove it until the paper is ready.
    </div>
  </li>

</ol>
