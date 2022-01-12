---
layout: index
---
# Dead Princess
{% for dead-princess in site.archive.deadprincess %}
    {{ dead-princess.version }}
    {{ dead-princess.content }}
{% endfor %}
