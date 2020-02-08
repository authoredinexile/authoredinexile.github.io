---
layout: page
title: Sting
cover: "assets/images/sting/banner.png"
permalink: /:collection/
---

{% assign collection = page.collection %}
{% assign data = site.data[collection] %}
[CharactersLink]:{{ page.url }}/characters

# The World of Sting

{{ data.twwb.long_description }}

## Characters
These are the [Characters][CharactersLink].

## POSTS

<ol>
{% for post in site[collection] %}
  <li>{{post.layout}}</li>
  {%if post.layout!="post" %}{%continue%}{%endif%}
  BINGBONG
  <li>{{ post.title }} - <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ol>

