---
title: Pushkin Fairytales index
layout: index
---


<div class = "grid_cell">
  {% for item in site.archives %}
  <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
    {{ item.title }}
  {% endfor %}