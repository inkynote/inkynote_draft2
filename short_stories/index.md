---
layout: default
title: "Short Stories"
---

# Short Stories Collection

Welcome to my Short Stories collection. Here, you can delve into a world of imagination and creativity. Each story is crafted with care, offering unique narratives that span various genres and themes. Whether you're in the mood for something thrilling, thought-provoking, or heartwarming, you'll find a story that resonates.

Browse through the stories below and enjoy the journey into the worlds I've created.

<ul>
  {% for post in site.categories.short_stories %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
    </li>
  {% endfor %}
</ul>

Explore more of my writing by visiting my [PhD Poetry](/phd_poetry/) and [Professional Blog](/blog/).
