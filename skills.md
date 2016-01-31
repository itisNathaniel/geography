---
layout: page
title: Skills
permalink: /skills/
---
All geography required skills: 

{% for post in site.posts %}
 {% if post.categories contains "skills" %}
<li><a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}

<br>