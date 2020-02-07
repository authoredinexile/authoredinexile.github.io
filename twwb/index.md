---
layout: post
title: The Whole World Blind
categories: "The-Whole-World-Blind"
cover: "assets/images/twwb/twwb_map.jpeg"
paginator:
  enable: true
---

[CharactersLink]:{{ page.url }}/characters

# The Whole World of The-Whole-World-Blind

Everyone is blind

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ac augue libero. Fusce ac tempor dolor. Ut est dui, gravida a consequat aliquet, fermentum sodales risus. Suspendisse eu arcu id mi ornare facilisis non id nisl. Maecenas nec congue arcu, non semper neque. Proin mollis nisl diam, eu ultrices diam facilisis et. Integer fringilla lorem quis semper venenatis.

Etiam sapien dolor, mattis vel feugiat nec, egestas eget risus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean aliquam massa a est porta vehicula. Cras eu gravida massa. Integer non sem ac mi ultrices posuere a pretium tortor. Mauris vitae varius sem. Praesent faucibus nec felis et dictum. Vestibulum lorem velit, laoreet nec vestibulum in, varius nec enim.

## Characters
These are the [Characters][CharactersLink].

## POSTS

<ul>
{% for post in paginator.posts %}
  BINGBONG
  {% for post in category %}
    <li>{{ post.title }} - <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {%endfor%}
{% endfor %}
</ul>

