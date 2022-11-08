---
title: "IT"
layout: archive
permalink: categories/it
author_profile: true
sidebar:
    nav: "docs"
---

{% assign posts = site.categories.it %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}