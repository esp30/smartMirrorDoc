---
layout: post
title:  "Week 7, Team + Mentor Meetings"
categories: [ info, weekly-progress ]
image: assets/images/logbook.jpg
featured: false
logbook: true
---

*1. Team Meeting 27 March, 11h-12h*
* Discussed Demo 1 constraints and planned it
  * Objective is to prove everything is working
  * Must make a video demonstrating at least part of the system, beforehand
  * Scheduled meeting next week to do so
  * Server will be temporarily deployed in a Raspberry Pi, since the given server is not accessible at the moment
  * Database will be deployed, without the final relations 

*2. Team Meeting 27 March, 12h-13h*
* Discussed MVP
  * Consider Memorandum of Understanding to fully grasp the concept of MVP
  * Shorten list of features in the current MVP (now a vision report) to present a viable MVP
  * Consider prediction of effort for each feature and extrapolate from the work done when each feature will be concluded.

* Discussed several deployment specifics
  * Consider already done web frameworks for the UI portions of the system (search for LTE Admin, Ionic, Flutter)
  * SCI Server is needed because we have to do HTTP Requests
  * Inside the stand controller:
    * Sensors + card reader + weight modules only push info saying "I detected movement/change"
    * UI module only sends to display
    * Between these modules, there will be a module (MQTT broker with a bridge to another MQTT broker @SCI)
    * All algorithmic processing will be done @SCI -> centralized
  * SCI now registered at the DB and is not a screen-less device. It's responsible for the calculs associated with the 
  * Dashboard for canteen workers to add meals, etc, will be Web, directly hosted on the main server, avoid duplication of information.
  * Database in MySQL is a possibility 

