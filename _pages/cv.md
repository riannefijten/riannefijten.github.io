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
* **Medical Software Developer**, [Maastro Clinic](http://maastro.nl), 2016 - 2017
* **PhD researcher**
  * **Topic:** Translational Research on Exhaled Volatile Organic Compounds from Bedside to Bench
  * **Location:** [Dept. of Pharmacology & Toxicology](https://phartox.nl/), Maastricht University 
  * **Date:** 2013 - 2017
* **Google Summer of Code**, Student programmer, 2012


Education
======
* **PhD**, Maastricht University, 2017
* **MSc. Biomedical Sciences**, Maastricht University, 2011 - 2013
  * **Internship**. Imperial College, London, United Kingdom (8 months). *Topic*: Analysis of gene amplifications in breast cancer reveals SQLE as a predictor of poor outcome in estrogen receptor-positive disease
  * **Internship**. Dept. of Toxicogenomics, Maastricht University (6 months). *Topic*: Identifying non-genotoxic effects of carcinogens using bioinformatics 
* **BSc. Biomedical Sciences**, Maastricht University, 2008 - 2011
  * **Internship**. Dept. of Bioinformatics (2.5 months). *Topic:* Pathway modulation at the mRNA level in Crohn’s disease and ulcerative colitis.

Committees and workgroups
======
* **[Open Science Community Maastricht (OSCM)](http://twitter.com/oscmaastricht)**, Founder & representative, 2019 - present
* **[ICT&Health](https://www.icthealth.nl/redactieraad/rianne-fijten/)**, Editorial Board Member, 2019 - present
* [**Female Empowerment Maastricht (FEM)**](https://www.maastrichtuniversity.nl/about-um/diversity-inclusivity/di-organisations/fem-female-empowerment-maastricht-university) 
  * Board member, 2019 - present
  * Ambassador, 2019
* **Workgroup Implementation Shared Decision Making in Oncology at Maastro (WISDOM)**, Chair/Leader, 2018 - present
* **[NUTRIM](https://www.maastrichtuniversity.nl/research/school-nutrition-and-translational-research-metabolism) PhD student council**, Chair, 2014 - 2016
* **[FHML](https://www.maastrichtuniversity.nl/about-um/faculties/faculty-health-medicine-and-life-sciences) Interfaculty PhD council**, NUTRIM PhD student representative, 2014 - 2016
* **Maastricht University Kidz College program**, Organizer, 2014 - 2015

Research grants
======
  <ol>{% for post in site.grants reversed%}
    {% include archive-single-grant-cv.html %}
  {% endfor %}</ol>

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
  