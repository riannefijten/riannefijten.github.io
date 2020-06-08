---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* **Senior Scientist**, [Maastro Clinic](http://maastro.nl), 2019 - Present
* **Postdoctoral Researcher**, [Maastro Clinic](http://maastro.nl), 2017 - 2019
* **PhD researcher**
  * **Topic:** Translational Research on Exhaled Volatile Organic Compounds from Bedside to Bench
  * **Location:** [Dept. of Pharmacology & Toxicology](https://phartox.nl/), Maastricht University 
  * **Date:** 2013 - 2017

Education
======
* **PhD**, Maastricht University, 2017
* **MSc. Biomedical Sciences**, Maastricht University, 2011 - 2013
* **BSc. Biomedical Sciences**, Maastricht University, 2008 - 2011

Committees and workgroups
======
* Founder & representative, [Open Science Community Maastricht (OSCM)](http://twitter.com/oscmaastricht)
* Editorial Board Member, [ICT&Health](https://www.icthealth.nl/redactieraad/rianne-fijten/)
* Board member, [Female Empowerment Maastricht (FEM)](https://www.maastrichtuniversity.nl/about-um/diversity-inclusivity/di-organisations/fem-female-empowerment-maastricht-university)


Publications
======
  <ol>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>
  
Talks
======
  <ol>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ol>
  
Teaching
======
  <ul>{% for post in site.teaching reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  