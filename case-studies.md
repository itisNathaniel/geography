---
layout: page
title: Case Studies/Examples
permalink: /casestudyandexample/
---
All case studies and examples by unit: 

**Energy:**

* Case Studies:

{% for post in site.posts | sort: 'title', 'last' %}
    {% if post.categories contains 'energy' and post.categories contains 'casestudy' %}
   <li style="list-style-type: none;"><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
<br>

* Examples:

{% for post in site.posts | sort: 'title', 'last' %}
    {% if post.categories contains 'energy' and post.categories contains 'example' %}
   <li style="list-style-type: none;"><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}

---

**Population:**

* Case Studies:
{% for post in site.posts | sort: 'title', 'last' %}
    {% if post.categories contains 'population' and post.categories contains 'casestudy' %}
   <li style="list-style-type: none;"><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
<br>

* Examples:
{% for post in site.posts | sort: 'title', 'last' %}
    {% if post.categories contains 'population' and post.categories contains 'example' %}
   <li style="list-style-type: none;"><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}