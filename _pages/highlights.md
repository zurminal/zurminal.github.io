---
title: "Highlights"
permalink: /highlights/
layout: single
author_profile: false
classes: wide
---

A collection of awards, media features, and milestones from my academic and professional journey.

{% assign awards = site.highlights | where_exp: "i", "i.tags contains 'awards'" %}
{% assign media = site.highlights | where_exp: "i", "i.tags contains 'media'" %}
{% assign career = site.highlights | where_exp: "i", "i.tags contains 'career'" %}

<section class="highlights-section">
  <h2>Awards</h2>
  {% include highlights-list.html items=awards limit=6 footer_url="/highlights/awards/" footer_label="View all awards" %}
</section>

<section class="highlights-section">
  <h2>Media Coverage</h2>
  {% include highlights-list.html items=media limit=6 footer_url="/highlights/media/" footer_label="View all media" %}
</section>

<section class="highlights-section">
  <h2>Career</h2>
  {% include highlights-list.html items=career limit=6 footer_url="/highlights/career/" footer_label="View all career highlights" %}
</section>
