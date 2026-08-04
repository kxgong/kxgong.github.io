---
layout: about
title: home
permalink: /
nav: true
nav_order: 1
subtitle: <a href='https://www.cuhk.edu.hk/'>CUHK</a> MMLab. Hong Kong.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>MMLab, The Chinese University of Hong Kong</p>
    <p>Hong Kong</p>

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: false
  limit: 10

latest_posts:
  enabled: false
---

<div id="home" class="single-page-anchor"></div>

I am a Ph.D. student at <a href='https://mmlab.ie.cuhk.edu.hk/'>MMLab</a>, The Chinese University of Hong Kong, advised by <a href='http://people.eecs.berkeley.edu/~xyyue/'>Prof. Xiangyu Yue</a>. Before this, I worked with <a href='https://shuangli.xyz'>Prof. Shuang Li</a> and <a href='https://cs.bit.edu.cn/szdw/jsml/gjjgccrc/lc_1065cf35e06845a7a667945726df0886/index.htm'>Prof. Chi Harold Liu</a> at Beijing Institute of Technology.

My research interests lie in **AR generative models** for video generation and **multi-modal language models**. I am always open to discussion and collaboration — feel free to drop me an email.

<section id="news" class="home-section">
  <h2 class="home-section-title"><i class="fa-solid fa-newspaper home-section-icon"></i> News</h2>
  {% include news.liquid limit=true %}
</section>

<section id="experience" class="home-section">
  <h2 class="home-section-title"><i class="fa-solid fa-briefcase home-section-icon"></i> Experience</h2>

  <div class="timeline-entry">
    <div class="entry-row">
      <div class="entry-name">Hunyuan @Tencent</div>
      <div class="entry-meta">10/2025 - Present<br>Shenzhen</div>
    </div>
    <div class="entry-subtitle">Research Intern</div>
    <div class="entry-description">Mentors: Jian-Wei Zhang and Miles Yang</div>
    <div class="entry-description"><strong>Research Topics:</strong> Unified Understanding and Generation, Video Generation</div>
    <div class="entry-description"><strong>Core Contribution:</strong> Hunyuan Video</div>
    <div class="entry-description"><strong>Contribution:</strong> Hunyuan Image</div>
  </div>

  <hr class="entry-divider">

  <div class="timeline-entry">
    <div class="entry-row">
      <div class="entry-name">Kuaishou Tech @Kling</div>
      <div class="entry-meta">05/2024 - 08/2025<br>Shenzhen</div>
    </div>
    <div class="entry-subtitle">Research Intern</div>
    <div class="entry-description">Mentor: <a href="https://xinntao.github.io/">Xintao Wang</a></div>
    <div class="entry-description"><strong>Research Topics:</strong> Autoregressive Visual Generation, Unified Understanding and Generation</div>
  </div>

  <hr class="entry-divider">

  <div class="timeline-entry">
    <div class="entry-row">
      <div class="entry-name">Shanghai AI Lab</div>
      <div class="entry-meta">11/2022 - 05/2024<br>Beijing</div>
    </div>
    <div class="entry-subtitle">Research Intern</div>
    <div class="entry-description">Mentor: Xiangyu Yue</div>
    <div class="entry-description"><strong>Research Topics:</strong> Multi-modal LLM</div>
  </div>
</section>

<section id="education" class="home-section">
  <h2 class="home-section-title"><i class="fa-solid fa-graduation-cap home-section-icon"></i> Education</h2>

  <div class="timeline-entry">
    <div class="entry-row">
      <div class="entry-name">The Chinese University of Hong Kong</div>
      <div class="entry-meta">Sep. 2023 - Present<br>Hong Kong, China</div>
    </div>
    <div class="entry-subtitle">Ph.D. in MMLAB (Information Engineering)</div>
    <div class="entry-description">Supervisor: <a href="http://people.eecs.berkeley.edu/~xyyue/">Prof. Xiangyu Yue</a></div>
    <div class="entry-description"><strong>Research Topics:</strong> Multi-modal Learning, Generative Models</div>
  </div>

  <hr class="entry-divider">

  <div class="timeline-entry">
    <div class="entry-row">
      <div class="entry-name">Beijing Institute of Technology</div>
      <div class="entry-meta">2020 - 2023<br>Beijing, China</div>
    </div>
    <div class="entry-subtitle">Master's Degree in Computer Science</div>
    <div class="entry-description"><strong>Honor:</strong> National Scholarship, Ministry of Education of China (2021)</div>
  </div>

  <hr class="entry-divider">

  <div class="timeline-entry">
    <div class="entry-row">
      <div class="entry-name">Beijing Institute of Technology</div>
      <div class="entry-meta">2016 - 2020<br>Beijing, China</div>
    </div>
    <div class="entry-subtitle">Bachelor's Degree in Software Engineering</div>
  </div>
