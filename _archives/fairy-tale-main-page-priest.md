---
title: The Tale of the Priest and His Workman Balda
layout: priest
category: mainpage
abbr: priest
publication date: 1840
image-url: https://skaz-pushkina.ru/ill/z_15.jpg
original text: https://alexanderpushkin.ru/skazki/2-skazka-o-pope-i-rabotnike-ego-balde.html
plot/summary translation: https://en-academic.com/dic.nsf/enwiki/1549390
literal translation: https://docplayer.com/43180266-A-s-pushkin-skazka-o-pope-i-rabotnike-ego-balde-pushkin-the-tale-of-the-priest-and-of-his-workman-balda-translated-by-oliver-elton.html
tags: 
---
 <h1>Priest</h1>
<ul>
    {% for item in site.pages %}
        {% if item.category == 'priest' %}
    <li>
        <a href = "{{ site.baseurl }}/translation/priest/{{ item.version }}">{{ item.version }}</a><br>
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