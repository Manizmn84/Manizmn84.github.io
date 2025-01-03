---
layout: page
title: first Project
description: random image from city
img: assets/img/london.jpeg
importance: 1
category: fun
related_publications: true
---

in this Project we show random images from london

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: first Project
    description: random image from city
    img: assets/img/london.jpeg
    importance: 1
    category: habit
    related_publications: true
    ---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/london.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/London.webp" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    random image from london
</div>