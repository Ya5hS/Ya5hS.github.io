---
layout: page
title: Projects
permalink: /projects.html
---

<ul class="project-list">
{% for project in site.projects %}
  <li>
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.summary }}</p>
  </li>
{% endfor %}
</ul>
