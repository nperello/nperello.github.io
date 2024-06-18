---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
*Equal contribution, ^Equal advising

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h2>In Preperation</h2>
{% for post in site.publications reversed %}
  {% if post.collection == 'inprogress' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Archival</h2>
{% for post in site.publications reversed %}
  {% if post.collection == 'publications' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Non-Archival</h2>
{% for post in site.publications reversed %}
  {% if post.collection == 'nonarchival' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

