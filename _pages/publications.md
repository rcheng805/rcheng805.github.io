
{% comment %} 

---
layout: archive
title: "Publications"
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

{% endcomment %}

Richard Cheng, Yanan Sui, Dimitry Sayenko, Joel W. Burdick. On Muscle Activation for Improving Robotic Rehabilitation after Spinal Cord Injury. (2010). IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2018. 

Richard Cheng, Joel W. Burdick. "Extraction of Muscle Synergies in Spinal Cord Injured Patients. IEEE Engineering in Medicine and Biology Conference, 2018. http://rcheng805.github.io/files/embc2018.pdf
