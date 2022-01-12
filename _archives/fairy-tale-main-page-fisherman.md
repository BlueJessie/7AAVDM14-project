---
title: The Tale of the Fisherman and the Fish
layout: archive
abbr: fisherman
publication date: 1833
image-url: https://skaz-pushkina.ru/ill/z_13.jpg
original-text: https://alexanderpushkin.ru/skazki/29-skazka-o-rybake-i-rybke-1833.html
translation-in-verse: http://www.stosvet.net/12/chandler/index9.html
plot/summary-translation: https://www.fairytales.biz/alexander-pushkin/fisherman-and-the-golden-fish.htm
plot/summary-translation: https://www.booksummary.net/the-tale-of-the-fisherman-and-the-fish-alexander-pushki
Tags: The Tale of the Fisherman and the Fish
---



<div class = "container">
  {% for item in site.archives %}
  <div id = "content">
    <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
    {{ item.title }}
  </div>
{% endfor %}
</div>