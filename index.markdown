---
title: Pushkin Fairytales index
layout: index
---

<div class = "container">
  {% for item in site.archives %}
  <div id = "grid_cell">
    <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
    <p class = "caption">{{ item.title }}</p>
  </div>
{% endfor %}
</div>