---
title: Pushkin Fairytales index
layout: index
---

<div id = "container">
  {% for item in site.archives %}
  <div class = "grid_cell">
    <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
    {{ item.title }}
  </div>
{% endfor %}
</div>