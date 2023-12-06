---
layout: page
title: members
permalink: /members/
description: 🥷 <i>Homo sapiens</i> studying <i>Nature</i>
nav: true
nav_order: 2
display_categories: [PI, Postdoc, Graduate students]
---

<!-- pages/members.md -->
<div class="projects">
<!-- Display categorized projects -->
{%- for category in page.display_categories %}
<h2 class="category">{{ category }}</h2>
{%- assign categorized_members = site.members | where: "category", category -%}
{%- assign sorted_members = categorized_members | sort: "lastname" %}
<!-- Generate cards for each member -->
<div class="container">
  <div class="row row-cols-1">
  {%- for member in sorted_members -%}
    <p>
    {% include members.html %}
    </p>
  {%- endfor %}
  </div>
</div>
{% endfor %}
</div>
