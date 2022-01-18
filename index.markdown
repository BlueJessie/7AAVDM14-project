---
title: Pushkin Fairytales index
layout: index
---

<div id = "gallery">
  {% for item in site.archives %}
  <div class = "grid_cell">
    <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
    <p class = "caption"><a href = "{{  item.url | relative_url }}">{{ item.title }}</a></p>
  </div>
{% endfor %}
</div>


All illustrations on this page give credit to [Boris Zworykin](https://arthive.com/borissworykin/biography)(1872, Moscow -1942 (45?), Paris)  
For more beautiful illustrations from him, please visit: [metmuseum.com](https://www.metmuseum.org/art/collection/search#!?q=Boris%20Zvorykin&perPage=20&sortBy=Relevance&offset=0&pageSize=0), [printerest.com](https://www.pinterest.co.uk/OakmossLover/zvorykin-boris-russian-illustrator/),[archive.com](https://arthive.com/borissworykin/exhibitions)  <br><br><br>