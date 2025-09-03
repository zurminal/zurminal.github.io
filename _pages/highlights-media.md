---
title: "Highlights — Media Coverage"
permalink: /highlights/media/
layout: single
author_profile: false
classes: wide
---

{% assign media = site.highlights | where_exp: "i", "i.tags contains 'media'" %}

{% include highlights-list.html items=media %}
