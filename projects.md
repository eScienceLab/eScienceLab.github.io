---
layout: page
title: Projects
permalink: /projects/
---

## Current projects

{% for project in site.projects %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endfor %}

## Previous projects

{% for project in site.previous-projects %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endfor %}

