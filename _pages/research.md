---
layout: page
title: research
permalink: /research/
description:
nav: true
nav_order: 3
horizontal: false

---
<!-- ===================== -->
<!-- Topological Physics   -->
<!-- ===================== -->

<section class="research-section">

  <h2 class="research-title">Topological Physics</h2>

  <p class="research-description">
    My research in topological physics explores geometric and topological
    structures in classical and quantum systems, with particular emphasis on
    electromagnetic fields, geometric phases, and the physical consequences
    of nontrivial field configurations.
  </p>

  <div class="research-papers">

    <p>
      <strong>Paper 1</strong><br>
      <span class="paper-description">
        A short one-sentence description of the main idea or result.
      </span><br>
      <a href="LINK">paper</a>
      &nbsp;·&nbsp;
      <a href="LINK">arXiv</a>
      &nbsp;·&nbsp;
      <a href="LINK">DOI</a>
    </p>

    <p>
      <strong>Paper 2</strong><br>
      <span class="paper-description">
        A short description of this work.
      </span><br>
      <a href="LINK">paper</a>
    </p>

    <p>
      <strong>Paper 3</strong><br>
      <span class="paper-description">
        A short description of this work.
      </span><br>
      <a href="LINK">paper</a>
    </p>

  </div>

</section>


<!-- ========================= -->
<!-- Classical Electrodynamics -->
<!-- ========================= -->

<section class="research-section">

  <h2 class="research-title">Classical Electrodynamics</h2>

  <p class="research-description">
    My work in classical electrodynamics focuses on structural and foundational
    aspects of Maxwell's theory, including electromagnetic energy and momentum,
    interactions between fields and sources, gauge freedom, and alternative
    formulations of familiar electromagnetic phenomena.
  </p>

  <div class="research-papers">

    <p>
      <strong>Interaction Poynting Theorem</strong><br>
      <span class="paper-description">
        A formulation of electromagnetic energy conservation that isolates
        the mutual energy and energy flow associated with two interacting
        Maxwell systems.
      </span><br>
      <a href="LINK">paper</a>
      &nbsp;·&nbsp;
      <a href="LINK">arXiv</a>
    </p>

    <p>
      <strong>Gauge Invariance in the Hydrogen Atom</strong><br>
      <span class="paper-description">
        An examination of the hydrogen atom in gauge-equivalent descriptions,
        illustrating explicitly how gauge freedom reshapes the Hamiltonian and
        wavefunction while leaving physical predictions unchanged.
      </span><br>
      <a href="LINK">paper</a>
    </p>

    <p>
      <strong>Another paper</strong><br>
      <span class="paper-description">
        A short description of the work.
      </span><br>
      <a href="LINK">paper</a>
    </p>

  </div>

</section>

{% comment %}
<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
{% endcomment %}