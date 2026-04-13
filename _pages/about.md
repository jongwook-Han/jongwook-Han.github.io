---
layout: about
title: about
permalink: /
subtitle: PhD Student, Graduate School of Data Science, Seoul National University

profile: false

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

# announcements:
#   enabled: true # includes a list of news items
#   scrollable: true # adds a vertical scroll bar if there are more than 3 news items
#   limit: 5 # leave blank to include all the news in the `_news` folder

# latest_posts:
#   enabled: true
#   scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#   limit: 3 # leave blank to include all the blog posts
---
<section class="home-hero">
  <p class="home-kicker">Pluralistic value alignment, psychometric evaluation, and LLM behavior</p>
  <div class="home-lead">
    <p>I'm a PhD student at Seoul National University, where I work with <a href="https://yohanjo.github.io/" target="_blank">Prof. Yohan Jo</a> on how language models represent, express, and can be aligned with diverse human values.</p>
    <p>My recent work studies pluralistic value alignment, contamination in psychometric evaluation, and robust ways to measure value expression in language models.</p>
  </div>
  <div class="home-actions">
    <a class="home-button" href="{{ '/publications/' | relative_url }}">View publications</a>
    <a class="home-button home-button-secondary home-button-icon" href="mailto:johnhan00@snu.ac.kr" aria-label="Email">
      <i class="fa-solid fa-envelope" aria-hidden="true"></i>
      <span>Email</span>
    </a>
    <a class="home-button home-button-secondary home-button-icon" href="https://scholar.google.com/citations?user=eAeLn3gAAAAJ&hl=en&oi=ao" target="_blank" aria-label="Google Scholar">
      <i class="ai ai-google-scholar" aria-hidden="true"></i>
      <span>Scholar</span>
    </a>
    <a class="home-button home-button-secondary home-button-icon" href="https://x.com/jwhansnu" target="_blank" aria-label="X">
      <i class="fa-brands fa-x-twitter" aria-hidden="true"></i>
      <span>X</span>
    </a>
  </div>
  <div class="home-signal-grid">
    <div class="home-signal">
      <span class="home-signal__label">Current</span>
      <strong class="home-signal__value">HOLI Lab, Graduate School of Data Science, Seoul National University</strong>
    </div>
    <div class="home-signal">
      <span class="home-signal__label">Focus</span>
      <strong class="home-signal__value">Value alignment, evaluation, and behavior in LLMs</strong>
    </div>
    <div class="home-signal">
      <span class="home-signal__label">Base</span>
      <strong class="home-signal__value">Seoul, South Korea</strong>
    </div>
  </div>
</section>

<div class="home-panels">
  <section class="home-panel">
    <h2>Research Focus</h2>
    <ul class="home-list">
      <li>Pluralistic value alignment for language models</li>
      <li>Psychometric and behavioral evaluation of LLMs</li>
    </ul>
  </section>
  <section class="home-panel">
    <h2>Background</h2>
    <ul class="home-list">
      <li>PhD student, Seoul National University</li>
      <li>M.S. in Electrical Engineering, KAIST</li>
      <li>B.S. in Integrated Technology, Yonsei University</li>
    </ul>
  </section>
</div>

<section class="home-section">
  <h2>Representative Work</h2>
  <div class="home-highlights home-highlights-featured">
    <article class="home-highlight home-highlight-featured">
      <span class="home-highlight__meta">ACL 2025</span>
      <h3>Value Portrait</h3>
      <p>Introduces a psychometrically validated benchmark built from real user-LLM interactions, making value assessment more reliable and ecologically grounded than annotation-heavy alternatives.</p>
      <p class="home-highlight__note">Across 44 language models, it shows consistent emphasis on Benevolence, Security, and Self-Direction, while also surfacing demographic biases in how models express values.</p>
      <a class="home-highlight__link" href="https://aclanthology.org/2025.acl-long.838/" target="_blank">Read paper</a>
    </article>
    <article class="home-highlight home-highlight-featured">
      <span class="home-highlight__meta">Working Paper</span>
      <h3>Dual Mechanisms of Value Expression: Intrinsic vs. Prompted Values in LLMs</h3>
      <p>Separates intrinsic value expression from prompted value expression and studies them mechanistically through value vectors in the residual stream and value neurons in the MLP layers.</p>
      <p class="home-highlight__note">The analysis shows that the two mechanisms partly overlap but diverge in practice: prompted values are more steerable, while intrinsic values preserve greater response diversity.</p>
      <a class="home-highlight__link" href="https://arxiv.org/abs/2509.24319" target="_blank">Read paper</a>
    </article>
  </div>
</section>

<section class="home-section">
  <h2>Contact</h2>
  <div class="home-contact-grid">
    <a class="home-contact-card" href="mailto:johnhan00@snu.ac.kr">
      <span class="home-contact-card__icon" aria-hidden="true"><i class="fa-solid fa-envelope"></i></span>
      <span class="home-contact-card__label">Email</span>
      <strong>johnhan00@snu.ac.kr</strong>
    </a>
    <a class="home-contact-card" href="https://scholar.google.com/citations?user=eAeLn3gAAAAJ&hl=en&oi=ao" target="_blank">
      <span class="home-contact-card__icon" aria-hidden="true"><i class="ai ai-google-scholar"></i></span>
      <span class="home-contact-card__label">Google Scholar</span>
      <strong>Publication profile</strong>
    </a>
    <a class="home-contact-card" href="https://x.com/jwhansnu" target="_blank">
      <span class="home-contact-card__icon" aria-hidden="true"><i class="fa-brands fa-x-twitter"></i></span>
      <span class="home-contact-card__label">X</span>
      <strong>@jwhansnu</strong>
    </a>
  </div>
</section>
