---
layout: page
title: The Whole World Blind Characters
category: "The-Whole-World-Blind"
---

{% for char in site.data.characters %}
# {{ char.name }}
  <amp-img width="{{ char.pic.width }}" height="{{ char.pic.height }}" layout="responsive" src="{{ site.url }}/{{ site.baseurl }}/{{ char.pic.url }}"></amp-img>
{{ char.bio }}
{% endfor %}
