---
layout: page
title: "Modeling Endotherm Performance"
permalink: /research/endotherms/
---

<!-- HERO IMAGE -->
<section class="proj-hero">
  <img class="proj-hero-image"
       src="{{ site.baseurl }}/assets/tree_swallow.jpg"
       alt="Endotherm in thermal environment">

  <div class="proj-hero-overlay"></div>

  <div class="proj-hero-content">
    <h1 class="proj-hero-title">Modeling Endotherm Performance</h1>
    <p class="proj-hero-subtitle">
      Linking heat balance to performance, species distributions, and climate responses.
    </p>
  </div>
</section>

<!-- CONTENT -->
<section class="proj-wrap">

  <!-- LEDE -->
  <div class="proj-lede">
    <p>
      Endotherms maintain body temperature through internal heat production, but the
      energetic costs of doing so vary dramatically across environments. We study how
      heat exchange shapes performance and use those mechanisms to predict distributions,
      range limits, and responses to climate change.
    </p>
  </div>

  <div class="proj-panels">

    <!-- SECTION 1 -->
<article class="panel panel--wide">

  <div class="panel-figure panel-figure--wide">
    <img src="{{ site.baseurl }}/assets/cartoon.png"
         alt="Endotherm thermal performance curve illustration">
    <div class="fig-label">Section 1</div>
  </div>

  <div class="panel-text panel-text--wide">
    <h2>Thermal performance and heat balance</h2>

    <p>
      Thermal performance curves are widely used to describe how temperature
      shapes organismal function, but there are few broadly applicable
      frameworks for endotherms. Because endotherms actively regulate body
      temperature, performance depends not simply on environmental temperature
      but on the balance of heat exchange between organisms and their
      environments.
    </p>

    <p>
      Our work proposes that performance in endotherms can be understood using
      <b>net sensible heat flux</b>. When heat gain and heat loss are balanced,
      thermoregulatory costs are minimized, producing a natural prediction for
      the environmental conditions where performance is highest.
    </p>

    <ul class="key-points">
      <li><b>Heat exchange:</b> net sensible heat flux between organism and environment</li>
      <li><b>Thermal balance:</b> minimal metabolic costs of thermoregulation</li>
      <li><b>Optimal performance:</b> predicted to occur near heat balance</li>
    </ul>

    <div class="callout">
      <div class="callout-title">Concept</div>
      <p>
        In endotherms, optimal performance may occur where environmental heat
        exchange minimizes thermoregulatory costs.
      </p>
    </div>

  </div>

</article>

    <!-- SECTION 2 -->
    <article class="panel panel--reverse">
      <div class="panel-figure">
        <img src="{{ site.baseurl }}/assets/Q_prediction.png"
             alt="Endotherm climate and distribution illustration">
        <div class="fig-label">Section 2</div>
      </div>

      <div class="panel-text">
        <h2>Species distributions and climate responses</h2>
        <p>
          Because heat balance depends on both organismal traits and environmental
          conditions, this framework can be used to predict how endotherms perform
          across landscapes and through time. By linking physiology to climate data,
          we can identify where animals experience favorable thermal environments
          and where thermoregulatory costs become limiting.
        </p>

        <ul class="key-points">
          <li><b>Spatial predictions:</b> mapping thermal performance across landscapes</li>
          <li><b>Temporal dynamics:</b> seasonal and daily variation in heat balance</li>
          <li><b>Climate change:</b> forecasting shifts in suitable environments</li>
        </ul>

        <div class="callout">
          <div class="callout-title">Big question</div>
          <p>
            Can heat balance provide a mechanistic link between physiology,
            climate, and the geographic distributions of endothermic animals?
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
  /* WIDE PANEL FOR CONCEPTUAL FIGURES */

.panel--wide{
  grid-template-columns: 1fr;
}

.panel-figure--wide{
  padding: 1.5rem 1.5rem 0 1.5rem;
}

.panel-figure--wide img{
  width: 100%;
  height: auto;
  object-fit: contain;
}

.panel-text--wide{
  padding: 1.25rem 1.75rem 1.75rem 1.75rem;
  max-width: 900px;
}
</style>

</section>
