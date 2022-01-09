---
title: Pushkin Fairytales index
layout: index
---


  {% for item in site.archives %}
  <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
        <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
  {% endfor %}