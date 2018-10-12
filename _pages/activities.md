---
layout: archive
title: ""
permalink: /activities/
author_profile: true
---

Teaching Assistant
===

CDS 110 (Introduction to Feedback Systems)
---

ME/CS/EE 134 (Autonomy)
---


Tutoring
===

RISE Program
---

McGraw Study Hall
---

Petey Greene Prisoner Assistance Program
---

Advising
===

Senior thesis projects



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
