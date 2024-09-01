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
* **2022 - present:  PhD Student at Friedrich-Alexander-Universität Erlangen-Nürnberg, Department Hardware-Software-Co-Design**
* **2019 - 2021: M.S. in Computer Science, Friedrich-Alexander-Universität Erlangen-Nürnberg**
  * Thesis: Energy Efficient Deployment of Deep Learning Applications on Restricted Hardware using Deep Compression (in cooperation with Fraunhofer IIS Nuremberg)
  * Relevant Coursework: Artificial Intelligence, Deep Learning, Operating Systems Design, Distributed Systems, Virtual Machines
* **2015 - 2019: B.S. in Computer Science, Friedrich-Alexander-Universität Erlangen-Nürnberg**
  * Thesis: Android Inter Process Communication Fuzzing
  * Relevant Coursework: Computer Graphics, Embedded Systems, Hyperperformance Computing

Work experience
======
* **2022 - present: Research Assistant at Friedrich-Alexander-Universität Erlangen-Nürnberg, Department Hardware-Software-Co-Design and Fraunhofer IIS, Group Efficient AI**
  * Automated design, compression, and deployment of deep neural networks (DNNs) on Cortex-M microcontrollers for image and time series classification and regression tasks
  * On-device training of fully quantized DNNs on Cortex-M microcontrollers
  * Design, implementation, and maintenance of three demonstrators for live audio classification, object detection, and on-device training of DNNs on Cortex-M microcontrollers

* **2020 - 2022: Student Assistant at Fraunhofer IIS, Group "Self-Learning Systems" and "Machine Learning & Validation", Nuremberg**
  * Compression of deep neural networks for deployment on restricted hardware
  * Duties includes: Updates and improvements to template
  * Evaluation of different parameter reduction, quantization, and graph optimization techniques for deep neural networks

* **2015 - 2020: Working Student at Siemens AG, Erlangen**
  * Design, development and integration of a webservice into the open, cloud based IoT system Mindsphere
  * Continuous delivery and maintenance of the webservice as a tool used by Mindsphere´s system test and quality assurance departments
  * Implementation of an Android application and a web UI for the webservice
  * Implementation of automated UI tests based on the Selenium framework

* **Summer 2015: Internship at Siemens AG, Erlangen**
  * Design and Development of a webservice for easy test analytics based on Google's ACC-model
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!--Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
