---
layout: page
title: Sting Characters
---

{% assign collection = page.collection %}
{% assign data = site.data[collection] %}
{% include character_page.html characters=data.characters %}
