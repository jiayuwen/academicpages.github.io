---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
author.googlescholar: true
---


======

Lin CJ, Hu F, Dubruille R, Vedanayagam J, Wen J., Smibert P, Loppin B, Lai EC. The hpRNA/RNAi Pathway is essential to resolve intragenomic conflict in the Drosophila male germline. Developmental Cell, (2018). 46(3):316-326.e5. IF 9.6.
Full Text HTML | PDF



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=Hb1ojSwAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