</section>

<section id="research" class="home-section">
  <h2 class="home-section-title"><i class="fa-solid fa-flask home-section-icon"></i> Research</h2>
  {% include selected_papers.liquid %}
</section>

<section id="services" class="home-section">
  <h2 class="home-section-title"><i class="fa-solid fa-handshake-angle home-section-icon"></i> Services</h2>

  <div class="service-block">
    <div class="entry-name">Conference Reviewer</div>
    <div class="entry-subtitle">NeurIPS, ICML, CVPR, ICCV</div>
  </div>

  <div class="service-block invited-talks">
    <h3>Invited Talks</h3>
    <div class="entry-row talk-row">
      <div>
        <div class="talk-title">MetaSAug: Meta Semantic Augmentation for Long-Tailed Visual Recognition</div>
        <div class="entry-subtitle">VALSE</div>
      </div>
      <div class="entry-meta">10/2021</div>
    </div>
    <div class="entry-row talk-row">
      <div>
        <div class="talk-title">MetaSAug: Meta Semantic Augmentation for Long-Tailed Visual Recognition</div>
        <div class="entry-subtitle">BAAI (Beijing Academy of Artificial Intelligence)</div>
      </div>
      <div class="entry-meta">03/2021</div>
    </div>
  </div>
</section>

<style>
  html {
    scroll-behavior: smooth;
  }

  .single-page-anchor,
  .home-section {
    scroll-margin-top: 5.5rem;
  }

  .single-page-anchor {
    height: 1px;
  }

  .home-section {
    clear: both;
    padding-top: 3rem;
  }

  .home-section-title {
    display: flex;
    align-items: center;
    gap: 0.65rem;
    margin: 0 0 1.75rem;
    color: var(--global-text-color);
    font-size: 1.65rem;
    font-weight: 700;
  }

  .home-section-icon {
    width: 1.7rem;
    color: var(--global-theme-color);
    text-align: center;
  }

  .timeline-entry {
    margin-bottom: 1.5rem;
  }

  .entry-row {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 1.25rem;
    margin-bottom: 0.35rem;
  }

  .entry-name,
  .talk-title {
    color: var(--global-text-color);
    font-size: 1.05rem;
    font-weight: 700;
  }

  .entry-meta {
    flex-shrink: 0;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
    line-height: 1.45;
    text-align: right;
    white-space: nowrap;
  }

  .entry-subtitle {
    margin-bottom: 0.45rem;
    color: var(--global-theme-color);
    font-size: 1rem;
  }

  .entry-description {
    margin-bottom: 0.25rem;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
  }

  .entry-divider {
    margin: 1.5rem 0;
    border: 0;
    border-top: 1px solid var(--global-divider-color);
  }

  .service-block {
    margin-bottom: 1.75rem;
  }

  .invited-talks {
    margin-top: 2.5rem;
  }

  .invited-talks h3 {
    margin-bottom: 1.25rem;
    color: var(--global-text-color);
    font-size: 1.25rem;
    font-weight: 700;
  }

  .talk-row {
    padding: 0.85rem 0;
    border-bottom: 1px solid var(--global-divider-color);
  }

  @media (max-width: 576px) {
    .home-section {
      padding-top: 2.5rem;
    }

    .entry-row {
      flex-direction: column;
      gap: 0.35rem;
    }

    .entry-meta {
      text-align: left;
      white-space: normal;
    }
  }
</style>
