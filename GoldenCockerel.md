---
title: The Tale of Golden Cockerel
layout: index
---

{% for translation in site.archives %}

   {{ translation.version | group_by:"page.title" }} of {{ translation.title }}

{% endfor %}