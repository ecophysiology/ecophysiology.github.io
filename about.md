---
layout: page
title: Research
permalink: /research/
main_nav: true
---

<!-- HERO VIDEO -->
<section class="hero">
  <!-- Replace src with your video file path -->
  <video class="hero-video" autoplay muted loop playsinline preload="auto">
    <source src="{{ site.baseurl }}/assets/research_project.mp4" type="video/mp4">
  </video>

  <div class="hero-overlay"></div>

  <div class="hero-content">
    <h1 class="hero-title">Research Projects</h1>
    <p class="hero-subtitle">
      We use physiology and models to predict how animals respond to environmental change.
    </p>
  </div>
</section>

<!-- PROJECTS -->
<section class="projects">

  <!-- 1 -->
  <article class="project" id="skin-breathing">
    <div class="project-media">
      <img src="{{ site.baseurl }}/assets/hyla_versicolor.png" alt="Amphibian skin breathing project image">
    </div>
    <div class="project-body">
      <h2 class="project-title">Amphibian Skin Breathing</h2>
      <p class="project-teaser">
        We quantify how skin structure and function jointly govern oxygen uptake and water loss.
      </p>
      <div class="tag-row">
        <span class="tag">Cutaneous exchange</span>
        <span class="tag">Water balance</span>
        <span class="tag">Boundary layers</span>
      </div>
      <a class="project-link" href="{{ site.baseurl }}/research/skin-breathing/">Explore →</a>
    </div>
  </article>

  <!-- 2 -->
  <article class="project project--reverse" id="tortoise">
    <div class="project-media">
      <img src="{{ site.baseurl }}/assets/desert_tortoise.webp" alt="Desert tortoise project image">
    </div>
    <div class="project-body">
      <h2 class="project-title">Desert Tortoise Conservation Physiology</h2>
      <p class="project-teaser">
        We link heat and hydration physiology with landscapes to predict persistence in warming deserts.
      </p>
      <div class="tag-row">
        <span class="tag">Heat stress</span>
        <span class="tag">Hydration</span>
        <span class="tag">Persistence forecasting</span>
      </div>
      <a class="project-link" href="{{ site.baseurl }}/research/tortoise/">Explore →</a>
    </div>
  </article>

  <!-- 3 -->
  <article class="project" id="salamanders">
    <div class="project-media">
      <img src="{{ site.baseurl }}/assets/plethodon.jpeg" alt="Woodland salamander project image">
    </div>
    <div class="project-body">
      <h2 class="project-title">Woodland Salamander Ecophysiology</h2>
      <p class="project-teaser">
        We connect microclimate, performance, and physiology across landscapes to understand range limits and risk.
      </p>
      <div class="tag-row">
        <span class="tag">Microclimate</span>
        <span class="tag">Performance</span>
        <span class="tag">Range limits</span>
      </div>
      <a class="project-link" href="{{ site.baseurl }}/research/salamanders/">Explore →</a>
    </div>
  </article>

  <!-- 4 -->
  <article class="project project--reverse" id="bumblebees">
    <div class="project-media">
      <img src="{{ site.baseurl }}/assets/bombus.jpg" alt="Bumble bee project image">
    </div>
    <div class="project-body">
      <h2 class="project-title">Bumble Bee Collective Acclimation</h2>
      <p class="project-teaser">
        We study how colony-level behavior regulates thermal and energetic conditions that shape resilience to change.
      </p>
      <div class="tag-row">
        <span class="tag">Collective behavior</span>
        <span class="tag">Nest thermoregulation</span>
        <span class="tag">Energetics</span>
      </div>
      <a class="project-link" href="{{ site.baseurl }}/research/bumblebees/">Explore →</a>
    </div>
  </article>

  <!-- 5 -->
  <article class="project" id="endotherms">
    <div class="project-media">
      <img src="{{ site.baseurl }}/assets/tree_swallow.jpg" alt="Endotherm performance project image">
    </div>
    <div class="project-body">
      <h2 class="project-title">Modeling endotherm Performance </h2>
      <p class="project-teaser">
        We quantify how heat flux shapes performance and exposure to climate change risk in endotherms.
      </p>
      <div class="tag-row">
        <span class="tag">Wind niche</span>
        <span class="tag">Heat flux</span>
        <span class="tag">Performance limits</span>
      </div>
      <a class="project-link" href="{{ site.baseurl }}/research/endotherms/">Explore →</a>
    </div>
  </article>

