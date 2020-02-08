---
layout: page
title: The Whole World Blind Characters
---
{% assign collection = page.collection %}
{% assign data = site.data[collection] %}
[CollectionMainPage]:{{site.url}}/{{site.baseurl}}/{{collection}}

#### {{ data.description }}
[«{{data.title}} Main Page][CollectionMainPage]

{% include character_page.html characters=data.characters %}
