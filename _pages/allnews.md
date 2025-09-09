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
    <strong>{{ article.date }}</strong> — {{ article.headline }}
  </li>
{% endfor %}
</ul>
