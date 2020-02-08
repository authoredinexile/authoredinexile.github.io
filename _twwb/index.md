---
layout: post
title: The Whole World Blind
cover: "assets/images/twwb/twwb_map.jpeg"
permalink: /:collection/
---

{% assign collection = page.collection %}
{% assign data = site.data[collection] %}
[CharactersLink]:{{ page.url }}/characters

# The Whole World of The-Whole-World-Blind

{{ data.long_description }}

## Characters
These are the [Characters][CharactersLink].

## POSTS

<ol>
{% for post in site[collection] %}
  BINGBONG
  <li>{{ post.title }} - <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ol>

