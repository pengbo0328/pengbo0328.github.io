---
title: "Pgpool-II"
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  actions:
    - label: "<i class='fas fa-download'></i> Download Now"
      url: "/download/"
    - label: "<i class='fas fa-file-lines'></i> Documetation"
      url: "/docs/"
excerpt: >
  Feature-rich, open-source middleware for PostgreSQL connection pooling, load balancing and high availability.<br />
  <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.28.0">Latest release</a></small>
feature_row:
  - title: "<i class='fas fa-unlock'></i> 100% Open Source"
    alt: "customizable"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - title: "<i class='fas fa-sliders-h'></i> Feature-rich"
    alt: "fully responsive"
    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/docs/"
    btn_class: "btn--primary"
    btn_label: "See All Features"
  - title: "<i class='fas fa-play'></i> Getting Started"
    alt: "100% free"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/docs/"
    btn_class: "btn--primary"
    btn_label: "Tutorial"      
---

{% include feature_row %}

## Latest News

{% assign latest = site.news | sort: "date" | reverse | first %}

## [{{ latest.title }}]({{ latest.url }})

{{ latest.content }}

[View All News <i class="fas fa-arrow-right"></i>](/news_archive/){: .btn .btn--primary}
