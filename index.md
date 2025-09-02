---
title: "Home"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.45"
  overlay_image: /assets/images/header.jpg
intro:
  - excerpt: "Welcome. This is a generic placeholder for your personal website."
feature_row:
  - title: "About"
    excerpt: "A short bio and background."
    url: "/about/"
    btn_label: "Learn more"
    btn_class: "btn--primary"
  - title: "Publications"
    excerpt: "Selected publications via BibTeX."
    url: "/publications/"
    btn_label: "View"
  - title: "Highlights"
    excerpt: "Notable updates, media, awards, or milestones."
    url: "/highlights/"
    btn_label: "Browse"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
