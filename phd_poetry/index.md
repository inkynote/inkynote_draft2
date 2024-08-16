---
layout: default
title: "PhD Poetry"
---

# PhD Poetry Collection

Welcome to my PhD Poetry collection. Here, you'll find a curated selection of poems that reflect my journey through academia. Each piece is a reflection of the challenges, insights, and emotions encountered during my PhD studies.

Feel free to explore and immerse yourself in the poetic expressions of scholarly life.

<ul>
  {% for post in site.categories.phd_poetry %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
    </li>
  {% endfor %}
</ul>

If you're interested in more of my work, don't forget to check out my [Short Stories](/short_stories/) and [Professional Blog](/blog/).
