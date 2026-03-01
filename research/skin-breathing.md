---
layout: page
title: "Amphibian Skin Breathing"
permalink: /research/skin-breathing/
---

<!-- HERO IMAGE -->
<section class="proj-hero">
  <img class="proj-hero-image"
       src="{{ site.baseurl }}/assets/hyla_versicolor.png"
       alt="Hyla cinerea">

  <div class="proj-hero-overlay"></div>

  <div class="proj-hero-content">
    <h1 class="proj-hero-title">Amphibian Skin Breathing</h1>
    <p class="proj-hero-subtitle">
      Linking skin structure to function
    </p>
  </div>
</section>

<!-- CONTENT -->
<section class="proj-wrap">

  <!-- ONE-LINER -->
  <div class="proj-lede">
    <p>
      Amphibians rely on their skin to breathe.
      We study how amphibians breathe across their skin and how they adapt to different environments by adjusting skin breathing.
    </p>
  </div>

  <!-- TEXTBOOK FIGURE PANELS -->
  <div class="proj-panels">

    <!-- PANEL 1 -->
    <article class="panel">
      <div class="panel-figure">
        <!-- “cartoon” illustration -->
        <img src="{{ site.baseurl }}/assets/frog_breathing.png" alt="Flow of oxygen, carbon dioxide, and water">
        <div class="fig-label">Figure 1</div>
      </div>
      <div class="panel-text">
        <h2>Skin as a barrier</h2>
        <p>
          Amphibian skin must do two things that often work against each other:
          <b>let oxygen diffuse inward</b> while <b>slowing water loss outward</b>.
          This produces a fundamental trade-off between breathing and hydration.
        </p>

        <ul class="key-points">
          <li><b>Oxygen uptake:</b> the absorption of oxygen across respiratory tissue</li>
          <li><b>Water balance:</b> evaporative demand + skin permeability determine the water loss rate </li>
          <li><b>Trade-offs:</b> traits that help one function can constrain the other</li>
        </ul>
      </div>
    </article>

    <!-- PANEL 2 -->
    <article class="panel panel--reverse">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/histology.png" alt="Cartoon of histology workflow and measurements">
        <div class="fig-label">Figure 2</div>
      </div>
      <div class="panel-text">
        <h2>Skin structure</h2>
        <p>
          We use histology to characterize skin structure to connect morphology to physiology.
          Depending on the question, this can include epidermal thickness, gland densities,
          capillary density, and other features that influence diffusion and resistance.
        </p>

        <div class="callout">
          <div class="callout-title">What we measure</div>
          <p>
            Thickness, layer organization, surface complexity, and features associated with
            permeability and hydration.
          </p>
        </div>
      </div>
    </article>

  <!-- PANEL 3 -->
  <article class="panel">
    <div class="panel-figure">
      <img src="{{ site.baseurl }}/assets/phylogeny.png" alt="Cartoon phylogeny with frog species at the tips">
      <div class="fig-label">Figure 3</div>
    </div>

    <div class="panel-text">
      <h2>Comparative approach: linking traits to evolution</h2>
      <p>
        We use the <b>comparative phylogenetic method</b> to ask how skin structure and environment
        shape skin breathing across species. By combining trait data with evolutionary relationships,
        we can test whether phenotype differences between species are driven by natural selection or shared ancestry.
      </p>

      <ul class="key-points">
        <li><b>Across species:</b> quantify skin traits and gas flux in multiple lineages</li>
        <li><b>Comparative method:</b> account for relatedness when understanding species' differences</li>
        <li><b>Inference:</b> identify repeated evolutionary shifts that point to selection</li>
      </ul>
    </div>
  </article>

    <!-- PANEL 4 -->
    <article class="panel panel--reverse">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/frog_tree.png" alt="Cartoon linking traits to predictions across environments">
        <div class="fig-label">Figure 4</div>
      </div>
      <div class="panel-text">
        <h2>Why it matters</h2>
        <p>
          Rates of water loss and gas exchange serve an imporant link between organism fitness and environmental change. 
          By understanding variation in these rates across species, we can improve forecasts of dehydration risk and physiological performance
          across microclimates — and better understand how amphibians respond to environmental change.
        </p>

        <div class="callout">
          <div class="callout-title">Big picture</div>
          <p>
            Traits → performance → energy and water balance. This is the bridge from physiology to ecology.
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
        <p>Skin-specific measurements of gas exchange and water loss using respirometry.</p>
      </div>
      <div class="method-card">
        <h3>Integration</h3>
        <p>Mechanistic niche models to identify which structures explain functional variation.</p>
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
  position: relative;
  height: 520px;
  overflow: hidden;

  /* FULL-BLEED */
  width: 100vw;
  margin-left: calc(50% - 50vw);
  margin-right: calc(50% - 50vw);
}
.proj-hero-image{
  position: absolute;
  inset: 0;
  width: 100% !important;
  height: 100% !important;
  object-fit: cover;
  object-position: center;
  display: block;
  max-width: none !important;
}
  .proj-hero-overlay{
    position:absolute;
    inset:0;
    z-index:1;
    background: linear-gradient(90deg,
      rgba(0,0,0,0.55) 0%,
      rgba(0,0,0,0.18) 55%,
      rgba(0,0,0,0.06) 100%);
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
