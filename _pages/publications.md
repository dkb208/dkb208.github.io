---
layout: archive
title: "Publication"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
 For the complete list of all the peer-reviewed journal papers and conference proceedings, please refer to:
 <u><a href="{{https://scholar.google.com/citations?user=ZTM7ZUkAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
