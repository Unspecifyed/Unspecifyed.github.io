---
layout: default
title: "Welcome to My Portfolio"
description: "Explore my projects, skills, and professional journey."
---

<style>
  /* Overall page styling */
  body {
    background-color: #1a1a1a;
    color: #e63946;
    font-family: Arial, sans-serif;
  }

  /* Hero section styling */
  .hero-section {
    text-align: center;
    margin-top: 50px;
  }

  .hero-title {
    font-size: 2.5em;
    color: #e63946;
    margin-bottom: 20px;
  }

  .hero-description {
    font-size: 1.2em;
    color: #ffffff;
    margin-bottom: 40px;
  }

  /* Call-to-action buttons */
  .cta-buttons {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin-top: 20px;
    flex-wrap: wrap;
  }

  .cta-buttons a {
    text-decoration: none;
    color: #1a1a1a;
    background-color: #e63946;
    padding: 10px 20px;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s, color 0.3s;
  }

  .cta-buttons a:hover {
    background-color: #ffffff;
    color: #e63946;
  }
</style>

<div class="hero-section">
  <h1 class="hero-title">Welcome to My Portfolio</h1>
  <p class="hero-description">
    Explore my projects, skills, and professional journey through this site. I specialize in creating innovative solutions and thrive on tackling complex challenges in software development.
  </p>
  <div class="cta-buttons">
    <a href="{{ '/projects/' | relative_url }}">View My Projects</a>
    <a href="/cv.pdf" target="_blank">See My Resume</a>
    <a href="{{ '/store/' | relative_url }}">Visit My Store</a>
  </div>
</div>
