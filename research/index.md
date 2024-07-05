---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

{% include section.html %}

## Recent


{% assign citations = site.data.citations %}

{% assign citations_with_keys = citations | sort: 'date' | reverse %}

{% for citation in citations_with_keys limit: 3 %}
  {% include citation.html lookup=citation.id style="rich" %}
{% endfor %}


{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}