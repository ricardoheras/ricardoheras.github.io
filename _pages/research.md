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

/* ==================================================
   TOPOLOGICAL PHYSICS
   ================================================== */

.research-section {
  margin-bottom: 4rem;
}


/* --------------------------------------------------
   Section heading
   -------------------------------------------------- */

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


/* --------------------------------------------------
   Main layout
   -------------------------------------------------- */

.research-content {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 230px;
  gap: 2.5rem;
  align-items: start;
}


/* --------------------------------------------------
   Introduction
   -------------------------------------------------- */

.research-description {
  line-height: 1.7;
  margin-top: 0;
  margin-bottom: 2.2rem;
}


/* --------------------------------------------------
   Papers
   -------------------------------------------------- */

.research-papers {
  margin-left: 1rem;
}

.research-paper {
  margin-bottom: 2.2rem;
}

.paper-title {
  font-weight: 600;
  margin-bottom: 0.4rem;
}

.paper-summary {
  line-height: 1.6;
  margin-bottom: 0.55rem;
}

.paper-citation {
  line-height: 1.5;
  margin-bottom: 0.35rem;
}

.paper-links {
  font-size: 0.95rem;
}


/* --------------------------------------------------
   Research image
   -------------------------------------------------- */

.research-image {
  width: 100%;
}

.research-image img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 6px;
}


/* --------------------------------------------------
   Mobile layout
   -------------------------------------------------- */

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


<!-- ==================================================
     TOPOLOGICAL PHYSICS
     ================================================== -->

<section class="research-section">


  <!-- Heading -->

  <div class="research-heading">

    <h2 class="research-title">
      Topological Physics
    </h2>

    <div class="research-divider"></div>

  </div>


  <!-- Main content -->

  <div class="research-content">

    <div class="research-text">


      <!-- Introduction -->

      <p class="research-description">
        I am interested in situations where topology is not merely a
        mathematical language for describing physics, but becomes part
        of the physics itself. My work explores how global geometric
        and topological structures acquire observable consequences in
        classical electrodynamics and quantum mechanics. In particular,
        I study the Aharonov–Bohm effect, topological electromagnetic
        angular momentum, magnetic monopoles and dyons, where winding
        and linking numbers, gauge invariance, nonlocality, quantisation,
        electromagnetic duality and vacuum structure become directly
        intertwined with physical phases and observables.
      </p>


      <!-- Papers -->

      <div class="research-papers">


        <!-- ==========================================
             Classical nonlocality
             ========================================== -->

        <div class="research-paper">

          <div class="paper-title">
            Can classical electrodynamics predict nonlocal effects?
          </div>

          <div class="paper-summary">
            A classical counterpart to the topological nonlocality
            associated with the Aharonov–Bohm effect. For a charge
            encircling a confined magnetic flux, the electromagnetic
            angular momentum describes a nonlocal interaction between
            spatially separated electromagnetic systems. Its dependence
            on the winding number reveals that this nonlocality is
            topological and arises from the non-simply connected
            geometry of the configuration.
          </div>

          <div class="paper-citation">
            José A. Heras and Ricardo Heras,
            <em>The European Physical Journal Plus</em>,
            <b>136</b>, 847 (2021)
          </div>

          <div class="paper-links">

            <a href="https://ricardoheras.github.io/assets/pdf/rh22.pdf">
              PDF
            </a>

            &nbsp;·&nbsp;

            <a href="https://doi.org/10.1140/epjp/s13360-021-01835-9">
              DOI
            </a>

          </div>

        </div>



        <!-- ==========================================
             Aharonov–Bohm effect
             ========================================== -->

        <div class="research-paper">

          <div class="paper-title">
            The Aharonov–Bohm effect in a closed flux line
          </div>

          <div class="paper-summary">
            An exact formulation of the Aharonov–Bohm effect for a
            closed magnetic flux line, providing a natural idealisation
            of a toroidal magnet. The AB phase is determined by a
            linking number rather than a winding number, making its
            topological character explicit and allowing the local and
            nonlocal interpretations of the effect to be examined from
            a different perspective.
          </div>

          <div class="paper-citation">
            Ricardo Heras,
            <em>The European Physical Journal Plus</em>,
            <b>137</b>, 157 (2022)
          </div>

          <div class="paper-links">

            <a href="https://ricardoheras.github.io/assets/pdf/rh24.pdf">
              PDF
            </a>

            &nbsp;·&nbsp;

            <a href="https://doi.org/10.1140/epjp/s13360-022-02832-2">
              DOI
            </a>

          </div>

        </div>



        <!-- ==========================================
             Quantum phase of a dyon
             ========================================== -->

        <div class="research-paper">

          <div class="paper-title">
            The quantum phase of a dyon
          </div>

          <div class="paper-summary">
            A duality-invariant quantum phase acquired by a dyon
            encircling confined electric and magnetic fluxes. The
            construction unifies the Aharonov–Bohm phase with its
            electromagnetic dual and shows how topology, nonlocality
            and electric–magnetic duality can be incorporated within
            a single quantum-mechanical framework.
          </div>

          <div class="paper-citation">
            Ricardo Heras,
            <em>The European Physical Journal Plus</em>,
            <b>138</b>, 329 (2023)
          </div>

          <div class="paper-links">

            <a href="https://ricardoheras.github.io/assets/pdf/rh25.pdf">
              PDF
            </a>

            &nbsp;·&nbsp;

            <a href="https://doi.org/10.1140/epjp/s13360-023-03914-5">
              DOI
            </a>

          </div>

        </div>



        <!-- ==========================================
             Dyons with theta phase
             ========================================== -->

        <div class="research-paper">

          <div class="paper-title">
            Dyons with phase
            δ<sub>θ</sub> = nθ
          </div>

          <div class="paper-summary">
            An extension of the topological dyon phase obtained by
            combining electromagnetic duality with the Witten effect.
            The resulting phase is proportional to the vacuum angle θ
            and becomes quantised as δ<sub>θ</sub> = nθ, establishing
            a connection between dyonic quantum phases, CP violation
            and an Abelian form of the θ-vacua.
          </div>

          <div class="paper-citation">
            Ricardo Heras,
            <em>The European Physical Journal Plus</em>,
            <b>138</b>, 991 (2023)
          </div>

          <div class="paper-links">

            <a href="https://ricardoheras.github.io/assets/pdf/rh26.pdf">
              PDF
            </a>

            &nbsp;·&nbsp;

            <a href="https://doi.org/10.1140/epjp/s13360-023-04629-3">
              DOI
            </a>

          </div>

        </div>



        <!-- ==========================================
             Dirac monopoles
             ========================================== -->

        <div class="research-paper">

          <div class="paper-title">
            Dirac quantisation condition:
            a comprehensive review
          </div>

          <div class="paper-summary">
            A systematic account of the Dirac quantisation condition
            and the physics of magnetic monopoles. The review develops
            the connections between charge quantisation, gauge
            invariance, singular potentials, the Dirac string and
            electromagnetic angular momentum, comparing several
            quantum-mechanical and semiclassical routes to the
            quantisation condition.
          </div>

          <div class="paper-citation">
            Ricardo Heras,
            <em>Contemporary Physics</em>,
            <b>59</b>, 331–355 (2018)
          </div>

          <div class="paper-links">

            <a href="https://ricardoheras.github.io/assets/pdf/rh16.pdf">
              PDF
            </a>

            &nbsp;·&nbsp;

            <a href="https://doi.org/10.1080/00107514.2018.1527974">
              DOI
            </a>

          </div>

        </div>


      </div>
      <!-- End research-papers -->


    </div>
    <!-- End research-text -->



    <!-- ==============================================
         Image
         ============================================== -->

    <div class="research-image">

      <img
        src="{{ '/assets/img/research/topological-physics.jpg' | relative_url }}"
        alt="Topological Physics"
      >

    </div>


  </div>
  <!-- End research-content -->


