---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Department of Computing, the Hong Kong Polytechnic University, 2026 (expected)
* M.S. in College of Computer Science, Sichuan University, 2022
* B.S. in College of Computer Science, Sichuan University, 2019

Work experience
======
* June 2020 - March 2021: Research Intern
  * Pengcheng Laboratory
  * Duties include: ECG-related data collection and research

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
