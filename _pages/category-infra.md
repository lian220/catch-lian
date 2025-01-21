---
title: "infra"
layout: single
permalink: /infra
author_profile: true
sidebar:
  nav: sidebar-category
---
{% assign posts = site.categories.infra %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}