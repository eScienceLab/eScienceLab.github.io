---
layout: page
title: Previous Projects
permalink: /previous-projects/
---

fish


{% for project in site.previous-projects %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endfor %}
