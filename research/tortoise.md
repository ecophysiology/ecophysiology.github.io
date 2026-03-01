---
layout: page
title: "Desert Tortoise Physiology"
permalink: /research/tortoise/
---

<!-- HERO IMAGE -->
<section class="proj-hero">
  <img class="proj-hero-image"
       src="{{ site.baseurl }}/assets/tortoise_hero.png"
       alt="Desert tortoise in habitat">

  <div class="proj-hero-overlay"></div>

  <div class="proj-hero-content">
    <h1 class="proj-hero-title">Desert Tortoise Physiology</h1>
    <p class="proj-hero-subtitle">
      Linking age-specific physiology to mechanistic predictions for conservation and translocations.
    </p>
  </div>
</section>

<!-- CONTENT -->
<section class="proj-wrap">

  <!-- ONE-LINER -->
  <div class="proj-lede">
    <p>
      Desert tortoises experience extreme thermal and hydric conditions. We study how physiology varies
      across age classes and use those mechanisms to improve predictions of habitat suitability and
      translocation outcomes.
    </p>
  </div>

  <!-- TWO PANELS -->
  <div class="proj-panels">

    <!-- PANEL 1 -->
    <article class="panel">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/fig_tortoise_age_phys.png" alt="Cartoon showing hatchling, juvenile, and adult physiology across temperatures">
        <div class="fig-label">Figure 1</div>
      </div>

      <div class="panel-text">
        <h2>Physiology across age classes</h2>
        <p>
          We test whether <b>hatchlings and juveniles are more thermally sensitive</b> than adults and whether
          early life stages face narrower safety margins during hot, dry conditions. By measuring performance
          and stress responses across temperatures, we identify which age classes are most vulnerable—and why.
        </p>

        <ul class="key-points">
          <li><b>Age comparisons:</b> hatchlings, juveniles, and adults</li>
          <li><b>Thermal sensitivity:</b> performance curves and limits across temperatures</li>
          <li><b>Mechanisms:</b> water balance, metabolic demand, and heat exchange constraints</li>
        </ul>
      </div>
    </article>

    <!-- PANEL 2 -->
    <article class="panel panel--reverse">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/fig_tortoise_mnm.png" alt="Cartoon linking physiology to mechanistic niche models and translocation site predictions">
        <div class="fig-label">Figure 2</div>
      </div>

      <div class="panel-text">
        <h2>From mechanism to management</h2>
        <p>
          We integrate age-specific physiology into <b>mechanistic niche models</b> to predict where tortoises can
          maintain safe body temperatures and water balance across real landscapes. These forecasts can guide
          decisions about <b>translocation sites</b> and identify when microclimate refuges are necessary for success.
          This work is conducted in partnership with the <b>San Diego Zoo</b>.
        </p>

        <ul class="key-points">
          <li><b>Mechanistic models:</b> predict body temperature and dehydration risk</li>
          <li><b>Site selection:</b> identify refuges and microclimates that support survival</li>
          <li><b>Conservation impact:</b> improve translocation planning under climate change</li>
        </ul>
      </div>
    </article>

  </div>

  <!-- OPTIONAL: METHODS SNAPSHOT -->
  <section class="proj-section">
    <h2 class="proj-section-title">Methods snapshot</h2>
    <div class="method-grid">
      <div class="method-card">
        <h3>Physiology</h3>
        <p>Thermal sensitivity assays across age classes, focused on performance and stress-relevant traits.</p>
      </div>
      <div class="method-card">
        <h3>Microclimate</h3>
        <p>Quantifying operative conditions and refuge environments that shape exposure in the field.</p>
      </div>
      <div class="method-card">
        <h3>Modeling</h3>
        <p>Mechanistic niche models linking traits to landscape-scale predictions for management decisions.</p>
      </div>
    </div>
  </section>

  <!-- OPTIONAL: CTA -->
  <section class="proj-section">
    <h2 class="proj-section-title">Interested in collaborating?</h2>
    <p class="proj-cta">
      If you’re working on reptile physiology, mechanistic niche modeling, or conservation translocations,
      feel free to reach out: <a href="mailto:riddell@unc.edu">riddell@unc.edu</a>.
    </p>
  </section>

</section>

<!-- PAGE-LOCAL STYLES -->
<style>
  /* HERO */
  .proj-hero{
    position:relative;
    width:100%;
    height:520px;
    overflow:hidden;
  }
  .proj-hero-image{
    position:absolute;
    inset:0;
    width:100%;
    height:100%;
    display:block;
    object-fit:cover;
    object-position:center;
    max-width:none !important;
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
