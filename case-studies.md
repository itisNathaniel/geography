---
layout: page
title: Case Studies
permalink: /casestudies/
---
All case studies by unit: 

**Rivers Case Studies:**

{% for post in site.posts %}
 {% if post.categories contains "rivers" %}
  {% if post.categories contains "casestudy" %}
<li><a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endif %}
{% endfor %}

<br>

**Population:**

{% for post in site.posts %}
 {% if post.categories contains "population" %}
  {% if post.categories contains "casestudy" %}
<li><a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endif %}
{% endfor %}

<br>

**Coasts:**

{% for post in site.posts %}
 {% if post.categories contains "coasts" %}
  {% if post.categories contains "casestudy" %}
<li><a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endif %}
{% endfor %}

<br>

**Energy:**

{% for post in site.posts %}
 {% if post.categories contains "energy" %}
  {% if post.categories contains "casestudy" %}
<li><a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endif %}
{% endfor %}