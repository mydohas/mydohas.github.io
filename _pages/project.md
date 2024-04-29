---
title: Project
layout: archive
permalink: /project/
entries_layout: grid
author_profile: true
sidebar:
  title: ""
  nav: project
---
> School
{% assign posts = site.categories.project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
