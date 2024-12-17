---
layout: page
title: Kidzoom
description: An Intelligent Home Monitoring System for Children
img: assets/img/monitor.jpg
importance: 1
category: Computer Vision
related_publications: true
giscus_comments: true
toc:
    sidebar: left
---

### Overview  
This is a mobile application based on **deep learning**, **temperature and humidity sensors**, and **full-stack software development** technologies. We developed this software to prevent children👶 who are home alone from being harmed by dangerous objects, such as flames, scissors, and glass cups, due to a lack of safety awareness. Additionally, the system effectively detects children’s window-climbing behavior and promptly sends alert notifications to the parents' mobile application, helping parents who are away from home to better supervise their children.  


### Key Features
- 🔥**Hazardous Object Detection**: Identifies dangerous items such as flames, scissors, and glass cups in the scene and sends alerts.
- ⚠️**Fall Detection Warning**: Recognizes climbing postures, calculates the overlap between the child and the window, and sends alert messages via the mobile app.
- 🌡️**Temperature and Humidity Monitoring**: Sensors detect and record environmental temperature and humidity continuously, issuing alerts when abnormal values are detected.  
- 🔅**Lighting Adaptation**: Automatically adjusts detection under varying lighting conditions for consistent performance.  
- 🚷**Electronic Fence**: Monitors restricted areas and provides alerts when boundaries are crossed.  
- 🕜**Real-Time Monitoring**: Ensures continuous surveillance and accurate hazard recognition.  


### Algorithms
- **YOLOv7**: Trained on a large, self-collected dataset of hazardous objects to improve the model's accuracy in recognizing these items. 
- **PP-TinyPose**: A lightweight and efficient pose estimation model, trained by us to detect window-climbing postures in real-time video streams.
- **SE-Net**: Considering the small spatial proportion of hazardous objects in real-world surveillance videos, this attention module is integrated into the YOLOv7 architecture to enhance the model's accuracy in detecting small objects.

---

### Video Demo
Check out the system in action!  
{% include video.liquid path="assets/video/Intelligent_Child_Home_Monitoring_System.mp4" class="img-fluid rounded z-depth-1" controls=true %}

---  


