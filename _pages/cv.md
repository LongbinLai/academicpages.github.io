---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
FYI
======
Please find my complete CV [here](https://longbinlai.github.io/files/cv.pdf).

Education
======
* B.S. in Science of Engineering, Shanghai Jiao Tong University, 2010
* M.S. in Engineering, Shanghai Jiao Tong University, 2013
* Ph.D in Computer Science, University of New South Wales, Sydney, 2017

Work experience
======
* Winter/Spring 2017: Technical Intern
  * Google Inc. Mountain View
  * Duties included: Designed and implemented an emulator that simulates the Google backbone network and the routing strategies for testing, debugging and routing validation.

* Jan.-Dec. 2012: 
  * Alibaba Cloud Computing Corporation
  * Duties included: (1) Designed and implemented a web recommendation system based on Alibaba cloud computing system (MapReduce-like system), which serves over 1000 top websites in China; (2) improved the throughput of the recommendation system to over 2 billion records per hour via a well-designed MapReduce data flow; (3) Implemented a prototype of web classification algorithm that is twice faster than existing algorithm by solely using the url of the web page.
  
Skills
======
* Programming
  * Java (Expert), C++ (Expert), Python (Prior Experienced), Scala (Prior Experienced) and Rust (Prior Experienced)
* Big Data
  * Hadoop (Expert), Spark (Proficient), Giraph (Prior Experienced)
* Machine Learning
  * TensorFlow (Proficient)
* Web
  * Yii2 on PHP, Django on Python

Publications
======
  <ol style="color: inherit; font-weight: normal">{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>
  
Teaching
======
  <ol style="color: inherit; font-weight: normal">{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
