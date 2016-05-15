---
layout: page
title: Examples
permalink: /examples/
---
All examples by unit: 

**Energy Examples:**


{% assign sorted_threat_posts = site.categories.energy | sort: 'title', 'last' %}
{% assign sorted_threat_posts = site.categories.example | sort: 'title', 'last' %}

{% for post in sorted_threat_posts %}
   <li style="list-style-type: none;"><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}