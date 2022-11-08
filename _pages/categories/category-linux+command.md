---
title: "Linux Command"
layout: archive
permalink: categories/linuxcommand
author_profile: true
sidebar:
    nav: "docs"
---

{% assign posts = site.categories.linuxcommand %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}