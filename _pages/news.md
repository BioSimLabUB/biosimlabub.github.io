---
layout: page
title: news
description: let's keep the good news coming! 🥳
permalink: /news/
nav: true
nav_order: 4
pagination:
  enabled: false
  collection: posts
  per_page: 10
  sort_field: date
  sort_reverse: true
  trail:
    before: 1 # The number of links before the current page
    after: 3  # The number of links after the current page
---

{% include news.html %}
