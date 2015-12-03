---
layout: page
title: Projects
permalink: /projects/
---

{% for project in site.projects %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endfor %}
