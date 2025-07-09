---
title: "Splash Page"
layout: splash
date: 2016-03-23T11:48:41-04:00
feature_row:
  - image_path: /assets/images/bio-photo.png
    alt: "placeholder image 1"
    title: "Projects / Code"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/bio-photo.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Blog"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/bio-photo.png
    title: "Short Stories"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    url: "#test-link-2"
    btn_label: "Go to Demo"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/bio-photo.png
    alt: "placeholder image 2"
    title: "Portfolio"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/bio-photo.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

# Thanks for stopping by
{: .text-center style="margin-top: 1rem;"}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}
