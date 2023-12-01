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
  - title: Biodiversity Health Monitoring and Improvement
    time:
    url:
    image: https://lh3.googleusercontent.com/u/0/drive-viewer/AK7aPaCr3NrxONYysJvzQMeU81zEECeO1kCtxBsNsSlol7908Vltn9i3DwIRpPmh2pgsDQobNu6Uwv0dCvutzQhqh5T4DkTa=w2560-h1353
    abstract: "
    Up to 1M species face extinction in the next several decades, with biodiversity loss a major factor. In this talk, I will describe my team’s efforts to leverage advances in deep learning to monitor and improve biodiversity health. Our work is bolstered by the $24M University of Guelph-led BIOSCAN project, a global interdisciplinary effort to build a biodiversity observation system; and LIFEPLAN, a global biodiversity monitoring effort that collects data, including images, audio and DNA samples, from around 100 sites worldwide. Manual analysis of the data collected in these massive international biodiversity efforts are resource prohibitive and their success will depend on automating the analysis of images, sets, sequences, and graphs. 
    "
    author:
      name: Graham Taylor
      description:
        "Associate Professor of Engineering at the University of Guelph
        Faculty Member, Vector Institute
        Canada CIFAR AI Research Chair"
      bio: 
        "
        Graham Taylor is a Canada Research Chair and Professor of Engineering at the University of Guelph. He co-directs the University of Guelph Centre for Advancing Responsible and Ethical AI and is the Research Director, External of the Vector Institute for AI. He has co-organized the annual CIFAR Deep Learning Summer School, and trained more than 80 students and researchers on AI-related projects. In 2016 he was named as one of 18 inaugural CIFAR Azrieli Global Scholars. In 2018 he was honoured as one of Canada's Top 40 under 40. In 2019 he was named a Canada CIFAR AI Chair. He spent 2018-2019 as a Visiting Faculty member at Google Brain, Montreal.

        Graham co-founded Kindred, which was featured at number 29 on MIT Technology Review's 2017 list of smartest companies in the world. He is the Academic Director of NextAI, a non-profit accelerator for AI-focused entrepreneurs.
        "
  - title: Visual Human Motion Analysis
    time:
    url:
    image: https://vision-and-learning-lab-ualberta.github.io/author/li-cheng/avatar_huc2687370fa97988757d31395fff45c12_66166_270x270_fill_q90_lanczos_center.jpg
    abstract: "
    Recent advancement of imaging sensors and deep learning techniques has opened door to many interesting applications for visual analysis of human motions. In this talk, I will discuss our research efforts toward addressing the related tasks of 3-D human motion syntheses, pose and shape estimation from images and videos, visual action quality assessment. Looking forward, our results could be applied to everyday life scenarios such as natural user interface, AR/VR, robotics, and gaming, among others. 
    "
    author:
      name: Li Cheng, PhD
      description: "Professor, Faculty of Engineering - Electrical & Computer Engineering Dept - University of Alberta"
      bio: 
        "
        Li CHENG is a professor at the Department of Electrical and Computer Engineering, University of Alberta. He is an associate editor of IEEE Transactions on Multimedia. Prior to joining University of Alberta, He worked at A*STAR, Singapore, TTI-Chicago, USA, and NICTA, Australia. His current research interests include human motion analysis, mobile and robot vision, and multimedia data analytics. More details can be found at [http://www.ece.ualberta.ca/~lcheng5/](http://www.ece.ualberta.ca/~lcheng5/).
        "
  - title: AI for Precision Medicine - An MRI-based End-to-End Pipeline for Molecular Diagnosis of Pediatric Brain Tumours
    time:
    url:
    image: https://medical-imaging.utoronto.ca/sites/default/files/styles/square_1_1_900/public/assets/faculty/image/Khalvati%2C%20F.webp?itok=i5EE6z16
    abstract: 
      "
      Pediatric low-grade gliomas (pLGG) are the most common brain tumours in children. With surgical excision as the main treatment, and chemotherapy and radiation as additional treatment options, the 10-year progression-free survival is less than 50% and affected children commonly suffer multiple recurrences requiring multi-modal therapy leading to considerable morbidity. Recent advances in identifying genetic markers for different molecular subtypes of pLGG have had a significant impact on patient outcome with improved prognosis and individualized treatment strategies. However, biopsies are invasive, and cannot capture the entirely of tumour. In this talk, I will present MRI-based AI solutions combined with healthcare informatics, which we have developed for the molecular diagnosis of pLGG using the latest MRI prior to surgery or biopsy. I will also briefly talk about the specific challenges of AI models for pLGG (e.g., confidence, and lack of training data), and possible solutions.
      "
    author:
      name: Farzad Khalvati, MASc, PhD
      description: 
        "
        • Scientist & Endowed Chair in Medical Imaging and Artificial Intelligence 
        • Neurosciences & Mental Health Program, Research Institute
        • Department of Diagnostic & Interventional Radiology
        • The Hospital for Sick Children


        • Associate Professor
        • Department of Medical Imaging
        • Institute of Medical Science (IMS)
        • Department of Computer Science
        • Department of Mechanical and Industrial Engineering
        • University of Toronto
        • Faculty Affiliate, Vector Institute
        • Intelligent Medical Informatics Computing Systems Lab (IMICS Lab)
        "
      bio:
        "
        Dr. Farzad Khalvati received his PhD in Electrical and Computer Engineering from the University of Waterloo, Ontario, Canada and currently, he is a Scientist and Endowed Chair in Medical Imaging and Artificial Intelligence at The Hospital for Sick Children (SickKids) and the University of Toronto (UofT). He is an Associate Professor in the Department of Medical Imaging and Institute of Medical Science at UofT, with cross appointments to the Departments of Computer Science, and Mechanical and Industrial Engineering. He is also a Faculty Affiliate at the Vector Institute. Dr. Khalvati is the director of Intelligent Medical Informatics Computing Systems Lab [(IMICSLab.com)](https://www.IMICSLab.com) at SickKids where he leads the design, development, validation, and deployment of AI tools for early diagnosis and prognosis, and individualized treatment planning of different diseases including cancer, using multi-modal data such as medical imaging and healthcare informatics. Interpretable, human-centered, and optimized AI for medicine, and AI for equitable access to healthcare are other aspects of his research program. 
        
        
        Dr. Khalvati has published ~100 peer-reviewed publications in scientific journals and conference proceedings with additional 52 peer-reviewed scientific abstracts presented in different international conferences. He has received over $3.6M in peer-reviewed research funding ($2.5M as PI and Co-PI) from different Canadian grant agencies including Natural Sciences and Engineering Research Council of Canada (NSERC), Canadian Institutes of Health Research (CIHR), New Frontiers in Research Fund (NFRF), Canadian Cancer Society, and Brain Canada Foundation. As the primary supervisor, Dr. Khalvati has supervised over 65 trainees at different levels and his students have received $246K in scholarships and awards.
        "
---


{% for keynote in page.keynotes %}
## {{ keynote.title }}
<img src="{{ keynote.image}}" class="align-left" style="width: calc(30% - 0.5em);"/>


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
