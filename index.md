---
title: "Home"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.45"
  overlay_image: /assets/images/header.jpg
feature_row:
  - title: "About"
    excerpt: "An overview of my background, research interests, and professional journey."
    url: "/about/"
    btn_label: "Learn more"
    btn_class: "btn--primary"
  - title: "Publications"
    excerpt: "Peer-reviewed research and selected publications."
    url: "/publications/"
    btn_label: "View"
  - title: "Highlights"
    excerpt: "Key milestones, awards, and media coverage"
    url: "/highlights/"
    btn_label: "Browse"
---

{% include feature_row %}

{%- comment -%}
To add a centered intro blurb above the feature cards later,
uncomment the `intro:` block in the front matter and include:

intro:
  - excerpt: "Write a short welcome message here."

Then add this include where you want it to appear:
{% include feature_row id="intro" type="center" %}
{%- endcomment -%}
