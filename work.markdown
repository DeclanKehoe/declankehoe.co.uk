---
layout: page
title: Work
permalink: /work/
---

Here's some things I've done! Click the links for more information, videos, context, all kinds of good stuff 😬.

{% for work in site.work %}
  <h3>
    <a href="{{ work.url }}">{{ work.title }}</a>
  </h3>
  <p>{{ work.description }}<p>

{% endfor %}