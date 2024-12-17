---
layout: page
title: Intelligent Child Home Monitoring System
description: Recognizing Hazards with YOLO and Pose Recognition
img: assets/img/12.jpg
importance: 1
category: _computer vision
related_publications: true
giscus_comments: true
toc:
    sidebar: left
---

## Project Overview  
This project aims to address safety concerns in home environments by monitoring children's activities in real time. The system combines advanced deep learning algorithms with full-stack software development to ensure reliable and efficient performance. By leveraging the **YOLOv7** object detection model and the **PP-TinyPose** pose estimation model, the system detects hazardous postures, such as window climbing, with high precision. Additionally, **SE-Net** is incorporated to improve feature representation and reduce model loss, further enhancing detection accuracy. The system is optimized for real-time performance, allowing it to adapt seamlessly under varying lighting conditions and detect activities in diverse home settings. Its implementation ensures a safer and smarter home monitoring solution for families.  

## Key Features
- **Hazard Detection**: Identifies dangerous postures and activities, such as window climbing.  
- **Lighting Adaptation**: Automatically adjusts detection under varying lighting conditions for consistent performance.  
- **Electronic Fence**: Monitors restricted areas and provides alerts when boundaries are crossed.  
- **Real-Time Monitoring**: Ensures continuous surveillance and accurate hazard recognition.  

## Algorithms Used
- **YOLOv7**: A state-of-the-art real-time object detection algorithm known for its speed and accuracy in identifying and localizing objects within images or videos. 
- **PP-TinyPose**: A lightweight and efficient pose estimation model designed for real-time human keypoint detection, balancing accuracy and speed for edge and mobile devices.  
- **SE-Net**: A neural network architecture that enhances feature representations by adaptively recalibrating channel-wise feature responses, improving model accuracy with minimal computational cost.  
---

## Video Demo
Check out the system in action!  
{% include video.liquid path="assets/video/Intelligent_Child_Home_Monitoring_System.mp4" class="img-fluid rounded z-depth-1" controls=true %}

---  


