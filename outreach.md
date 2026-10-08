---
layout: page
title: Outreach
permalink: /outreach/
main_nav: true
---

<!-- OUTREACH HEADER -->
<section class="outreach-hero">
  <div class="outreach-hero-content">
    <h1 class="outreach-hero-title">Outreach</h1>
    <p class="outreach-hero-subtitle">
      Sharing research beyond the lab through media, classroom partnerships, and public engagement.
    </p>
  </div>
</section>

<!-- OUTREACH POSTS -->
<section class="outreach-posts">

  <!-- 1: CHAPELBORO -->
  <article class="outreach-post">
    <div class="outreach-media">
      <img src="{{ site.baseurl }}/assets/the_hill.png"
           alt="Eric Riddell interview with 97.9 The Hill">
    </div>
    <div class="outreach-body">
      <div class="outreach-label">Media</div>
      <h2 class="outreach-title">Into the World of Salamanders</h2>
      <p class="outreach-text">
        I joined Aaron Keck on Chapelboro’s “Tell Me Something” to talk about the
        remarkable diversity of salamanders in North Carolina and why this region
        is such an important place for studying them.
      </p>
      <a class="outreach-link"
         href="https://chapelboro.com/the-aaron-keck-show/on-air-today/tell-me-something-into-the-world-of-salamanders-with-uncs-eric-riddell"
         target="_blank" rel="noopener noreferrer">
        Listen to the interview →
      </a>
    </div>
  </article>

  <!-- 2: SCIREN -->
  <article class="outreach-post outreach-post--reverse">
    <div class="outreach-media">
      <!-- Replace sciren.jpg with the filename of your SciREN photo. -->
      <img src="{{ site.baseurl }}/assets/sciren.jpg"
           alt="Ecophysiology Lab participating in SciREN">
    </div>
    <div class="outreach-body">
      <div class="outreach-label">K–12 Outreach</div>
      <h2 class="outreach-title">Bringing Research into the Classroom</h2>
      <p class="outreach-text">
        Our lab participates in the Scientific Research and Education Network
        (SciREN), a program that connects scientists with K–12 educators to bring
        current science into classrooms. Through SciREN, we developed a lesson
        plan, <em>Adapting to Survive: How Animals Thrive in Their Environments</em>,
        which introduces students to behavioral, physiological, and evolutionary
        responses to environmental change.
      </p>
      <!-- Replace # with the website you want this post to link to. -->
      <a class="outreach-link" href="#"
         target="_blank" rel="noopener noreferrer">
        Learn more about SciREN →
      </a>
    </div>
  </article>

</section>

<style>
  .page-title { display: none; }

  /* HERO */
  .outreach-hero {
    position: relative;
    width: 100%;
    min-height: 300px;
    border-radius: 18px;
    overflow: hidden;
    margin: 0 0 2.5rem 0;
    display: flex;
    align-items: flex-end;
    background:
  linear-gradient(
    120deg,
    rgba(0, 0, 0, 0.45),
    rgba(0, 0, 0, 0.15)
  ),
  url("{{ site.baseurl }}/assets/outreach.png") center / cover no-repeat;
  }
  .outreach-hero-content { padding: 3rem; max-width: 760px; }
  .outreach-hero-title {
    font-size: clamp(2.2rem, 4vw, 3.2rem);
    line-height: 1.05;
    margin: 0 0 0.75rem 0;
    color: #fff;
    letter-spacing: -0.02em;
  }
  .outreach-hero-subtitle {
    margin: 0;
    color: rgba(255,255,255,0.88);
    font-size: 1.12rem;
    line-height: 1.55;
    max-width: 62ch;
  }

  /* POSTS */
  .outreach-posts { display: grid; gap: 1.25rem; margin-top: 1rem; }
  .outreach-post {
    display: grid;
    grid-template-columns: 1.15fr 1fr;
    gap: 1.2rem;
    align-items: center;
    background: #fff;
    border: 1px solid rgba(0,0,0,0.08);
    border-radius: 18px;
    overflow: hidden;
    box-shadow: 0 6px 22px rgba(0,0,0,0.06);
  }
  .outreach-post--reverse { grid-template-columns: 1fr 1.15fr; }
  .outreach-post--reverse .outreach-media { order: 2; }
  .outreach-post--reverse .outreach-body { order: 1; }

  /* IMAGE */
  .outreach-media { padding: 1rem; }
  .outreach-media img {
    width: 100%;
    height: 340px;
    object-fit: cover;
    display: block;
    border-radius: 14px;
  }

  /* TEXT */
  .outreach-body { padding: 1.5rem; }
  .outreach-label {
    display: inline-block;
    margin-bottom: 0.7rem;
    font-size: 0.82rem;
    font-weight: 600;
    letter-spacing: 0.04em;
    text-transform: uppercase;
    color: rgba(0,0,0,0.58);
  }
  .outreach-title {
    margin: 0 0 0.65rem 0;
    font-size: 1.65rem;
    letter-spacing: -0.01em;
  }
  .outreach-text {
    margin: 0 0 1rem 0;
    color: rgba(0,0,0,0.72);
    line-height: 1.6;
    max-width: 62ch;
  }
  .outreach-link {
    display: inline-block;
    text-decoration: none;
    font-weight: 600;
    border-bottom: 2px solid rgba(86,145,232,0.35);
    padding-bottom: 2px;
  }

  /* RESPONSIVE */
  @media (max-width: 860px) {
    .outreach-hero { min-height: 260px; }
    .outreach-hero-content { padding: 2rem; }
    .outreach-post, .outreach-post--reverse { grid-template-columns: 1fr; }
    .outreach-post--reverse .outreach-media,
    .outreach-post--reverse .outreach-body { order: unset; }
    .outreach-media img { height: 280px; }
  }
</style>
