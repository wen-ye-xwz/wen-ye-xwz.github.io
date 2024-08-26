---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

You can also find my articles on <u><a href="https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=_HxPFowAAAAJ">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
