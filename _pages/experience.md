---
layout: page
permalink: /experience/
title: experience
description: Work history and roles. Edit the "Experience" section in _data/cv.yml to update this list.
nav: true
nav_order: 5
---

<div class="post">
  <article>
    <div class="cv">
      {% assign entries = site.data.cv.cv.sections.Experience %}
      {% if entries %}
        {% include cv/experience.liquid %}
      {% else %}
        <p class="font-weight-light">
          No experience added yet. Add an "Experience" section to <code>_data/cv.yml</code> to populate this page.
        </p>
      {% endif %}
    </div>
  </article>
</div>
