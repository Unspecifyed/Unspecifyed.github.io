
---
layout: default
title: "Projects"
description: "Discover the projects I've worked on."
---

# Projects

Here are some of my featured projects:

<div class="projects-grid">
  {% for project in site.data.projects %}
  <div class="project-card">
    <h3><a href="{{ project.url }}" target="_blank">{{ project.name }}</a></h3>
    <p>{{ project.description }}</p>
  </div>
  {% endfor %}
</div>

<div class="nav-links">
  {% for item in site.data.navigation.main %}
  <a href="{{ item.url }}">{{ item.title }}</a>
  {% endfor %}
</div>
