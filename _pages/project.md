---
title: Project in others
layout: archive
permalink: /project/
entries_layout: post
author_profile: true
sidebar:
  title: ""
  nav: project
---

{% assign posts = site.categories.project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}