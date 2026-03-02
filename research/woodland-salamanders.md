---
layout: page
title: "Ecophysiology of Woodland Salamanders"
permalink: /research/woodland-salamanders/
---

<!-- HERO IMAGE -->
<section class="proj-hero">
  <img class="proj-hero-image"
       src="{{ site.baseurl }}/assets/plethodon.jpeg"
       alt="Woodland salamander in leaf litter">

  <div class="proj-hero-overlay"></div>

  <div class="proj-hero-content">
    <h1 class="proj-hero-title">Ecophysiology of Woodland Salamanders</h1>
    <p class="proj-hero-subtitle">
      Linking metabolism, water balance, dormancy, and tissue regeneration.
    </p>
  </div>
</section>

<!-- CONTENT -->
<section class="proj-wrap">

  <!-- LEDE -->
  <div class="proj-lede">
    <p>
      Woodland salamanders are one of the most unique and ecologically important vertebrates in North America.
      We study how physiology links environment to fitness and how those links shape
      vulnerability, range limits, and evolutionary trajectories.
    </p>
  </div>

  <div class="proj-panels">

    <!-- SECTION 1 -->
    <article class="panel">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/salamander_flux.png"
             alt="Metabolic rate and water loss illustration">
        <div class="fig-label">Section 1</div>
      </div>

      <div class="panel-text">
        <h2>Physiology and climate vulnerability</h2>
        <p>
          We quantify how <b>metabolic rate</b> and <b>water loss</b> interact to shape
          organismal performance across thermal and hydric gradients. Because salamanders
          rely heavily on cutaneous respiration, changes in skin resistance directly influence
          oxygen uptake, activity capacity, and dehydration risk.
        </p>

        <ul class="key-points">
          <li><b>Metabolic rate:</b> energy demand under variable temperature</li>
          <li><b>Water loss:</b> evaporative constraint on activity and survival</li>
          <li><b>Integration:</b> linking physiology to performance and climate exposure</li>
        </ul>

        <div class="callout">
          <div class="callout-title">Goal</div>
          <p>
            Connect physiological traits to fitness-relevant outcomes to improve predictions
            of climate vulnerability across species and landscapes.
          </p>
        </div>
      </div>
    </article>

    <!-- SECTION 2 -->
    <article class="panel panel--reverse">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/salamander_winter.png"
             alt="Winter dormancy and metabolic physiology illustration">
        <div class="fig-label">Section 2</div>
      </div>

      <div class="panel-text">
        <h2>Winter dormancy, energetics, and species ranges</h2>
        <p>
          Winter is a dominant selective force for temperate salamanders.
          We investigate how <b>metabolic regulation</b>, tissue structure,
          and energy storage strategies during dormancy influence survival,
          overwinter performance, and geographic range limits.
        </p>

        <ul class="key-points">
          <li><b>Metabolic physiology:</b> rates during dormancy and warming</li>
          <li><b>Histology:</b> tissue organization and structural changes</li>
          <li><b>Energetics:</b> stored fuels and seasonal constraints</li>
        </ul>

        <div class="callout">
          <div class="callout-title">Big question</div>
          <p>
            How do winter metabolic constraints set the boundaries of where species can persist?
          </p>
        </div>
      </div>
    </article>

    <!-- SECTION 3 -->
    <article class="panel">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/salamander_regeneration.png"
             alt="Tail regeneration and metabolic rate illustration">
        <div class="fig-label">Section 3</div>
      </div>

      <div class="panel-text">
        <h2>Ecology and evolution of tissue regeneration</h2>
        <p>
          Salamanders are renowned for their regenerative capacity, yet rates of regeneration
          vary across environments. We examine how <b>metabolic rate</b>, <b>elevation</b>,
          and energy availability shape regeneration rates and mechanisms.
        </p>

        <ul class="key-points">
          <li><b>Tail-tip regeneration:</b> standardized assays across populations</li>
          <li><b>Metabolic links:</b> energetic costs of tissue rebuilding</li>
          <li><b>Evolutionary gradients:</b> regeneration across elevation and climate</li>
        </ul>

        <div class="callout">
          <div class="callout-title">Current focus</div>
          <p>
            We are quantifying tail-tip regeneration rates to test how
            energy availability shapes regenerative investment.
          </p>
        </div>
      </div>
    </article>

  </div>

  <!-- PAGE-LOCAL STYLES -->
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

  /* PANELS */
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
    object-fit: contain;
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

  .panel-text{ padding: 1.5rem 1.5rem 1.5rem 0; }
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


</section>
