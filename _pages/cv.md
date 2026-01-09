---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D in Electronic Engineering**, Queen Mary University of London, 2024-Present
  * EPSRC DTP Funded
  * Research: AI-driven RF localisation for wireless capsule endoscopy

## Skills

* **Programming:** Python, SQL
* **Machine Learning:** TensorFlow, PyTorch
* **Cloud Computing:** AWS (Lambda, EC2, RDS)
* **Hardware:** Software-Defined Radio, Antenna Design
* **Frameworks:** Django, Flask

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
