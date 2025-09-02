---
title: "Highlights — Career"
permalink: /highlights/career/
layout: single
author_profile: true
---

{% assign career = site.highlights | where_exp: "i", "i.tags contains 'profile' or i.tags contains 'career'" %}

{% include highlights-list.html items=career %}

