---
layout: page
title: Assignments
description: >-
    Course Assignments.
---

# Assignments
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
{% assign info = site.assignments | where: 'type', 'info' %}
{% if info != 0 %}
 {{ info }}
{% endif %}

## Homeworks
### HW1: Exploring HCI Principles **Due Sep 25 11:59**{: .label .label-red }
{% assign assignment = site.assignments | where: 'task', 'hw1' %}
{% if assignment != 0 %}
 {{ assignment }}
{% endif %}

### HW2: Event-Driven Framework/GUI Simulation 
Coming Soon 🤮

## Project
**🤖AI assisted Interactive Ticketing**

### M1: User Research
Coming Soon 🤮

### M2: Interaction Modeling
Coming Soon 🤮

### M3: Interface Design
Coming Soon 🤮

### M4: Implementation
Coming Soon 🤮

### M5: Evaluation
Coming Soon 🤮
