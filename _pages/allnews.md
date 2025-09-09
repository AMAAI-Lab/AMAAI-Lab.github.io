---
title: "News"
layout: textlay
excerpt: "AMAAI Lab at Singapore University of Technology and Design."
sitemap: false
permalink: /allnews.html
---

# News

<ul>
{% for article in site.data.news %}
  <li>
    <strong>{{ article.date }}</strong> — 
    {% if article.link %}
      <a href="{{ article.link }}">{{ article.headline }}</a>
    {% else %}
      {{ article.headline }}
    {% endif %}
  </li>
{% endfor %}
</ul>
