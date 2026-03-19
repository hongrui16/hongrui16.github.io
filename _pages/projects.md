---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
---

{% for project in site.data.projects %}
**[{{ project.title }}]({{ project.url }})** — {{ project.description }}

{% endfor %}