---
title: "Azure"
layout: archive
permalink: categories/azure
author_profile: true
sidebar:
    nav: "docs"
---

{% assign posts = site.categories.azure %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
