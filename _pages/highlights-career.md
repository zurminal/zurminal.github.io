---
title: "Highlights — Career"
permalink: /highlights/career/
layout: single
author_profile: false
classes: wide
---

{% assign career = site.highlights | where_exp: "i", "i.tags contains 'career'" %}

{% include highlights-list.html items=career %}
