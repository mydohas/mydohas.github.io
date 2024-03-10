---
title: 졸업 프로젝트 스튜디오
layout: archive
permalink: /grad
entries_layout: post
author_profile: true
sidebar:
  title: ""
  nav: grad
---

> 리서치
{% assign posts = site.categories.research %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}


> 과제
{% assign posts = site.categories.assinment %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
