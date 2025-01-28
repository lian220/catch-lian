---
title: "infra"
layout: single
permalink: /infra
author_profile: true
sidebar:
  nav: sidebar-category
---

{% assign posts = site.categories.infra %}
{% for post in posts %}
  <div class="list__item">
    <article class="archive__item">
      <h2 class="archive__item-title">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h2>
      {% if post.excerpt %}
        <p>{{ post.excerpt | strip_html }}</p>
      {% endif %}
    </article>
  </div>
{% endfor %}
