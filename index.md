---
layout: default
title: "Welcome to My Portfolio"
description: "Explore my projects, skills, and professional journey."
---

<style>
  /* Styling for a modern look */
  .hero-section {
    text-align: center;
    margin-top: 50px;
  }

  .hero-title {
    font-size: 2.5em;
    color: #4fc3f7; /* Highlighted light blue color */
    margin-bottom: 20px;
  }

  .hero-description {
    font-size: 1.2em;
    color: #f5f5f5;
    margin-bottom: 40px;
  }

  .cta-buttons {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin-top: 20px;
  }

  .cta-buttons a {
    text-decoration: none;
    color: white;
    background-color: #4fc3f7;
    padding: 10px 20px;
    border-radius: 5px;
    font-weight: bold;
  }

  .cta-buttons a:hover {
    background-color: #0288d1; /* Darker blue */
  }
</style>

<div class="hero-section">
  <h1 class="hero-title">Welcome to My Portfolio</h1>
  <p class="hero-description">
    Explore my projects, skills, and professional journey through this site. I specialize in creating innovative solutions and thrive on tackling complex challenges in software development.
  </p>
  <div class="cta-buttons">
    <a href="{{ '/projects/' | relative_url }}">View My Projects</a>
    <a href="{{ '/resume/' | relative_url }}">See My Resume</a>
  </div>
</div>
