---
layout: page
title: Assignments-Test
nav_exclude: true
description: >-
    Course Assignments Test page (hidden).
---

{% assign assignment = site.assignments | where: 'status', 'fixing' %}
{% if assignment != 0 %}
 {{ assignment }}
{% endif %}