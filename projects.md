---
layout: page
title: Projects, programmes and activities with eScience Lab
permalink: /projects/
---

{% include logo_grid.html %}

## Current projects and programmes

{% for project in site.projects %}
{% unless project.expired %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endunless %}
{% endfor %}

## Current activities

{% for activity in site.activities %}
{% unless activity.expired %}
* [{{ activity.title }}]({{ activity.url }}) - {{ activity.description }}
{% endunless %}
{% endfor %}

## Previous projects and programmes

{% assign sorted_projects = site.projects | sort: 'title' %}
{% for project in sorted_projects %}
{% if project.expired %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endif %}
{% endfor %}

## Previous activities

{% assign sorted_activities = site.activities | sort: 'start-date' %}
{% for activity in sorted_activities reversed %}
{% if activity.expired %}
* [{{ activity.title }}]({{ activity.url }}) - {{ activity.description }}
{% endif %}
{% endfor %}

