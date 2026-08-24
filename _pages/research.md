---
layout: page
title: research
permalink: /research/
description:
nav: true
nav_order: 3
horizontal: false

---


<style>

/* =========================
   General section
   ========================= */

.research-section {
  margin-bottom: 4rem;
}


/* =========================
   Section heading
   ========================= */

.research-heading {
  margin-bottom: 1.8rem;
}

.research-title {
  color: #555;
  font-weight: 500;
  letter-spacing: 0.02em;
  margin: 0 0 0.7rem 0;
  text-align: right;
}

.research-divider {
  width: 100%;
  height: 2px;
  background-color: #555;
  margin-left: auto;
  opacity: 0.9;
}


/* =========================
   Text + image layout
   ========================= */

.research-content {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 230px;
  gap: 2.5rem;
  align-items: start;
}


/* =========================
   Main description
   ========================= */

.research-description {
  color: #000;
  line-height: 1.7;
  margin-bottom: 2rem;
}


/* =========================
   Papers
   ========================= */

.research-papers {
  margin-left: 1rem;
}

.research-paper {
  margin-bottom: 1.8rem;
}

.paper-title {
  font-weight: 600;
  margin-bottom: 0.25rem;
}

.paper-description {
  color: #000;
  line-height: 1.5;
  margin-bottom: 0.3rem;
}

.paper-links {
  font-size: 0.95rem;
}


/* =========================
   Images
   ========================= */

.research-image {
  width: 100%;
}

.research-image img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 6px;
}


/* =========================
   Mobile layout
   ========================= */

@media (max-width: 768px) {

  .research-content {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }

  .research-image {
    max-width: 300px;
    margin-left: auto;
  }

  .research-papers {
    margin-left: 0;
  }

  .research-divider {
    width: 100%;
  }

}

</style>


<!-- ================================================== -->
<!-- Topological Physics                                -->
<!-- ================================================== -->

<section class="research-section">

  <div class="research-heading">
    <h2 class="research-title">Topological Physics</h2>
    <div class="research-divider"></div>
  </div>

  <div class="research-content">

    <div class="research-text">

      <p class="research-description">
        My research in topological physics explores geometric and topological
        structures in classical and quantum systems, with particular emphasis
        on electromagnetic fields, geometric phases, and the physical
        consequences of nontrivial field configurations.
      </p>

      <div class="research-papers">

        <div class="research-paper">
          <div class="paper-title">
            Title of Paper 1
          </div>

          <div class="paper-description">
            A short description of the main idea or result of this work.
          </div>

          <div class="paper-links">
            <a href="LINK">paper</a>
            &nbsp;·&nbsp;
            <a href="LINK">arXiv</a>
            &nbsp;·&nbsp;
            <a href="LINK">DOI</a>
          </div>
        </div>


        <div class="research-paper">
          <div class="paper-title">
            Title of Paper 2
          </div>

          <div class="paper-description">
            A short description of this work.
          </div>

          <div class="paper-links">
            <a href="LINK">paper</a>
          </div>
        </div>


        <div class="research-paper">
          <div class="paper-title">
            Title of Paper 3
          </div>

          <div class="paper-description">
            A short description of this work.
          </div>

          <div class="paper-links">
            <a href="LINK">paper</a>
          </div>
        </div>

      </div>

    </div>


    <div class="research-image">
      <img
        src="{{ '/assets/img/research/topological-physics.jpg' | relative_url }}"
        alt="Topological Physics"
      >
    </div>

  </div>

</section>


<!-- ================================================== -->
<!-- Classical Electrodynamics                          -->
<!-- ================================================== -->

<section class="research-section">

  <div class="research-heading">
    <h2 class="research-title">Classical Electrodynamics</h2>
    <div class="research-divider"></div>
  </div>

  <div class="research-content">

    <div class="research-text">

      <p class="research-description">
        My work in classical electrodynamics focuses on structural and
        foundational aspects of Maxwell's theory, including electromagnetic
        energy and momentum, interactions between fields and sources, gauge
        freedom, and alternative formulations of familiar electromagnetic
        phenomena.
      </p>

      <div class="research-papers">

        <div class="research-paper">
          <div class="paper-title">
            Interaction Poynting Theorem
          </div>

          <div class="paper-description">
            A formulation of electromagnetic energy conservation that isolates
            the mutual energy and energy flow associated with two interacting
            Maxwell systems.
          </div>

          <div class="paper-links">
            <a href="LINK">paper</a>
            &nbsp;·&nbsp;
            <a href="LINK">arXiv</a>
            &nbsp;·&nbsp;
            <a href="LINK">DOI</a>
          </div>
        </div>


        <div class="research-paper">
          <div class="paper-title">
            Gauge Invariance in the Hydrogen Atom
          </div>

          <div class="paper-description">
            An examination of the hydrogen atom in gauge-equivalent
            descriptions, illustrating how gauge freedom reshapes the
            Hamiltonian and wavefunction while leaving physical predictions
            unchanged.
          </div>

          <div class="paper-links">
            <a href="LINK">paper</a>
            &nbsp;·&nbsp;
            <a href="LINK">arXiv</a>
          </div>
        </div>


        <div class="research-paper">
          <div class="paper-title">
            Title of Another Paper
          </div>

          <div class="paper-description">
            A short description of this work.
          </div>

          <div class="paper-links">
            <a href="LINK">paper</a>
          </div>
        </div>

      </div>

    </div>


    <div class="research-image">
      <img
        src="{{ '/assets/img/research/classical-electrodynamics.jpg' | relative_url }}"
        alt="Classical Electrodynamics"
      >
    </div>

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