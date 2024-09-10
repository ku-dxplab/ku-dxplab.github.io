---
layout: page
title: Lectures
description: Listing of course modules and topics.
---

# Lectures

{% assign lectures = site.modules | where: "type", "lecture" %}
{% assign resources = site.modules | where: "type", "resources" %}

{% for module in lectures %}
  {{ module }}
{% endfor %}

## Resources
{% for module in resources %}
  {{ module }}
{% endfor %}