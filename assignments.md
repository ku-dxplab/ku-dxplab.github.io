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
### HW1: Exploring HCI Principles 
**Homeworks**{: .label .label-yellow } **Due Sep 25 11:59**{: .label .label-green }

{% assign assignment = site.assignments | where: 'task', 'hw1' %}
{% if assignment != 0 %}
 {{ assignment }}
{% endif %}

### HW2: User Research / Contextual Inquiry **Due Oct 20 11:59**{: .label .label-red }
**Project Milestones**{: .label .label-yellow }

{% assign assignment = site.assignments | where: 'task', 'hw2' %}
{% if assignment != 0 %}
 {{ assignment }}
{% endif %}

### HW3: Basic HTML/JavaScript Practice **Due Nov 10 11:59**{: .label .label-red }
**Homeworks**{: .label .label-yellow } **Project Milestones**{: .label .label-yellow }

{% assign assignment = site.assignments | where: 'task', 'hw3' %}
{% if assignment != 0 %}
 {{ assignment }}
{% endif %}

### HW4: Detecting and Mitigating AI Bias 
**Homeworks**{: .label .label-yellow }

{% assign assignment = site.assignments | where: 'task', 'hw4' %}
{% if assignment != 0 %}
 {{ assignment }}
{% endif %}


## Project
**🤖AI assisted Interactive Ticketing**

<!-- {% assign info = site.assignments | where: 'type', 'milestones-info' %}
{% if info != 0 %}
 {{ info }}
{% endif %} -->


### M1: User Research / Contextual Inquiry
Check for [Homework 2](#hw2-user-research--contextual-inquiry-due-oct-20-1159).


### M2: Interaction Modeling / Interface Design
Coming Soon 🤮


### M3: Implementation
Coming Soon 🤮


### M4: Evaluation
Coming Soon 🤮
