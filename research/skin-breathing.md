---
layout: page
title: "Amphibian Skin Breathing"
permalink: /research/skin-breathing/
---

<!-- HERO VIDEO (optional) -->
<section class="proj-hero">
  <video class="proj-hero-video" autoplay muted loop playsinline preload="metadata">
    <source src="{{ site.baseurl }}/assets/skin_breathing.mp4" type="video/mp4">
  </video>
  <div class="proj-hero-overlay"></div>

  <div class="proj-hero-content">
    <h1 class="proj-hero-title">Amphibian Skin Breathing</h1>
    <p class="proj-hero-subtitle">
      Linking skin structure (histology) to skin function: oxygen uptake and water-loss resistance.
    </p>
  </div>
</section>

<!-- CONTENT -->
<section class="proj-wrap">

  <!-- ONE-LINER -->
  <div class="proj-lede">
    <p>
      Frogs and salamanders rely on their skin as a living interface with the environment.
      We study how microscopic structure and physiological function interact to shape
      oxygen absorption and dehydration risk.
    </p>
  </div>

  <!-- TEXTBOOK FIGURE PANELS -->
  <div class="proj-panels">

    <!-- PANEL 1 -->
    <article class="panel">
      <div class="panel-figure">
        <!-- “cartoon” illustration -->
        <img src="{{ site.baseurl }}/assets/fig_skin_layers_cartoon.png" alt="Cartoon schematic of frog skin layers">
        <div class="fig-label">Figure 1</div>
      </div>
      <div class="panel-text">
        <h2>Skin as a multi-functional barrier</h2>
        <p>
          Amphibian skin must do two things that often work against each other:
          <b>let oxygen diffuse inward</b> while <b>slowing water loss outward</b>.
          We treat the skin as a layered transport system with structure that can be quantified.
        </p>

        <ul class="key-points">
          <li><b>Oxygen uptake:</b> diffusion through hydrated tissue and boundary layers</li>
          <li><b>Water balance:</b> evaporation + permeability set dehydration rate</li>
          <li><b>Trade-offs:</b> traits that help one function can constrain the other</li>
        </ul>
      </div>
    </article>

    <!-- PANEL 2 -->
    <article class="panel panel--reverse">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/fig_histology_cartoon.png" alt="Cartoon of histology workflow and measurements">
        <div class="fig-label">Figure 2</div>
      </div>
      <div class="panel-text">
        <h2>Structure: histology and morphometrics</h2>
        <p>
          We quantify skin microstructure using histology to connect anatomy to transport.
          Depending on the system, this can include epidermal thickness, gland densities,
          keratinization, capillary proximity, and other features that influence diffusion and resistance.
        </p>

        <div class="callout">
          <div class="callout-title">What we measure</div>
          <p>
            Thickness, layer organization, surface complexity, and features associated with
            permeability and hydration — summarized into interpretable traits.
          </p>
        </div>
      </div>
    </article>

    <!-- PANEL 3 -->
    <article class="panel">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/fig_flux_cartoon.png" alt="Cartoon showing oxygen flux in and water flux out">
        <div class="fig-label">Figure 3</div>
      </div>
      <div class="panel-text">
        <h2>Function: oxygen uptake and water-loss physiology</h2>
        <p>
          We measure physiological performance of the skin as a transport surface:
          <b>how effectively oxygen is absorbed</b> and <b>how rapidly water is lost</b>
          under controlled environmental conditions.
        </p>

        <ul class="key-points">
          <li><b>Oxygen:</b> skin-driven uptake under standardized flow / boundary conditions</li>
          <li><b>Water:</b> evaporative water loss rates and resistance metrics</li>
          <li><b>Environment:</b> temperature, humidity, airflow, and hydration state</li>
        </ul>
      </div>
    </article>

    <!-- PANEL 4 -->
    <article class="panel panel--reverse">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/fig_model_link_cartoon.png" alt="Cartoon linking traits to predictions across environments">
        <div class="fig-label">Figure 4</div>
      </div>
      <div class="panel-text">
        <h2>Why it matters</h2>
        <p>
          Skin transport sets the boundary between survival and stress. By linking measurable structure
          to measurable function, we can improve forecasts of dehydration risk and physiological performance
          across microclimates — and better understand how amphibians respond to environmental change.
        </p>

        <div class="callout">
          <div class="callout-title">Big picture</div>
          <p>
            Mechanism → traits → performance → exposure risk. This is the bridge from histology to ecology.
          </p>
        </div>
      </div>
    </article>

  </div>

  <!-- OPTIONAL: METHODS SNAPSHOT -->
  <section class="proj-section">
    <h2 class="proj-section-title">Methods snapshot</h2>
    <div class="method-grid">
      <div class="method-card">
        <h3>Histology</h3>
        <p>Sampling, sectioning, staining, imaging, and standardized morphometric measurements.</p>
      </div>
      <div class="method-card">
        <h3>Skin flux</h3>
        <p>Controlled assays for oxygen uptake and water loss under defined boundary conditions.</p>
      </div>
      <div class="method-card">
        <h3>Integration</h3>
        <p>Trait-function models to identify which structures explain functional variation.</p>
      </div>
    </div>
  </section>

  <!-- OPTIONAL: CTA -->
  <section class="proj-section">
    <h2 class="proj-section-title">Interested in collaborating?</h2>
    <p class="proj-cta">
      If you’re working on amphibian physiology, skin structure, diffusion barriers, or dehydration ecology,
      feel free to reach out: <a href="mailto:riddell@unc.edu">riddell@unc.edu</a>.
    </p>
  </section>

