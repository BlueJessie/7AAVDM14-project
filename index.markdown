---
title: Pushkin Fairytales index
layout: index
---

<div id = "gallery">
  {% for item in site.archives %}
  <div class = "grid_cell">
    <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
    <p class = "caption">{{ item.title }}</p>
  </div>
{% endfor %}
</div>