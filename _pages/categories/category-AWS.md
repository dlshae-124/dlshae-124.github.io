---
title: "AWS"
layout: archive
permalink: categories/aws
author_profile: true
sidebar:
    nav: "docs"
---

{% assign posts = site.categories.aws %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}