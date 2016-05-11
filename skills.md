---
layout: page
title: Skills
permalink: /skills/
---
All geography required skills: 

{% assign sorted_threat_posts = site.categories.skills | sort: 'title', 'last' %}
{% for post in sorted_threat_posts %}
   <li style="list-style-type: none;"><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<br>