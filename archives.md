---
layout: index
title: Archives

---

# The Tale of the Dead Princess and the Seven Knights

    {% for item in site.translation %}
        {% if item.category == 'dead-princess' %}

-   <a href = "{{ item.url | relative_url }}">{{ item.version }}</a><br>
    Tags: {{ item.tags }}<br>
    Language: {{ item.language }}<br>
    Source: {{ item.source-url }}<br> 

        {% endif %} 
    {% endfor %} 


# The Tale of the Fisherman and the Fish

    {% for item in site.translation %}
        {% if item.category == 'fishermen' %}

-   <a href = "{{ item.url | relative_url }}">{{ item.version }}</a><br>
    Tags: {{ item.tags }}<br>
    Language: {{ item.language }}<br>
    Source: {{ item.source-url }}<br> 
    
        {% endif %} 
    {% endfor %} 


# The Tale of Golden Cockerel

    {% for item in site.translation %}
        {% if item.category == 'golden-cockerel' %}

-   <a href = "{{ item.url | relative_url }}">{{ item.version }}</a><br>
    Tags: {{ item.tags }}<br>
    Language: {{ item.language }}<br>
    Source: {{ item.source-url }}<br> 

        {% endif %} 
    {% endfor %} 


# The Tale of the Priest and His Workman Balda

    {% for item in site.translation %}
        {% if item.category == 'priest' %}

-   <a href = "{{ item.url | relative_url }}">{{ item.version }}</a><br>
    Tags: {{ item.tags }}<br>
    Language: {{ item.language }}<br>
    Source: {{ item.source-url }}<br> 

        {% endif %} 
    {% endfor %} 


# The Tale of Tsar Saltan

    {% for item in site.translation %}
        {% if item.category == 'tsar' %}
        
-   <a href = "{{ item.url | relative_url }}">{{ item.version }}</a><br>
    Tags: {{ item.tags }}<br>
    Language: {{ item.language }}<br>
    Source: {{ item.source-url }}<br> 

        {% endif %} 
    {% endfor %} 

