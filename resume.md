---
layout: default
title: "Resume"
description: "View my professional resume and experiences."
---

# Resume

## Professional Experience

### Software Engineer Intern
**[Company Name]**, [Location]  
*MM/YYYY - MM/YYYY*  
- Developed efficient code for [specific task or project].
- Improved application performance by [specific achievement].

### Research Assistant
**[Institution Name]**, [Location]  
*MM/YYYY - MM/YYYY*  
- Conducted research on [specific topic or project].

## Education
**Bachelor of Science in Computer Science**  
[Your University], [Graduation Year]

## Certifications
- [Certification Name], [Year]

<div class="nav-links">
  {% for item in site.data.navigation.main %}
  <a href="{{ item.url }}">{{ item.title }}</a>
  {% endfor %}
</div>
