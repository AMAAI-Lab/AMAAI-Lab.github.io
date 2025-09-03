---
title: "News"
layout: textlay
excerpt: "Allan Lab at Leiden University."
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
