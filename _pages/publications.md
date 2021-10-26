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

## [On Competitive Permutations for Set Cover by Intervals](http://jackycheng1999.github.io/files/interval_cover.pdf)

Oct 26, by Jiaqi Cheng and Sariel Har-Peled