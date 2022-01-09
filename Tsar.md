---
title: The Tale of Tsar Saltan
image-url: https://www.prlib.ru/item/315900,https://www.prlib.ru/item/315768
publication date: 1831
layout: post
tags: Tsar
---

# The Tale of Tsar Saltan, 1831

{% for image in site.archives.img %}

<p>{{ image.title | titie:"TsarSaltan" }}</p>

{% endfor %}

{% for translation in site.archives %}

<p>{{ translation.version | title:"The Tale of Tsar Saltan" }}</p>
<p>{{ translation.content | title:"The Tale of Tsar Saltan" }}</p>

{% endfor %}

