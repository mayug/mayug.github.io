---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## [Click here for Full CV](http://mayug.github.io/files/cv_2020_oct_condensed.pdf)


{% include base_path %}

Education
======
* B.Tech. in Electrical Engineering, IIT Madras, 2018
* M.Tech in Electrical Engineering (focus on Machine Learning and Image Processing), IIT Madras, 2018

Work experience
======
* Jun 2018-Oct 2020: Data Scientist at [Qure.ai](https://qure.ai)
  * Responsible for developing cranial bleed subtype detection algorithms using weak supervision techniques that lead to FDA approved product [qER](https://qure.ai/headct.html) which has been deployed in over 10 countries.
  * Responsible for developing cranial bleed segmentation, quantification algorithms that lead to [qQuant](https://qure.ai/headct.html) which has been deployed in over 7 countries.
  * Developed a active learning based 3d annotation portal for quick and efficient pixel-level annotations on CT scans.
  * Large Scale Analysis of Cranial Bleed Topologies- Paper to be published in an high impact radiology journal (Lancet).

* Jun 2017-May 2018: Graduate Student Researcher at [Computational Imaging Lab, IIT Madras](http://www.ee.iitm.ac.in/comp_photolab/)
  * Deep Learning based Phase Retrieval for Fourier Ptychography (FP) Microscopy
  * Medical Image Denoising using generative convolutional models.


  
Skills
======
* C, C++, Python, Matlab
* Fluent in pytorch
  * quickly deveop and deploy computer vision models


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Posters and Presentations
======
* Poster on Phase retrieval for Fourier Ptychography under varying amount of measurements presented at (Computational Cameras and Displays) CCD workshop, CVPR 2018

* Presented a poster [‘Denoising High Density Mouse Brain Images using Deep Generative Models’](https://drive.google.com/file/d/0B3qU0AODwfLbV3p4d1dtNVNHbjJGMm1zWVNIRWMtQjFNWHNB/view) at Society for Neuroscience Conference 2017 , Washington D.C.

* “Large Scale Topological Analysis of Cranial Bleeds” paper and open source dataset to be submitted to the Lancet (as of Oct 2020).

* 1 Poster presented at machine learning track of European Congress of Radiology (ECR) 2020 on building bleed classification algorithms robust to CT acquisition artifacts.

{% for post in site.posters reversed %}
  {% include archive-single.html %}
{% endfor %}
 
Teaching
======
* Jan-May 2018: Teaching Assistant for Image Processing EE 5175 for dual degree Students
* Aug-Nov 2017: Teaching Assistant for Advanced Microelectronics Lab for dual degree Students
  
