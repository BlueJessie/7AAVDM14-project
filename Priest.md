---
title: The Tale of Priest
layout: page
---
{% for image in site.data.img %}

<p>{{ image.url1 }}</p>

{% endfor %}

{% for translation in site.archives %}

<p>{{ translation.title }}</p>

{% endfor %}