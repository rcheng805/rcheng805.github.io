---
layout: archive
title: ""
permalink: /activities/
author_profile: true
---

Teaching Assistant
---

<u> CDS 110 (Introduction to Feedback Systems) </u>

The CDS 110 course provides an introduction to analysis and design of feedback control systems, including classical control theory in the time and frequency domain. As a teaching assistant, I held precepts, answered students' questions, and graded assignments.

<u> ME/CS/EE 134 (Autonomy) </u>

The ME/CS/EE 134 course covers the basics of autonomy at the intersection of computer vision, machine learning, and robotics. I designed one the hardware labs, which dealt with mapping, localization, and navigation. I ran students through how to program a turtlebot to autonomously navigate around obstacles from a start point to end point. In addition, I wrote up a couple assignments to get students familiar path planning and ROS (robot operating system), and I also guest lectured twice for the course, providing an overview and tutorial on ROS. A github repository with some of the course materials can be found [here](https://github.com/rcheng805/ME134_robotics).

Tutoring
---

<u> RISE program </u>

The Rise Program is an after-school tutoring program hosted at Caltech, which serves public schools students in the Pasadena area who are struggling with math and science. I volunteered as a tutor for this program for one year from 2017-2018, working with middle-school students on math and science.

McGraw Study Hall

McGraw Study Hall is a program at Princeton University for undergraduates to receive help in their courses from other students who have previously mastered the material. I worked as tutor for this program, teaching multivariable calculus, linear algebra, and general physics to other students.

Petey Greene Prisoner Assistance Program

The Petey Greene Prisoner Assistance program supplements education in correctional institutions by providing free academic tutoring to incarcerated people and helping them to obtain their GEDs. I volunteered as a tutor at the Garden State Youth Correctional Facility for two years, mainly teaching mathematics.

Undergraduate Advising
---

As a PhD student at Caltech, I have advised one senior thesis project and one summer research project in Joel Burdick's lab group. The summer research project undertaken by Aakash Bajpai was titled "Design and Implementation of a SCI Rehabilitation Home Therapy Robot", and dealt with the design and prototyping of a perturbation platform that could be used to train and test motor function in patients with spinal cord injury. The senior thesis project undertaken by Sandra Liu was titled "State Estimation and Control for a Perturbing Platform for Robotic Rehabilitation", which dealt with adding sensors and implementing a controller on the same perturbation platform.





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
