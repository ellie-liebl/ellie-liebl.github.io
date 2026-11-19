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
* PhD in Linguistics, George Mason University, Fairfax, VA: 2025–present
  * Presidential Scholar
  * Supervisor: Matthew C. Kelley
* MA in English, concentration in Linguistics, George Mason University, Fairfax, VA: 2023–2026
  * Supervisor: Géraldine Walther
* BA in English Language and Literature, minor in French, Bridgewater College, Bridgewater, VA: 2015–2020
  * Study abroad: Institut universitaire d'Enseignement du Français langue Étrangère (IEFE), Université Paul-Valéry Montpellier III, Fall 2018. Elected student representative for a cohort of about 20.

Publications
======
<ul>{% for category in site.publication_category %}
  {% assign pubs = site.publications | where: "category", category[0] | reverse %}
  {% if pubs.size > 0 %}
    <h3>{{ category[1].title }}</h3>
    <ul>{% for post in pubs %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>
  {% endif %}
{% endfor %}</ul>

  
Talks
======
{% assign proceedings = site.talks | where: "type", "Conference Proceedings Talk" | reverse %}
{% assign internal = site.talks | where: "type", "Internal Presentation" | reverse %}

 <h3>Conference Proceedings</h3>
<ul>{% for post in proceedings %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

<h3>Internal Presentations</h3>
<ul>{% for post in internal %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Honors and Awards
======
* 2025-Present:Presidential Scholarship, George Mason University
* 2018: Undergraduate Research Grant, Bridgewater College

Research Experience
======
* 2025-Present: Graduate Research Assistant (Presidential Scholar), Department of English, Linguistics Program, George Mason University
  *  Lead efforts to incorporate automatic transcription, part-of-speech annotation, and machine translation into documentation pipelines for Akuzipik (St. Lawrence Island Yupik).
  * Manager, Computational Linguistics Lab, 2024–2026: coordinated lab logistics, equipment, and research workflows across interdisciplinary teams; hosted student workshops. 
* 2024-2025: Graduate Research Assistant, Department of Computer Science, George Mason University
  * PI: Antonios Anastasopoulos. NSF-funded project Award ID 2109578.
  * Developed approaches to collecting language data from diaspora communities for endangered languages, presented at ICLDC 9.


Teaching Experience
======
* 2022: Lifeguard Instructor
  * SwimKids Swim School, Leesburg, VA
  * Taught a strict curriculum designed by the American Red Cross.
  * Ensured student safety while learning potentially hazardous techniques, designed multi-part practical assessments for students

* 2021: Long-term Substitute Teacher
  * Warren County Public Schools, Front Royal, VA
  * Taught across subjects at the high-school level and at Skyline Middle School, in person and online through Canvas and Zoom.
  * Designed assignments to fit the curriculum and handled grading for about 60 middle-school students.

  
Service and leadership
======
* 2026: Treasurer, Linguistics Society, George Mason University
* 2025-2026: Department Head, Public Safety, MAGStock, MAGFest, Inc.
  * Led 20+ person department during a 4 day camping event. 
  * Logistical planning included budget drafting, schedule creation, task delegation, volunteer orientations, equipment procurement, and safety training.
* 2023-2026: Manager, Public Safety, Super MAGFest, MAGFest, Inc.
  * Volunteer-mentor for the first aid team at a 20,000+ attendee convention
  * Organized volunteer schedules, oriented new volunteers, evaluated volunteer shift performance, and coordinated with on-site EMS personnel. 
* 2022-2024: Head Lifeguard, Public Safety, MAGStock, MAGFest, Inc.
  * Logistical planning and leadership of the lifeguards for a 4 day camping event. 
  * Created schedules, acquired relevant safety equipment, and wrote standard operating procedure document for lifeguards.
* 2017-2018: Lead Student Editor, Bridgewater International Poetry Festival anthologies 

Professional Society Membership
======
* Association for Computational Linguistics (ACL), 2026

Skills
======
Language Skills:
* English: Native
* French: Mastery of CEFR B2 level French

Academic and Research Skills:
* **Programming**: Python, R, Stanza, spaCy, CRFs, Gramble, Foma
* **Computing**: HPC cluster workflows and batch job scheduling, GPU/CUDA environments
* **Speech and corpus methods**: ASR training and evaluation (WER, CER, PER, PFER), IPA transcription, corpus construction and error annotation, Praat
* **Research**: IRB protocol writing, LaTeX




