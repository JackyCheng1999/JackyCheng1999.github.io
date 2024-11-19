---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## [On Competitive Permutations for Set Cover by Intervals](https://arxiv.org/pdf/2110.14528)

Oct 26 2021, Jiaqi Cheng, Sariel Har-Peled