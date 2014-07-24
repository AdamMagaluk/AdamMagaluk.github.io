---
title: Trips
layout: default
---

<div>
  <ul>
    {% for doc in site.categories["trips"] %}
      <li>
        <a href="{{ doc.url }}">{{ doc.title }}</a>
      </li>
    {% endfor %}
  </ul>
</div>
