---
title: "Full Path Transit Technology"
layout: splash
header:
  overlay_color: "#fff"
  overlay_filter: "rgba(112, 66, 20, 0.5)"
  overlay_image: /assets/images/hero.jpg
excerpt: "Wholistic Thinking and Tools for Community Transportation"
feature_row:
  - image_path: /assets/images/aaron-burden-151465-unsplash.jpg
    alt: "placeholder image 2"
    title: "It's Time for Technology to Better Serve Small Transit."
    excerpt: 'We can help you find your way.'
    url: "services/"
    btn_label: "What we do"
    btn_class: "btn--primary"
---

{% include feature_row id="feature_row" type="left" %}

# Recent Articles
{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}

---
Find older posts in the [blog archive]({{ "blog" | relative_url }})
