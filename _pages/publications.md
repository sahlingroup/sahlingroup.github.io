---
layout: archive
title: "Selected publications"
permalink: /publications/
author_profile: true
---

A selected list of publications is presented below. You can find a complete list of my papers on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

<!-- {% if author.googlescholar %}
  You can find a complete list of my papers on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
