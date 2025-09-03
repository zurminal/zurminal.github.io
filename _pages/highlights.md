---
title: "Highlights"
permalink: /highlights/
layout: single
author_profile: false
classes: wide
---

Browse highlights by category.

{% assign awards = site.highlights | where_exp: "i", "i.tags contains 'awards'" %}
{% assign media = site.highlights | where_exp: "i", "i.tags contains 'media'" %}
{% assign career = site.highlights | where_exp: "i", "i.tags contains 'career'" %}

<section class="highlights-section">
  <h2>Awards</h2>
  {% include highlights-list.html items=awards limit=6 %}
  <a class="highlights-viewall" href="/highlights/awards/">View all awards</a>
</section>

<section class="highlights-section">
  <h2>Media Coverage</h2>
  {% include highlights-list.html items=media limit=6 %}
  <a class="highlights-viewall" href="/highlights/media/">View all media</a>
</section>

<section class="highlights-section">
  <h2>Career</h2>
  {% include highlights-list.html items=career limit=6 %}
  <a class="highlights-viewall" href="/highlights/career/">View all career highlights</a>
</section>
