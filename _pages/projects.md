---
layout: default
title: Harrison Cai - Portfolio
permalink: /projects/
---
This is the project page for the MAE 2250 Project. Our objective was to design a product to solve the Spotted Lanterfly problem and protect the grape industry. There are 3 milestones listed below. 
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