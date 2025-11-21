---
layout: page
title: Projects
permalink: /projects/
---

Here are a few projects I’ve built across healthcare ML, graph ML, and LLM interpretability.

{% for project in site.projects %}
- **[{{ project.title }}]({{ project.url }})**  
  {{ project.description }}
{% endfor %}
