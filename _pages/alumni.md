---
layout: archive
title: ""
permalink: /alumni/
author_profile: true
---
<div class="grid__wrapper">
  {% for post in site.alumni %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>