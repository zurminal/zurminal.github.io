---
title: "Highlights — Awards"
permalink: /highlights/awards/
layout: single
author_profile: false
classes: wide
---

{% assign awards = site.highlights | where_exp: "i", "i.tags contains 'awards'" %}

{% include highlights-list.html items=awards %}
