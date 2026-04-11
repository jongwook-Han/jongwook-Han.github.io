---
layout: page
title: audience
permalink: /audience/
description: Private audience analytics for the site owner.
sitemap: false
_styles: |
  .audience-shell {
    padding: 1.35rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 1.4rem;
    background: var(--global-card-bg-color);
    box-shadow: 0 20px 40px -28px var(--global-shadow-color);
  }

  .audience-note {
    margin-bottom: 0.9rem;
    color: var(--global-text-color-light);
  }

  .audience-frame {
    width: 100%;
    min-height: 78vh;
    border: 0;
    border-radius: 1rem;
    background: var(--global-bg-color);
  }

  .audience-steps {
    margin-bottom: 0;
    padding-left: 1.2rem;
  }

  .audience-steps li + li {
    margin-top: 0.55rem;
  }
---
{% if site.enable_pirsch_analytics and site.pirsch_analytics %}
  <div class="audience-shell">
    <p class="audience-note">
      This page is intentionally not linked in the main navigation. Open it only when you want to check private audience analytics.
    </p>
    <iframe
      class="audience-frame"
      src="{{ site.pirsch_dashboard_url }}"
      loading="lazy"
      referrerpolicy="strict-origin-when-cross-origin"
      title="Audience analytics dashboard"
    ></iframe>
  </div>
{% else %}
  <div class="audience-shell">
    <p class="audience-note">
      The analytics page is ready, but tracking is not active yet.
    </p>
    <ol class="audience-steps">
      <li>Create a Pirsch site for <code>jongwook-han.github.io</code>.</li>
      <li>Paste the Pirsch identification code into <code>pirsch_analytics</code> in <code>_config.yml</code>.</li>
      <li>Keep <code>pirsch_dashboard_url</code> as <code>https://dashboard.pirsch.io/</code> for a login-protected view, or replace it with a Pirsch access-link embed URL if you want an embedded public dashboard.</li>
      <li>After the next deploy, open <code>/audience/</code> in a separate tab to inspect countries, cities, referrers, and other traffic stats.</li>
    </ol>
  </div>
{% endif %}
