---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}
{% assign sorted = site.research | sort: 'order' %}
{% for post in sorted %}
  {% include archive-single.html type="research" %}
{% endfor %}
