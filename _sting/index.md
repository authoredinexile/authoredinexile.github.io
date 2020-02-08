---
layout: post
title: Sting
cover: "assets/images/sting/banner.png"
permalink: /:collection/
---

[CharactersLink]:{{ page.url }}/characters

# The World of Sting

{{ site.data.twwb.long_description }}

## Characters
These are the [Characters][CharactersLink].

## POSTS

<ol>
{% for post in site.twwb %}
  BINGBONG
  <li>{{ post.title }} - <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ol>

