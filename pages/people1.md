---
layout: page
title: People
gallery: true
collection: people-uniq-rows
---

People set

Each person can have only one entry in the CSV

{% for item in site[page.collection] %}
* [{{ item.label }}]({{ item.url | relative_url }}) ({{ item.pid }})
{% endfor %}
