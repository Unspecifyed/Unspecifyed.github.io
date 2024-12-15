---
layout: default
title: "About Me"
description: "Learn more about my background and skills."
---

# About Me

Hello! I'm passionate about technology, programming, and creating innovative solutions. I specialize in reverse engineering, software development, and mobile app design.

## Skills
- **Programming Languages**: C++, Python, Java
- **Tools**: Octave, Radare2, Bless Hex Editor
- **Platforms**: Linux, Android

## Interests
When I'm not coding, I enjoy exploring new technologies and contributing to open-source projects.

<div class="nav-links">
  {% for item in site.data.navigation.main %}
  <a href="{{ item.url }}">{{ item.title }}</a>
  {% endfor %}
</div>
