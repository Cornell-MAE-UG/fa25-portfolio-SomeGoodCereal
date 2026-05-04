---
layout: default
title: Harrison Cai - Portfolio
permalink: /projects/
---

<h2 style="text-align: center;">MAE 2250 Final Project</h2>

<h2 style="text-align:center;">Project Overview</h2>
<p class="projects-intro">
  This is the project page for the MAE 2250 Final Project. Our objective was to design a product to solve the Spotted Lanternfly problem and protect the grape industry. There are 3 milestones listed below.
</p>

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>