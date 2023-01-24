---
layout: archive
title: "First-Author Publications"
permalink: /publications/
author_profile: true
---

You can find a list on <u><a href="https://scholar.google.com/citations?user=ZxKRzugAAAAJ&hl=en">Google Scholar</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
