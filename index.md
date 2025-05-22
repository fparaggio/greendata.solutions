---
layout: default
title: Greendata Projects
---

# Welcome to Greendata.solutions

We design and deploy AI and IoT systems for complex, real-world environments.  
Below is a selection of our recent work.

{% for project in site.data.projects %}
## ![{{ project.name }}](/assets/img/{{ project.image }}) {{ project.name }}
{{ project.description }}
{% endfor %}