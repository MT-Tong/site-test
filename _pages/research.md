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

## Working Papers

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

    <details class="paper-abstract">
      <summary>Abstract</summary>
      <p>
        We develop a practical framework for stochastic volatility models in which latent log-volatility follows an ARMA$(p,q)$ process, denoted SV$(p,q)$. Allowing for a moving-average component is economically and empirically motivated: volatility shocks often propagate over short horizons, and discretely sampled returns can inherit MA features from higher-frequency or continuous-time volatility dynamics. Despite their relevance, SV models with MA volatility innovations are rarely used in applied work because estimation and implementation become cumbersome beyond the simplest specifications.
      </p>
      <p>
        Our contribution is twofold. First, we derive a reduced-form characterization that transforms SV$(p,q)$ into a standard observable time-series problem. Using the centered log-squared return transformation, we show that the transformed series admits a reduced-form ARMA$(p,m)$ representation, where $m=\max(p,q)$, with an additive measurement-noise component of known variance.
      </p>
      <p>
        Second, we leverage this structure to provide a computationally efficient estimation and model-selection pipeline. We estimate the reduced-form ARMA using fast regression-based methods and then recover the structural SV$(p,q)$ parameters via an admissible backward-mapping step based on matching autocovariances. Our main estimator is a Hannan--Rissanen-type procedure tailored to the reduced form that applies uniformly across orders $(p,q)$.
      </p>
      <p>
        Monte Carlo experiments show that the proposed pipeline yields accurate finite-sample estimates and that the Hannan--Rissanen approach is stable for higher-order specifications. A two-stage order-selection rule reliably identifies the reduced-form order, while nested cases can lead to conservative selection of $q$. An empirical illustration using daily S&amp;P 500 returns selects an SV$(1,1)$ specification.
      </p>
    </details>
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

    <details class="paper-abstract">
      <summary>Abstract</summary>
      <p>
        Central bank announcements generate rapid asset-price movements, but these movements need not represent a single monetary-policy shock. They may combine policy news, information about the economic outlook, and transitory market noise. We develop an event-level framework for measuring and identifying monetary-policy announcement shocks from high-frequency financial data. Instead of collapsing each announcement window into an endpoint surprise, we use the intrawindow price path to construct noisy event-level covariance proxies. We then exploit heteroskedasticity across announcement events: when latent shock volatilities move non-proportionally, changes in covariance shape identify the impact matrix linking structural announcement shocks to asset prices, even under measurement noise. The framework shows how high-frequency announcement data can be used at the event level, where path and volatility information remain available, before being averaged into monthly shock proxies.
      </p>
    </details>
  </li>

</ol>

## Conference Proceedings

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

## Work in Progress

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
