---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Current Projects

### integrating the Processes of Green Infrastructure in a Large-Scale Land Surface Model

![Test Image](/images/conceptual_model_v4_simple_title-01.png)


{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
