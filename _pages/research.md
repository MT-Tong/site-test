---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
.research-page {
  counter-reset: paper-counter;
}

.paper-list {
  list-style: none;
  padding-left: 0;
  margin-bottom: 2.2em;
}

.paper-item {
  counter-increment: paper-counter;
  margin-bottom: 1.8em;
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
  display: inline;
  font-size: 0.95em;
}

.paper-status {
  margin-top: 0.25em;
  font-size: 0.92em;
  font-style: italic;
}

.paper-abstract {
  margin-top: 0.5em;
  font-size: 0.88em;
  line-height: 1.5;
  color: #555;
}

.paper-abstract summary {
  cursor: pointer;
  font-weight: 600;
  color: #333;
  margin-bottom: 0.35em;
}

.paper-abstract p {
  margin-top: 0.4em;
}

.section-note {
  font-size: 0.92em;
  color: #555;
  margin-top: -0.4em;
  margin-bottom: 1.2em;
}
</style>

<div class="research-page">

<h2>Working Papers</h2>

<ol class="paper-list">

  <li class="paper-item">
    <div>
      <span class="paper-title">“Pairwise Difference Representations of Moments: Gini and Generalized Lagrange Identities”</span>,
      <span class="paper-authors">
        with
        <a href="https://jeanmariedufour.research.mcgill.ca/dufour.html" target="_blank">Jean-Marie Dufour</a>
        and Abderrahim Taamouti
      </span>
    </div>

    <div class="paper-status">
      Submitted to <em>The International Statistical Review</em> |
      <a href="https://arxiv.org/abs/2510.22714" target="_blank">arXiv</a>
    </div>

    <details class="paper-abstract">
      <summary>Abstract</summary>
      <p>
        We provide pairwise-difference (Gini-type) representations of higher-order central moments for both general random variables and empirical moments. Such representations do not require a measure of location. For third and fourth moments, this yields pairwise-difference representations of skewness and kurtosis coefficients. We show that all central moments possess such representations, so no reference to the mean is needed for moments of any order. This is done by considering i.i.d. replications of the random variables considered, by observing that central moments can be interpreted as covariances between a random variable and powers of the same variable, and by giving recursions which link the pairwise-difference representation of any moment to lower order ones. Numerical summation identities are deduced. Through a similar approach, we give analogues of the Lagrange and Binet-Cauchy identities for general random variables, along with a simple derivation of the classic Cauchy-Schwarz inequality for covariances. Finally, an application to unbiased estimation of centered moments is discussed.
      </p>
    </details>
  </li>

  <li class="paper-item">
    <div>
      <span class="paper-title">“Estimating Higher-Order Stochastic Volatility Models with Moving Average Components: Methodology and Applications”</span>,
      <span class="paper-authors">
        with
        <a href="https://jeanmariedufour.research.mcgill.ca/dufour.html" target="_blank">Jean-Marie Dufour</a>
      </span>
    </div>

    <div class="paper-status">
      Revised May 2026
    </div>

  </li>

  <li class="paper-item">
    <div>
      <span class="paper-title">“From Micro-Slices to Macro Effects: Identifying Policy and Information Shocks via Time-Varying Volatility”</span>,
      <span class="paper-authors">
        Meilin Tong
      </span>
    </div>

    <div class="paper-status">
      Working paper
    </div>
  </li>

</ol>

<h2>Conference Proceedings</h2>

<ol class="paper-list">

  <li class="paper-item">
    <div>
      <span class="paper-title">“Pairwise Difference Representations of Central Moments: Skewness, Kurtosis, and Higher-order Recursions”</span>,
      <span class="paper-authors">
        with
        <a href="https://jeanmariedufour.research.mcgill.ca/dufour.html" target="_blank">Jean-Marie Dufour</a>
        and Abderrahim Taamouti
      </span>
    </div>

    <div class="paper-status">
      2026 JSM Proceedings
    </div>
  </li>

</ol>

<h2>Work in Progress</h2>

<ol class="paper-list">

  <li class="paper-item">
    <div>
      <span class="paper-title">“High-dimensional Stochastic Covariance Estimation via Model Aggregation”</span>,
      <span class="paper-authors">
        with Md. Nazmul Ahsan and
        <a href="https://jeanmariedufour.research.mcgill.ca/dufour.html" target="_blank">Jean-Marie Dufour</a>
      </span>
    </div>

    <div class="paper-status">
      Work in progress
    </div>
  </li>

</ol>

</div>
