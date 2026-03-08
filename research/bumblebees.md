---
layout: page
title: "Bumble Bee Collective Acclimation"
permalink: /research/bumblebees/
---

<!-- HERO IMAGE -->
<section class="proj-hero">
  <img class="proj-hero-image"
       src="{{ site.baseurl }}/assets/bombus.jpg"
       alt="Bumble bee colony">

  <div class="proj-hero-overlay"></div>

  <div class="proj-hero-content">
    <h1 class="proj-hero-title">Bumble Bee Collective Acclimation</h1>
    <p class="proj-hero-subtitle">
      Linking individual physiology to colony-level responses to thermal stress.
    </p>
  </div>
</section>

<!-- CONTENT -->
<section class="proj-wrap">

  <!-- LEDE -->
  <div class="proj-lede">
    <p>
      Bumble bees are essential pollinators that face rising thermal stress as climates warm.
      We study how physiology and collective behavior interact to determine how bees respond
      to changing temperatures, from individual queens to entire colonies.
    </p>
  </div>

  <div class="proj-panels">

    <!-- SECTION 1 -->
    <article class="panel">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/bombus_breathing.png"
             alt="Different breathing patterns between species">
        <div class="fig-label">Section 1</div>
      </div>

      <div class="panel-text">
        <h2>Thermal sensitivity of queen physiology</h2>
        <p>
          We study how temperature shapes the physiology of bumble bee queens during
          colony founding. In our work, queens exposed to warm temperatures showed little
          evidence of individual acclimation in <b>metabolic rate</b>, <b>water loss rate</b>,
          or <b>thermal tolerance</b>. At the same time, bee species differ in how they breathe,
          and certain species show greater thermal sensitivity of metabolic rate than others.
        </p>

        <ul class="key-points">
          <li><b>Metabolic rate:</b> species differ in thermal sensitivity</li>
          <li><b>Water loss:</b> limited evidence for individual acclimation</li>
          <li><b>Respiration:</b> interspecific differences in physiological responses to heat</li>
        </ul>

        <div class="callout">
          <div class="callout-title">Goal</div>
          <p>
            Understand how physiological differences among bee species shape their
            vulnerability to warming climates.
          </p>
        </div>
      </div>
    </article>

    <!-- SECTION 2 -->
    <article class="panel panel--reverse">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/bombus.jpg"
             alt="Bumble bee nest and coordinated behavior illustration">
        <div class="fig-label">Section 2</div>
      </div>

      <div class="panel-text">
        <h2>Collective acclimation in whole colonies</h2>
        <p>
          Because individual queens show limited physiological acclimation, we are now
          asking whether entire colonies can acclimate collectively. Bumble bee nests
          function as integrated systems in which workers regulate the thermal environment
          through coordinated activity, movement, and nest-level behavior.
        </p>

        <ul class="key-points">
          <li><b>Nest responses:</b> colonies exposed to warm and cool environments</li>
          <li><b>Coordinated behavior:</b> workers collectively regulate nest conditions</li>
          <li><b>Superorganism physiology:</b> colony-level buffering of thermal stress</li>
        </ul>

        <div class="callout">
          <div class="callout-title">Big question</div>
          <p>
            Can bumble bee colonies acclimate as superorganisms, even when individual bees
            show limited physiological flexibility?
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

</section>
