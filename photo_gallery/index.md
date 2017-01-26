---
layout: page
title: Photos
date: {}
comments: false
published: true
images:
- image_path: /assets/img/egg-plate-eggplant.jpg
  title: Egg Plate
- image_path: /assets/img/hands-and-tofu.jpg
  title: Tofu and Hands
- image_path: /assets/img/sauce-triptych.jpg
  title: Three Sauces
- image_path: /assets/img/hira-granola-romantic.jpg
  title: Hira with granola
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li>
      <img src="{{ image.image_path }}" alt="{{ image.title }}">
    </li>
  {% endfor %}
</ul>
