---
layout: page
title: Notes
---

## Go

  <ul>
    {% for note in site.go %}
      <li><a href="{{ note.url | relative_url }}">{{ note.title }}</a></li>
    {% endfor %}
  </ul>
