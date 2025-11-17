---
layout: page
permalink: /publications/
title: publications
description: publications grouped by review status
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

## Accepted / Published
{% bibliography --query @*[note ^= Accepted] --group_by none --sort_by none %}
{% bibliography --query @*[note ^= Published] --group_by none --sort_by none %}

## Under Review
{% bibliography --query @*[note ^= Under] --group_by none --sort_by none %}
{% bibliography --query @*[note ^= Submitted] --group_by none --sort_by none %}

## In Preparation
{% bibliography --query @*[note ^= In preparation] --group_by none --sort_by none %}
