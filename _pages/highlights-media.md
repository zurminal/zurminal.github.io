---
title: "Highlights — Media Coverage"
permalink: /highlights/media/
layout: single
author_profile: true
---

{% assign media = site.highlights | where_exp: "i", "i.tags contains 'media' or i.tags contains 'cover'" %}

{% include highlights-list.html items=media %}

