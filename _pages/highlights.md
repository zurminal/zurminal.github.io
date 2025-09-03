---
title: "Highlights"
permalink: /highlights/
layout: single
author_profile: true
---

Browse highlights by category.

{% assign awards = site.highlights | where_exp: "i", "i.tags contains 'awards'" %}
{% assign media = site.highlights | where_exp: "i", "i.tags contains 'media'" %}
{% assign career = site.highlights | where_exp: "i", "i.tags contains 'career'" %}

## Awards
{% include highlights-list.html items=awards limit=6 %}

<a class="highlights-viewall" href="/highlights/awards/">View all awards</a>

<div class="section-separator"></div>

## Media Coverage
{% include highlights-list.html items=media limit=6 %}

<a class="highlights-viewall" href="/highlights/media/">View all media</a>

<div class="section-separator"></div>

## Career
{% include highlights-list.html items=career limit=6 %}

<a class="highlights-viewall" href="/highlights/career/">View all career highlights</a>
