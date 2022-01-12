---
title: The Tale of Golden Cockerel
layout: archive
abbr: golden-cockerel
publication date: 1834
image-url: https://skaz-pushkina.ru/ill/z_16.jpg
original-text:
translation-in-verse:
plot/summary-translation: 
Tags:
---



<div class = "container">
  {% for item in site.archives %}
  <div id = "content">
    <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
    {{ item.title }}
  </div>
{% endfor %}
</div>