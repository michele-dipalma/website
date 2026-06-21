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
* Ph.D in Biomedical Sciences, University of Padova, 2026 (expected)
* Integrated Master's Degree in Pharmaceutical Chemistry and Technology, University of Padova, 2023

Work experience
======
* March 2024-July 2024: Visiting PhD student at King's College London
  * Rahman Lab
  
Skills
======
* Molecular Biology
* Recombinant protein production and purification
  * AKTA FPLC
* Biophysics
* X-ray crystallography
* Cryo-EM

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
