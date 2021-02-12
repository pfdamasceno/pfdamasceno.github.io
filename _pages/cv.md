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
* B.S. in Physics, U of Sao Carlos (SP), Brazil, 2005
* Ph.D in Applied Physics, U of Michigan (MI), 2015
* Postdoc in Cellular & Molecular Pharmacology, UCSF (CA) 2017
* Postdoc in Radiology & Biomedical Imaging, UCSF (CA) 2018

Work experience
======
* 2020 - Senior Machine Learning Specialist (UCSF)
  * Clinical deployment of computer vision algorithms:
    * Glioma progression detection
    * Breast tumor segmentation
    * Knee anomaly detection
    * Federated learning for COVID prevention

* 2018 - Data Scientist in Radiology (UCSF)
  * Machine Learning applied to neurodegenerative diseases:
    * Network diffusion model of proteins aggregation in the brain
    * Evaluating Alzheimer’s Disease Severity by Spectral Embedding Manifolds
  * Code / database management:
    * Matlab -> Python conversion
    * Code development (Git / CI)
    * Server / dataset management

* 2017 - Experimental Nanotech Designer (UCSF)
  * Computational Modeling of DNA
    * Workflows for microscopy image analysis
    * Molecular Dynamics models of DNA folding and assembly
    * Suites for geometrical manipulation and visualization of DNA
  * Nanofabrication of DNA origami
    * DNA-origami design and self-assembly
    * TEM (microscopy)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
