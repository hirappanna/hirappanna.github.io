---
layout: page
title: Photos
date: {}
comments: false
published: true
images:
- image_path: /assets/img/egg-plate-eggplant.jpg
  title: Egg Plate
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li>
      <img src="{{ image.image_path }}" alt="{{ image.title }}">
    </li>
  {% endfor %}
</ul>
