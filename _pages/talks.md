---
layout: page
permalink: /talks/
title: talks
nav: true
nav_order: 4
---

<div class="post">

  <article>
    <div class="cv">
      {% for entry in site.data.talks %}
        <div class="card mt-3 p-3">
          <h3 class="card-title font-weight-medium">{{ entry.title }}</h3>
          <div>
            {% if entry.type == "time_table" %}
              {% include cv/time_table.html %}
            {% else %}
              {{ entry.contents }}
            {% endif %}
          </div>
        </div>
      {% endfor %}
    </div>
  </article>
</div>