</section>

<!-- PAGE-LOCAL STYLES (keep here for now; later move to SCSS) -->
<style>
  /* HERO */
  .proj-hero{
    position:relative;
    width:100%;
    min-height: 520px;
    border-radius: 18px;
    overflow:hidden;
    margin: 0 0 2.5rem 0;
  }
  .proj-hero-video{
    width:100%;
    height:100%;
    object-fit:cover;
    position:absolute;
    inset:0;
    transform: scale(1.02);
  }
  .proj-hero-overlay{
    position:absolute;
    inset:0;
    background: linear-gradient(90deg, rgba(0,0,0,0.55) 0%, rgba(0,0,0,0.18) 55%, rgba(0,0,0,0.06) 100%);
  }
  .proj-hero-content{
    position:absolute;
    left: 3rem;
    bottom: 3rem;
    z-index:2;
    max-width: 980px;
    padding-right: 2rem;
  }
  .proj-hero-title{
    font-size: clamp(2.2rem, 4vw, 3.2rem);
    line-height: 1.05;
    margin: 0 0 0.6rem 0;
    color: #fff;
    letter-spacing: -0.02em;
  }
  .proj-hero-subtitle{
    margin: 0;
    color: rgba(255,255,255,0.90);
    font-size: 1.12rem;
    line-height: 1.55;
    max-width: 70ch;
  }

  /* WRAP */
  .proj-wrap{ margin: 0 auto; max-width: 1040px; }
  .proj-lede p{
    font-size: 1.15rem;
    line-height: 1.7;
    color: rgba(0,0,0,0.78);
    margin: 0 0 1.75rem 0;
  }

  /* PANELS (textbook figure + explanation) */
  .proj-panels{ display:grid; gap: 1.25rem; margin: 1rem 0 2.25rem 0; }
  .panel{
    display:grid;
    grid-template-columns: 1.15fr 1fr;
    gap: 1.25rem;
    align-items: center;
    background: #fff;
    border: 1px solid rgba(0,0,0,0.08);
    border-radius: 18px;
    overflow:hidden;
    box-shadow: 0 6px 22px rgba(0,0,0,0.06);
  }
  .panel--reverse{ grid-template-columns: 1fr 1.15fr; }
  .panel--reverse .panel-figure{ order: 2; }
  .panel--reverse .panel-text{ order: 1; }

  .panel-figure{
    position: relative;
    padding: 1.25rem;
  }
  .panel-figure img{
    width:100%;
    height: 320px;
    object-fit: contain; /* key for “cartoon figure” look */
    background: rgba(0,0,0,0.02);
    border: 1px solid rgba(0,0,0,0.06);
    border-radius: 16px;
    display:block;
  }
  .fig-label{
    position:absolute;
    left: 1.55rem;
    top: 1.55rem;
    background: rgba(255,255,255,0.86);
    border: 1px solid rgba(0,0,0,0.10);
    padding: 0.25rem 0.55rem;
    border-radius: 999px;
    font-size: 0.9rem;
    font-weight: 600;
  }

  .panel-text{
    padding: 1.5rem 1.5rem 1.5rem 0;
  }
  .panel-text h2{
    margin: 0 0 0.6rem 0;
    font-size: 1.55rem;
    letter-spacing: -0.01em;
  }
  .panel-text p{
    margin: 0 0 1rem 0;
    color: rgba(0,0,0,0.74);
    line-height: 1.65;
    max-width: 90ch;
  }

  .key-points{
    margin: 0;
    padding-left: 1.1rem;
    color: rgba(0,0,0,0.72);
    line-height: 1.6;
  }
  .key-points li{ margin: 0.25rem 0; }

  .callout{
    background: rgba(0,0,0,0.03);
    border: 1px solid rgba(0,0,0,0.06);
    border-radius: 14px;
    padding: 0.9rem 1rem;
  }
  .callout-title{
    font-weight: 700;
    margin-bottom: 0.25rem;
  }
  .callout p{ margin: 0; }

  /* METHODS */
  .proj-section{ margin: 2.25rem 0; }
  .proj-section-title{
    margin: 0 0 1rem 0;
    font-size: 1.6rem;
    letter-spacing: -0.01em;
  }
  .method-grid{
    display:grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
  }
  .method-card{
    background: #fff;
    border: 1px solid rgba(0,0,0,0.08);
    border-radius: 18px;
    box-shadow: 0 6px 22px rgba(0,0,0,0.06);
    padding: 1.25rem;
  }
  .method-card h3{ margin: 0 0 0.5rem 0; }
  .method-card p{
    margin: 0;
    color: rgba(0,0,0,0.74);
    line-height: 1.65;
  }

  .proj-cta{
    color: rgba(0,0,0,0.74);
    line-height: 1.65;
    max-width: 92ch;
  }
  .proj-cta a{
    text-decoration: none;
    border-bottom: 2px solid rgba(86,145,232,0.28);
  }

  /* RESPONSIVE */
  @media (max-width: 860px){
    .proj-hero-content{ left: 1.25rem; right: 1.25rem; bottom: 1.25rem; }
    .panel, .panel--reverse{ grid-template-columns: 1fr; }
    .panel--reverse .panel-figure, .panel--reverse .panel-text{ order: unset; }
    .panel-text{ padding: 0 1.25rem 1.5rem 1.25rem; }
    .panel-figure img{ height: 260px; }
    .method-grid{ grid-template-columns: 1fr; }
  }
</style>
