---
layout: post
title: "Observation: Giant Swallowtail Caterpillar Behavior"
date: 2025-08-17
categories: [wildlife]   # use one or more from: experiments, plants, wildlife, pond
tags: [insects, caterpillar, thermoregulation]
---
---
layout: page
title: Journal
permalink: /journal/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%B %d, %Y" }}</small>
      {% if post.categories.size > 0 %}
        <em> [{{ post.categories | join: ", " }}]</em>
      {% endif %}
    </li>
  {% endfor %}
</ul>
