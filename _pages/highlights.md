---
title: "Highlights"
permalink: /highlights/
layout: single
author_profile: true
---

Browse highlights by category.

{% assign awards = site.highlights | where_exp: "i", "i.tags contains 'award' or i.tags contains 'competition' or i.tags contains 'recognition'" %}
{% assign media = site.highlights | where_exp: "i", "i.tags contains 'media' or i.tags contains 'cover'" %}
{% assign career = site.highlights | where_exp: "i", "i.tags contains 'profile' or i.tags contains 'career'" %}

## Awards
{% include highlights-list.html items=awards limit=6 %}

[View all awards](/highlights/awards/)

## Media Coverage
{% include highlights-list.html items=media limit=6 %}

[View all media](/highlights/media/)

## Career
{% include highlights-list.html items=career limit=6 %}

[View all career highlights](/highlights/career/)
