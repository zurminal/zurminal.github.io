---
title: "Highlights — Awards"
permalink: /highlights/awards/
layout: single
author_profile: true
---

{% assign awards = site.highlights | where_exp: "i", "i.tags contains 'award' or i.tags contains 'competition' or i.tags contains 'recognition'" %}

{% include highlights-list.html items=awards %}

