---
layout: page
title: Projects
permalink: /projects/
---

## Current projects and programmes

{% include logo_projects.html %}

{% for project in site.projects %}
{% unless project.expired %}
* [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endunless %}
{% endfor %}

## Current activities and initiatives

{% include logo_activities.html %}

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

## Previous activities and initiatives

{% assign sorted_activities = site.activities | sort: 'start-date' %}
{% for activity in sorted_activities reversed %}
{% if activity.expired %}
* [{{ activity.title }}]({{ activity.url }}) - {{ activity.description }}
{% endif %}
{% endfor %}

