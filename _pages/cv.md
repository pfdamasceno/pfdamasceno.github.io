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
* B.S. in Physics, U of Sao Carlos, SP, Brazil, 2005
* Ph.D in Applied Physics, U of Michigan, MI, 2015
* Postdoc in Cellular and Molecular Pharmacology, UCSF, CA, 2017

Work experience
======
* 2017 - Data Scientist in Radiology (UCSF)
  * Machine Learning applied to patient care
  * Duties included:
    * Matlab -> Python conversions
    * Continuous integration
    * Git integration
    * Server management

Skills
======
* Machine Learning / Data-driven Modeling:
  * Autoencoder / CNN
  * Clustering & Classification
  * Graph Convolution Networks
  * Time series Classification
* Physics-based Modeling:
  * Agent-based Models (Complex Systems)
  * Network Theory
  * Thermodynamics & Statistics
* Multi-Scale Computer Simulations:
  * Finite Elements
  * Markov Chain Monte Carlo (MCMC)
  * Monte Carlo
  * Molecular Dynamics

Publications
======
  <ul>{% for post in site.publications %}
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
