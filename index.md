---
layout: default
title: "Welcome to My Portfolio"
description: "Explore my projects, skills, and professional journey."
---

<style>
  /* Page-specific styling */
  h1 {
    color: #4fc3f7;
  }
</style>

# Welcome to My Portfolio

Explore my projects, skills, and professional journey through this site.

<div class="nav-links">
  {% for item in site.data.navigation.main %}
  <a href="{{ item.url }}">{{ item.title }}</a>
  {% endfor %}
</div>
