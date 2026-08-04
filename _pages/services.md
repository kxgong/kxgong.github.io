---
layout: page
title: services
permalink: /services/
nav: true
nav_order: 6
description: Academic services, reviewer activities, and invited talks.
---

<div class="services-section">

  <h2 class="section-title">
    <span class="section-icon">🛠️</span> Academic Service
  </h2>

  <div class="svc-entry">
    <div class="svc-title">Conference Reviewer</div>
    <div class="svc-detail">
      NeurIPS, ICML, CVPR, ICCV, ECCV, AAAI
    </div>
  </div>

  <div class="svc-entry">
    <div class="svc-title">Journal Reviewer</div>
    <div class="svc-detail">
      IEEE TPAMI, IEEE TMM
    </div>
  </div>

  <hr class="svc-divider"/>

  <h2 class="section-title">
    <span class="section-icon">🎤</span> Invited Talks
  </h2>

  <div class="svc-entry">
    <div class="svc-row">
      <div class="svc-talk-title">Metasaug: Meta Semantic Augmentation for Long-Tailed Visual Recognition</div>
      <div class="svc-date">10/2021</div>
    </div>
    <div class="svc-venue">VALSE</div>
  </div>

  <div class="svc-entry">
    <div class="svc-row">
      <div class="svc-talk-title">Metasaug: Meta Semantic Augmentation for Long-Tailed Visual Recognition</div>
      <div class="svc-date">03/2021</div>
    </div>
    <div class="svc-venue">BAAI (Beijing Academy of Artificial Intelligence)</div>
  </div>

</div>

<style>
  .services-section {
    max-width: 100%;
    margin-top: 1.5rem;
  }
  .section-title {
    display: flex;
    align-items: center;
    gap: 0.6rem;
    font-size: 1.6rem;
    font-weight: 700;
    margin: 0 0 1.5rem 0;
    color: #1a202c;
  }
  .section-title:not(:first-of-type) {
    margin-top: 2rem;
  }
  .section-icon {
    font-size: 1.6rem;
    line-height: 1;
  }
  .svc-entry {
    margin-bottom: 1.2rem;
  }
  .svc-title {
    font-weight: 700;
    color: #1a202c;
    font-size: 1.05rem;
    margin-bottom: 0.3rem;
  }
  .svc-detail {
    color: #2a8a8a;
    font-size: 1rem;
  }
  .svc-row {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 1rem;
    margin-bottom: 0.2rem;
  }
  .svc-talk-title {
    font-weight: 600;
    color: #1a202c;
    font-size: 1rem;
  }
  .svc-date {
    color: #6b7280;
    font-size: 0.95rem;
    white-space: nowrap;
  }
  .svc-venue {
    color: #2a8a8a;
    font-size: 0.95rem;
  }
  .svc-divider {
    border: 0;
    border-top: 1px solid #e5e7eb;
    margin: 1.5rem 0;
  }
</style>
