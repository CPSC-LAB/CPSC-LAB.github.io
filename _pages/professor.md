---
layout: archive
title: "Post Archive with Feature Rows"
permalink: /professor_intro/
author_profile: true
feature_row:
  - image_path: assets/images/professor.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "2016 ~ currently: Associate Professor, Department of Electronic Engineering, Kyungpook National University (KNU)<br>
    2009 ~ 2015: Assistant Professor, Department of Electronic Engineering, Daegu University<br>
    2006 ~ 2008: Senior Researcher, Korea Telecom(KT)<br>
    2001 ~ 2006: Ph.D. Department of Electronic Engineering, Pohang University of Science and Technology (POSTECH)<br>
    1999 ~ 2001: M.S. POSTECH<br>1992 ~ 1999: B.S. EE. KNU"
---
{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="center" %}
