---
title: Glossary
nav_order: 9
nav_exclude: true
---

# Glossary of Terms

Below are some important concepts, software, standards, and other things you might encounter in this guide. 

{% assign terms = site.glossary %}
{% for t in terms %}
--------

## {{ t.title }}

{% if t.link %}<{{ t.link }}>{% endif %}

{{ t.content }}

{% endfor %}
