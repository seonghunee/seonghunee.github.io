---
title: "WEB"
layout: archive
permalink: /vuln-web
author_profile: true
sidebar:
  nav: "sidebar-category"
---

{% assign posts = site.categories.vuln-web %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}