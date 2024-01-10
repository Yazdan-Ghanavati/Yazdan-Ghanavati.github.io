---
layout: archive
title: "Research Experiences"
permalink: /Research/
author_profile: true
---


## Publications
**Yazdan Ghanavati**, Javad Rasti, “Behneshan: An Educational Video Game Utilizing Image Processing and Machine Learning Techniques to Teach Persian Sign Language to Deaf Children”, 6th International Serious Games Symposium (ISGS), 2023, status: Accepted
&nbsp;
&nbsp;

**Yazdan Ghanavati**, Javad Rasti, “A video game to teach PSL (Persian sign language) to deaf children based on Action Recognition”, 2023, status: under-preparation
&nbsp;
&nbsp;

**Yazdan Ghanavati**, Maryam Salehi, Javad Rasti, " Controlling computer games by tracking the body's anatomical marker points; real immersion Experience in virtual space", Seventh International Conference of Video Games, Challenges and Opportunities, Isfahan, Iran, 2022 (This Paper is Written in Persian)
&nbsp;
[Download paper here](https://civilica.com/doc/1445614)
&nbsp;

## Patent
### “ Human Pose Tracking Package ”, Software Application		 			        
This Windows-based application enables users to control exergames using physical movements by converting their actions into precise keyboard and mouse commands. It offers an alternative method of exercising for overweight individuals or those with muscle-related issues. Status: under-evaluation
&nbsp;

[Details of this project](https://github.com/Yazdan-Ghanavati/Human-Pose-Tracking-Package)
&nbsp;
2021 Sept - Present
&nbsp;
&nbsp;
&nbsp;



## Projects
### Behneshan; A video game to teach sign language to deaf children using AI asnd Machine Vision       	         
University of Isfahan, BME department, Isfahan, Iran				          
This project uses LSTM neural networks to create a software that teaches Persian Sign Language (PSL) to deaf children via a platformer game, Computer Vision techniques, and pose landmark recognition. The system accurately recognizes 29 PSL letters and practical words with a 96% accuracy rate.
&nbsp;

[Details of this project](https://github.com/Yazdan-Ghanavati/Behneshan)
&nbsp;
&nbsp;

2022 Sept - Present
&nbsp;
&nbsp;

[This project has been anounced as one of the top 3 projects in the field of serious games by the Iranian National Computer Games Foundation](https://ircg.ir/s/2ff)
&nbsp;
&nbsp;

### Breast cancer detection			   							           
A MATLAB project based on image-processing techniques (thermogram image processing) for breast cancer detection. 
&nbsp;
&nbsp;

[Details of this project](https://github.com/Yazdan-Ghanavati/Breast-Cancer-Detection)
&nbsp;
2022 Jun
&nbsp;

### Dyslexia treatment 											          
A C# based project developed to encourage children, in order to improve their reading and learning skills. 
&nbsp;
&nbsp;

[Details of this project](https://github.com/Yazdan-Ghanavati/Dyslexia-)
&nbsp;
2022 Dec
&nbsp;
&nbsp;



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
