---
layout: home
title: Home
---

# Greendata.solutions

**We engineer AI, Data Science and IoT systems for complex, real-world environments.**

From predictive maintenance in aerospace and energy, to machine learning in pharma and agriculture — we design, build and deploy production-grade solutions that deliver measurable impact.

---

## Featured Projects

{% for project in site.data.projects %}
### {{ project.name }}

{{ project.description }}

{% if project.highlights %}
{% for highlight in project.highlights %}- {{ highlight }}
{% endfor %}{% endif %}
{% endfor %}

---

## Trusted By

{% include clients.html %}
