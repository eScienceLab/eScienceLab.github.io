---
layout: page
title: Projects
permalink: /projects/
---

## Current projects

{% for project in site.projects %}
{% unless project.expired %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endunless %}
{% endfor %}

## Previous projects

{% for project in site.projects %}
{% if project.expired %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endif %}
{% endfor %}

