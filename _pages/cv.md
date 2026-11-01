---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv">

<p class="cv__updated">Last updated: {{ site.time | date: "%B %Y" }}</p>

<h2>Education</h2>

<div class="cv__entry">
  <div class="cv__when">2024–present</div>
  <div class="cv__what">
    <strong>Ph.D. in Electronic Engineering</strong>, Queen Mary University of London, UK<br>
    <em>Thesis area:</em> Machine learning for RF localisation in wireless capsule endoscopy<br>
    <em>Supervisors:</em> Dr Akram Alomainy and Dr Mohamed Adhnan Thaha
  </div>
</div>

<h2>Research experience</h2>

<div class="cv__entry">
  <div class="cv__when">2024–present</div>
  <div class="cv__what">
    <strong>Doctoral Researcher</strong>, Antennas and Electromagnetics Research Group, School of Electronic Engineering and Computer Science, Queen Mary University of London<br>
    SDR-based measurement and probabilistic ML for in-body RF localisation with wearable multi-antenna systems.
  </div>
</div>

<h2>Funding and awards</h2>

<div class="cv__entry">
  <div class="cv__when">2024–present</div>
  <div class="cv__what"><strong>EPSRC Doctoral Training Partnership Studentship</strong>, UK Research and Innovation (<a href="https://gtr.ukri.org/projects?ref=studentship-2923151">studentship 2923151</a>)</div>
</div>

<h2>Publications</h2>

{% include pub-list.html %}

<h2>Teaching</h2>

<div class="cv__entry">
  <div class="cv__when">2024–present</div>
  <div class="cv__what">
    <strong>Laboratory Demonstrator</strong>, School of Electronic Engineering and Computer Science, Queen Mary University of London<br>
    ECS528U Communication Systems; ECS607U Data Mining; ECS655U Security Engineering; ECS671U Semi-Structured Data Engineering
  </div>
</div>

<h2>Technical skills</h2>

<table class="cv__skills">
  <tr><th>RF and hardware</th><td>Software-defined radio, antenna measurement, wearable antenna systems</td></tr>
  <tr><th>Machine learning</th><td>PyTorch, TensorFlow; probabilistic and generative models</td></tr>
  <tr><th>Programming</th><td>Python, SQL</td></tr>
  <tr><th>Systems</th><td>AWS (Lambda, EC2, RDS), Kubernetes, Django, Flask</td></tr>
</table>

<h2>Links</h2>

<p>
  <a href="{{ site.author.googlescholar }}">Google Scholar</a> ·
  <a href="{{ site.author.orcid }}">ORCID 0009-0002-5942-9517</a> ·
  <a href="{{ site.author.researchgate }}">ResearchGate</a> ·
  <a href="https://github.com/{{ site.author.github }}">GitHub</a> ·
  <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a>
</p>

</div>
