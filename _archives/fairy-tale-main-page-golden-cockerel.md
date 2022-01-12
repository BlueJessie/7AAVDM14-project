---
title: The Tale of Golden Cockerel
layout: golden-cockerel
category: mainpage
abbr: golden-cockerel
publication date: 1834
image-url: https://skaz-pushkina.ru/ill/z_16.jpg
original-text:
translation-in-verse:
plot/summary-translation: 
Tags:
---
 <h1>Priest</h1>
<ul>
    {% for item in site.pages %}
        {% if item.category == 'golden-cockerel' %}
    <li>
        <a href = "{{ site.baseurl }}/translation/golden-cockerel/{{ item.version }}">{{ item.version }}</a><br>
        {{ item.content | truncatewords: 80 }}   
    </li>
        {% endif %} 
    {% endfor %} 
</ul>


<div class = "container">
  {% for item in site.archives %}
  <div id = "content">
    <a href = "{{  item.url | relative_url }}"><img src="{{ item.image-url }}" class="gallery_thumb"></a>
    {{ item.title }}
  </div>
{% endfor %}
</div>