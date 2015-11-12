---
layout: page
title: Projects
permalink: /projects/
---

This is a dynamically generated list of projects.

Project pages and metadata live in the `_projects/` folder

{% for project in site.projects %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endfor %}
