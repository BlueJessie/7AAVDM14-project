---
title: The Tale of Tsar Saltan
layout: tsar
category: mainpage
abbr: tsar
publication date: 1831
image-url: https://skaz-pushkina.ru/ill/z_2.jpg
original-text: https://alexanderpushkin.ru/skazki/30-skazka-o-tsare-saltane-1831.html
translation-in-verse: https://fairytalez.com/the-tale-of-tsar-saltan-of-his-son-the-renowned-and-mighty-bogatyr-prince-gvidon-saltanovich-and-of-the-beautiful-princess-swan/
plot/summary-translation: https://www.fairytales.biz/alexander-pu2shkin/the-tale-of-tsar-saltan.html
Tags:
---
 <h1>Priest</h1>
<ul>
    {% for item in site.pages %}
        {% if item.category == 'tsar' %}
    <li>
        <a href = "{{ site.baseurl }}/translation/tsar/{{ item.version }}">{{ item.version }}</a><br>
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