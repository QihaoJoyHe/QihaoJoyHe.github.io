---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
---

{% include base_path %}
{% assign sorted = site.code | sort: 'order' %}
{% for post in sorted %}
  {% include archive-single.html type="code" %}
{% endfor %}