</section>

<!-- STYLES (keep here for now; later we can move to your SCSS) -->
<style>
  /* HERO */
  .hero{
    position:relative;
    width:100%;
    min-height: 520px;
    border-radius: 18px;
    overflow:hidden;
    margin: 0 0 2.5rem 0;
  }
  .hero-video{
    width:100%;
    height:100%;
    object-fit:cover;
    position:absolute;
    top:0; left:0;
    transform: scale(1.02);
  }
  .hero-overlay{
    position:absolute;
    top:0; left:0;
    width:100%; height:100%;
    background: linear-gradient(90deg, rgba(0,0,0,0.35) 0%, rgba(0,0,0,0.18) 55%, rgba(0,0,0,0.05) 100%);
  }
  .hero-content{
    position:absolute;
    bottom: 3rem;     /* controls vertical position */
    left: 3rem;       /* controls horizontal position */
    z-index:2;
    max-width: 700px;
  }
  .hero-title{
    font-size: clamp(2.2rem, 4vw, 3.2rem);
    line-height: 1.05;
    margin: 0 0 0.75rem 0;
    color: #fff;
    letter-spacing: -0.02em;
  }
  .hero-subtitle{
    margin: 0 0 1.25rem 0;
    color: rgba(255,255,255,0.88);
    font-size: 1.12rem;
    line-height: 1.55;
    max-width: 62ch;
  }
  .hero-chips{ display:flex; gap: 10px; flex-wrap: wrap; }
  .chip{
    color: rgba(255,255,255,0.92);
    background: rgba(255,255,255,0.12);
    border: 1px solid rgba(255,255,255,0.18);
    padding: 0.45rem 0.7rem;
    border-radius: 999px;
    font-size: 0.9rem;
    backdrop-filter: blur(6px);
  }

  /* PROJECTS */
  .projects{ display: grid; gap: 1.25rem; margin-top: 1rem; }
  .project{
    display:grid;
    grid-template-columns: 1.15fr 1fr;
    gap: 1.2rem;
    align-items: center;
    background: #fff;
    border: 1px solid rgba(0,0,0,0.08);
    border-radius: 18px;
    overflow:hidden;
    box-shadow: 0 6px 22px rgba(0,0,0,0.06);
  }
  .project--reverse{ grid-template-columns: 1fr 1.15fr; }
  .project--reverse .project-media{ order: 2; }
  .project--reverse .project-body{ order: 1; }

  .project-media{
    padding: 1rem;
  }

  .project-media img{
    width:100%;
    height:320px;
    object-fit: cover;
    display:block;
    border-radius: 14px;
  }
  .project-body{
    padding: 1.5rem 1.5rem;
  }
  .project-title{
    margin: 0 0 0.55rem 0;
    font-size: 1.65rem;
    letter-spacing: -0.01em;
  }
  .project-teaser{
    margin: 0 0 0.9rem 0;
    color: rgba(0,0,0,0.72);
    line-height: 1.55;
    max-width: 62ch;
  }
  .tag-row{ display:flex; gap: 8px; flex-wrap: wrap; margin-bottom: 0.9rem; }
  .tag{
    font-size: 0.86rem;
    color: rgba(0,0,0,0.70);
    background: rgba(0,0,0,0.04);
    border: 1px solid rgba(0,0,0,0.06);
    padding: 0.35rem 0.6rem;
    border-radius: 999px;
  }
  .project-link{
    display:inline-block;
    text-decoration:none;
    font-weight: 600;
    border-bottom: 2px solid rgba(86,145,232,0.35);
    padding-bottom: 2px;
  }
  .page-title {
    display: none;
  }

  /* RESPONSIVE */
  @media (max-width: 860px){
    .project, .project--reverse{
      grid-template-columns: 1fr;
    }
    .project--reverse .project-media,
    .project--reverse .project-body{
      order: unset;
    }
    .project-media img{ height: 260px; }
  }
</style>
