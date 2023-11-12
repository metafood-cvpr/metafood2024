---
title: Keynotes
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: https://cvis2021.weebly.com/uploads/5/6/3/0/56308869/background-images/236520036.jpg
  actions:
permalink: /keynotes
toc: true
keynotes:
  - title: Visual Human Motion Analysis
    time:
    url:
    image: 
    abstract: "
    Recent advancement of imaging sensors and deep learning techniques has opened door to many interesting applications for visual analysis of human motions. In this talk, I will discuss our research efforts toward addressing the related tasks of 3-D human motion syntheses, pose and shape estimation from images and videos, visual action quality assessment. Looking forward, our results could be applied to everyday life scenarios such as natural user interface, AR/VR, robotics, and gaming, among others. 
    "
    author:
      name: Li Cheng, PhD
      description: "Professor, Faculty of Engineering - Electrical & Computer Engineering Dept - University of Alberta"
      bio: 
        "
        Li CHENG is a professor at the Department of Electrical and Computer Engineering, University of Alberta. He is an associate editor of IEEE Transactions on Multimedia. Prior to joining University of Alberta, He worked at A*STAR, Singapore, TTI-Chicago, USA, and NICTA, Australia. His current research interests include human motion analysis, mobile and robot vision, and multimedia data analytics. More details can be found at http://www.ece.ualberta.ca/~lcheng5/.
        "
---


{% for keynote in page.keynotes %}
## {{ keynote.title }}
{% if keynote.time %} <img src="{{ keynote.image}}" class="align-left" style="width: calc(30% - 0.5em);"/> {% endif %}


{% if keynote.time %} <sub>{{keynote.time}} </sub>  {% endif %}


{% if keynote.url %} <sub> {{keynote.url}}</sub> {% endif %}

{% if keynote.abstract %}
**Abstract:** 
{{keynote.abstract}}
{% endif %}

**Speaker Info:**
{{keynote.author.name}}

{{keynote.author.description}}

{{keynote.author.bio}}

{% endfor %}
