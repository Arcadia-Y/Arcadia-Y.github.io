---
layout: default
title: Under Maintenance
permalink: /
---

<style>
  .maintenance-home {
    min-height: calc(100vh - 14rem);
    display: grid;
    place-items: center;
    padding: 4rem 1rem;
    text-align: center;
  }

  .maintenance-home__inner {
    max-width: 42rem;
  }

  .maintenance-home__eyebrow {
    margin-bottom: 1rem;
    color: var(--global-theme-color);
    font-size: 0.8rem;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .maintenance-home h1 {
    margin-bottom: 1rem;
    font-size: clamp(2.5rem, 8vw, 5rem);
    line-height: 1;
  }

  .maintenance-home p {
    margin: 0 auto;
    max-width: 32rem;
    color: var(--global-text-color-light);
    font-size: 1.1rem;
    line-height: 1.7;
  }
</style>

<main class="maintenance-home" aria-labelledby="maintenance-title">
  <div class="maintenance-home__inner">
    <div class="maintenance-home__eyebrow">Temporary notice</div>
    <h1 id="maintenance-title">Under Maintenance</h1>
    <p>This homepage is temporarily offline. Please check back soon.</p>
  </div>
</main>
