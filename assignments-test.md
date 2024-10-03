---
layout: page
title: Assignments-Test
nav_exclude: true
description: >-
    Course Assignments Test page (hidden).
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

This assignment is the first milestone of your `🤖AI assisted Interactive Ticketing`
project.

{% assign assignment = site.assignments | where: 'task', 'hw2' %}
{% if assignment != 0 %}
 {{ assignment }}
{% endif %}

### HW3: Detecting and Mitigating AI Bias **Due Oct 27 11:59**{: .label .label-red }
**Homeworks**{: .label .label-yellow }

{% assign assignment = site.assignments | where: 'task', 'hw3' %}
{% if assignment != 0 %}
 {{ assignment }}
{% endif %}

## Project: 🤖AI assisted Interactive Ticketing

{% assign info = site.assignments | where: 'type', 'milestones-info' %}
{% if info != 0 %}
 {{ info }}
{% endif %}


### M1: User Research / Contextual Inquiry
Check for [Homework 2](#hw2-user-research--contextual-inquiry-due-oct-20-1159).


### M2: Interaction Modeling
Coming Soon 🤮

### M3: Interface Design
Coming Soon 🤮

### M4: Implementation
Coming Soon 🤮

### M5: Evaluation
Coming Soon 🤮
