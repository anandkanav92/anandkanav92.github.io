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
* Bachelors in Computer Science, Vellore institute of Technology, Vellore, 2010-14
* Masters in Data Science, Delft University of Technology, 2017-19

Work experience
======
* ADI 2019: Data Scientist
  * developing a data pipeline to ingest images and develop a deep learning model to detect diseased reducing the prior manual detection time from ~48 hours to ~25 minutes.
  * Developed an object detection model based on Faster RCNN with ResNet-101 backbone using a detectron2 framework built using PyTorch and open-cv.

* InMoBi 2015: Software Developer
  * Worked with the Big Data team to shift from pintail to Kafka platform, an open-source platform used for building real-time data pipelines catering over a billion events each day improving the ingestion rate by hours.
  * Worked with the USER platform team to develop and test live batch streaming applications for gathering appropriate information about users from terabytes of data, using Spark and Aerospike. This collected information is used for showing relevant ads.
* Knolskape 2014: Software Developer
  * Worked on a web-based application that is used to evaluate the performance of a relationship manager. My responsibilities included database schema designing, developing back-end using Laravel(PHP) and implementing the front-end using Javascript(Backbone.js). These simulations enabled MNCs to filter out ideal candidates in earlier stages. [LINK](https://blog.knolskape.com/hubfs/simualtions%20ebooks%20whitepaper/KNOLSKAPE_Inbox_Simulation.pdf)    
 
Skills
======
* Java, Python
* PyTorch
* Spark
* Kafka
* SQL
* Jenkins
* Postgres

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Extra
======
* Deep learning, Football
* Sports and Gaming: runners up at State level basketball annual competition for Delhi, won several tournaments for Counter-Strike 1.6 tournaments while representing VIT, Vellore. 
