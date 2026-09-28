---
layout: page
title: projects
permalink: /projects/
description: Research projects and coursework.
count: projects
nav: true
nav_order: 3
---

{% comment %} Projects are ordered by the reversed `date` field in each file under _projects/. {% endcomment %}
{% assign sorted_projects = site.projects | sort: "date" | reverse %}

<div class="projects">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>
