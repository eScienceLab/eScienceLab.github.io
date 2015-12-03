---
layout: page
title: Previous Projects
permalink: /previous_projects/
---



{% for project in site.previous_projects %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endfor %}