</section>

{% comment %}

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
    <h2 class="research-title">Topological aspects of quantum theory</h2>
    <div class="research-divider"></div>
  </div>

  <div class="research-content">

    <div class="research-text">

      <p class="research-description">
        
      </p>

      <div class="research-papers">

        <div class="research-paper">
          <div class="paper-title">
            The Aharonov-Bohm effect in a closed flux line
          </div>

          <div class="paper-description">
            Ricardo Heras, The European Physical Journal Plus, <b>137</b>, 157, 2022
          </div>

          <div class="paper-links">
            <a href="https://ricardoheras.github.io/assets/pdf/rh24.pdf">PDF</a>
            &nbsp;·&nbsp;
            <a href="https://doi.org/10.1140/epjp/s13360-022-02832-2">DOI</a>
          </div>
        </div>


        <div class="research-paper">
          <div class="paper-title">
            Dirac quantisation condition: a comprehensive review
          </div>

          <div class="paper-description">
            Ricardo Heras, Contemporary Physics, <b>59</b>, 331, 2018
          </div>

          <div class="paper-links">
            <a href="https://ricardoheras.github.io/assets/pdf/rh16.pdf">PDF</a>
            &nbsp;·&nbsp;
            <a href="https://doi.org/10.1080/00107514.2018.1527974">DOI</a>
          </div>
        </div>


        <div class="research-paper">
          <div class="paper-title">
         Can classical electrodynamics predict nonlocal effects?
          </div>

          <div class="paper-description">
            José Alfredo Heras, and Ricardo Heras, The European Physical Journal Plus, <b>136</b>, 847, 2021
          </div>

          <div class="paper-links">
            <a href="https://ricardoheras.github.io/assets/pdf/rh22.pdf">PDF</a>
            &nbsp;·&nbsp;
            <a href="https://doi.org/10.1140/epjp/s13360-021-01835-9">DOI</a>
          </div>
        </div>


      <div class="research-papers">

        <div class="research-paper">
          <div class="paper-title">
          The Aharonov-Bohm effect in a closed flux line
          </div>

          <div class="paper-description">
            Ricardo Heras, 
          </div>

          <div class="paper-links">
            <a href="https://ricardoheras.github.io/assets/pdf/rh24.pdf">PDF</a>
            &nbsp;·&nbsp;
            <a href="https://doi.org/10.1140/epjp/s13360-022-02832-2">DOI</a>
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







{% comment %}

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