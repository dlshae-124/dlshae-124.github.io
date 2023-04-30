---
title: "OpenStack"
layout: archive
permalink: categories/openstack
author_profile: true
sidebar:
    nav: "docs"
---

{% assign posts = site.categories.openstack %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}