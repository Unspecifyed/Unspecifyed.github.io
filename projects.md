---
layout: default
title: "Projects"
description: "Discover the projects I’ve worked on."
---

<style>
  /* Styling for projects page */
  body {
    background-color: #1a1a1a; /* Dark black background */
    color: #e63946; /* Vibrant red for text */
    font-family: Arial, sans-serif;
  }

  .projects-header {
    text-align: center;
    margin-top: 50px;
    margin-bottom: 30px;
  }

  .projects-header h1 {
    font-size: 2.5em;
    color: #e63946; /* Red for the title */
  }

  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin: 30px auto;
    max-width: 1000px;
  }

  .project-card {
    background-color: #2e2e2e; /* Slightly lighter black */
    border: 1px solid #e63946; /* Red border for cards */
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
  }

  .project-card h3 {
    color: #e63946; /* Red for project titles */
    margin-bottom: 10px;
  }

  .project-card p {
    color: #f5f5f5; /* White for descriptions */
  }

  .project-card a {
    text-decoration: none;
    color: #e63946;
    font-weight: bold;
  }

  .project-card a:hover {
    text-decoration: underline;
  }
</style>

<div class="projects-header">
  <h1>Projects</h1>
  <p>Here are some of my featured projects:</p>
</div>

<div class="projects-grid">
  {% for project in site.data.projects %}
  <div class="project-card">
    <h3><a href="{{ project.url }}" target="_blank">{{ project.name }}</a></h3>
    <p>{{ project.description }}</p>
  </div>
  {% endfor %}
</div>
