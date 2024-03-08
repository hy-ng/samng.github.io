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
* M.S. in Informatics, Pennsylvania State University, 2024 (expected)
* M.Des. in Interaction Design, National Taipei University of Technology (NTUT), 2024 (expected)
* B.B.A. in Professional Accounting and Information Systems (minor in Social Science and Design), The Hong Kong University of Science & Technology (HKUST), 2016

Work experience
======
* Fall 2023 - Present: Research Assistant
  * Pennsylvania State University
  * Duties included: Conducting extensive research in the field of Artificial Intelligence (AI) assisting technology
  * Supervisor: Prof. Ting-Hao (Kenneth) Huang

* Fall 2021 - Summer 2023: Research Assistant
  * National Taipei University of Technology (NTUT)
  * Duties included:
    * Conducted diverse research in XR (Extended Reality) domain to contribute to research and development initiatives
    * Conducted various live demo sessions with faculties and guests around the world to explain our research findings
  * Supervisor: Prof. Ping-Husan Han


Skills
======
* Research
  * Quantitative and data analysis
  * Literature review and synthesis
* Programming and application development
  * Virtual Reality Application (Unity)
  * AI Application (Python)

Publications
======
  <ul>
  {% assign sorted_posts = site.publications | sort: 'date' | reverse %}
    {% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!--
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
-->

  

Teaching
======
  <ul>
    {% assign sorted_posts = site.teaching | sort: 'date' | reverse %}
    {% for post in sorted_posts %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>


<!--
Service and leadership
======
* Currently signed in to 43 different slack teams
-->