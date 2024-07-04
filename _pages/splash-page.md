---
title: "Splash Page"
layout: splash
permalink: /splash-page/
date: 2024-07-04T22:36:00+10:00
header:
  overlay_image: /assets/images/grant-mciver-pmUEwPKL5IE-unsplash_1280.jpg
  excerpt:     
  caption: "Photo credit: Grant McIver(https://unsplash.com)"

feature_row:
  - image_path: assets/images/MTNK.png
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/MTNK.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "https://marie-tiang-nk.github.io/analyst-portfolio/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/MTNK.png
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/MTNK.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "https://marie-tiang-nk.github.io/analyst-portfolio/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/MTNK.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "https://marie-tiang-nk.github.io/analyst-portfolio/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/MTNK.png
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "https://marie-tiang-nk.github.io/analyst-portfolio/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
