---
layout: page
permalink: /skills/
title: skills
description: A summary of technical and professional skills. Edit the "Skills" section in _data/cv.yml to update this list.
nav: true
nav_order: 4
---

<div class="post">
  <article>
    <div class="cv">
      <div class="card mt-3 p-3">
        {% assign entries = site.data.cv.cv.sections.Skills %}
        {% if entries %}
          {% include cv/skills.liquid %}
        {% else %}
          <p class="font-weight-light">
            No skills added yet. Add a "Skills" section to <code>_data/cv.yml</code> to populate this page.
          </p>
        {% endif %}
      </div>
    </div>
  </article>
</div>
