{% for project in site.data.projects %}
**[{{ project.title }}]({{ project.url }})** — {{ project.description }}

{% endfor %}