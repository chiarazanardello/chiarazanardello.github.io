---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Publications
====
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Work in progress
====
Early Modern Academies, Universities, and Growth

This project explores the impact of the upper tail of human capital distribution on European economic growth from 1500 to 1900. I investigate the role of academies, of universities, and of the interaction of these two types of institutions. Using an original database of scholars, I define this interaction as the set of scholars active in both the university and the academy located in the same city. I proxy the economic growth of European cities with their population. I develop the main results of the paper implementing staggered event studies. I also include additional results using recent DID estimators for heterogeneous and inter-temporal treatment effects. In future stages, I will develop an instrumental variable approach to further mitigate endogeneity issues, and I will also exploit data on innovation and patents by country to deepen the analysis.

