---
title: "테스트"
permalink: /test/
layout: archive
---
{% assign posts = site.categories.테스트 %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}