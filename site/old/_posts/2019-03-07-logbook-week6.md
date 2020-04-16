---
layout: post
title:  "Week 6, Team + Mentor Meetings"
categories: [ info, weekly-progress ]
image: assets/images/logbook.jpg
featured: false
logbook: true
---

*1. Team Meeting 19 March, 13h00-18h*
* Discussed and planned work distribution (who's responsible and deputy responsible)
* Discussed how the modules will communicate (JAVA objects?, JSON?, others?)
* Discussed and decided releases contents
  * With detail for Release 1, M2 -> prove all modules connect 
* Discussed Database contents (Portuguese info not publicly available, must use a US version) and Abstraction Layer

*2. Team Meeting 20 March, 10h-10h30*
* Received (prior to this meeting) and discussed feedback on website -> minor adjustments will be needed (specially on separating Architecture into two parts, the less-detailed and the detailed).
* Discussed next steps: need for system acceptance tests coordinated by one person. Integration and unitary tests can be done by the responsible for each module. 
  * Each responsible must give a feature list asap to the tests coordinator.
* Discussed canteen disposition -> in line? can we allow different?

*3. Meeting with Team and Mentors, 20 March, 12h-13h*
* Sensors -> find a way to emulate the load cell?
* MVP -> not very clear how the food is identified
  * 1st phase: manual insertion (with a button)
  * 2nd phase: distance sensor
* Explain very well why the diets details are this way (percentage of proteins, etc.)
  * From goals to suggestion of percentages
* Talk with someone in nutrition area  
  * What's to lose?
  * It's an authority we can refer!
* Bancada
  * We're going to need something to build the stand (contraplacado/placa de MDF)
* UI at the stand
  * Both approaches? The screen is big enough
  * Bars solution to prove the concept, the plate (with an error) to give an indication
    * Nutricionist gives the info 
    * With a mechanism to calibrate
    * ADD NUTRICIONIST persona -> will input the recommended proportions and we have to put it in accordance to the user's profile
    * Scale to each food: 0-100%? goal 
    * Plate with the quantity of each ingredient (perhaps with an image representative of each food group) + bars 
    * DO MOCKUPS and discuss in next meetings
  * Weight for food, percentage for macronutrients
  * Divide by aisle ?

* Server: VM (Go to IT) + DB (SQLLite)

* Release 1: Our idea (concept of all modules communicating) approved

