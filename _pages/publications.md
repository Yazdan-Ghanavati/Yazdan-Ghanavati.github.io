---
layout: archive
title: "Research Experiences"
permalink: /Research/
author_profile: true
---


## Education  
B.Sc. in Biomedical Engineering			
2018 Sept – 2023 Jan
University of Isfahan, Isfahan, Iran
•	CGPA: 3.2 out of 4 (16.04/20)
•	GPA of Senior Level Courses: 3.54 out of 4 
•	9 Semesters, Full Scholarship
•	Capstone Project: “Behneshan; A video game to teach sign language to deaf children using AI and Machine Vision”
•	Supervisor: Dr. Javad Rasti
•	Selected Courses (Grade out of 20):                                                                                                                                  B.Sc. Project: 20, Biostatistics and Research Methods: 20, Communication Systems in Medicine: 18.3,                    Data Mining: 19, Advanced Computer Programming: 19.75, Principles of Diagnostic Radiology and Radiation Therapy Systems: 18.4, Physiology: 20, Microcontrollers: 20, Principles of Medical Physics: 20


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
