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
{% bibliography --query @*[note^="Accepted"] %}

## Under Review
{% bibliography --query @*[note^="Under"] %}
{% bibliography --query @*[note^="Submitted"] %}

## In Preparation
{% bibliography --query @*[note^="In preparation"] %}
