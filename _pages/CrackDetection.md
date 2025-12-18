---
layout: archive
title: "Crack Detection System Based on Drone Vision"
permalink: /CrackDetection/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2017
  </span>
  <span>
    🔖 Research Project
  </span>
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
To meet the demand for automated infrastructure crack inspection, this project develops a crack detection and recognition system integrating UAV platforms and computer vision techniques.
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
In terms of the hardware system, a quadrotor UAV is used as the carrier, integrating a camera, a wireless image transmission module, an ultrasonic distance sensor, and a wireless data transmission module to achieve synchronized acquisition and remote transmission of crack images and shooting distance information. On the PC side, video streams and distance data are received in real time through the image and data transmission modules, providing a data basis for subsequent analysis.
</p>

<div style="
  display: flex;
  justify-content: center;
  gap: 30px;
  flex-wrap: wrap;
  margin: 20px 0;
">
  <img
    src="/images/Crack_drone"
    alt="Crack Detection UAV"
    style="width: 320px; max-width: 100%; border-radius:6px;"
  />
  <img
    src="/images/Crack_framework"
    alt="System Framework"
    style="width: 320px; max-width: 100%; border-radius:6px;"
  />
</div>



<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
In terms of image processing and crack recognition, OpenCV is employed to perform grayscale conversion, filtering, histogram equalization, adaptive thresholding, and morphological operations on the acquired crack images, enabling automatic crack detection and contour extraction. Furthermore, projection features, area features, and distribution density features of cracks are extracted to construct feature vectors, which are then used to train an SVM classifier for automatic identification of crack types, including transverse, longitudinal, diagonal, and reticular cracks. Finally, by calculating the distances between pixel points on both sides of the crack contour and combining ultrasonic distance measurements with pixel-to-real-world scale transformation, the maximum crack width and actual crack area are accurately computed.
</p>

<div style="text-align: center; margin: 25px 0;">
  <img
    src="/images/Crack_Rec"
    alt="Crack Recognition Results"
    style="width: 520px; max-width: 100%; border-radius:6px;"
  />
</div>


<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
The following video presents the actual testing results. And the original source code has been released on
  <a href="https://github.com/XuminGaoGithub/Crack-Detection-System-Based-on-Drone-Vision"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    github.
  </a>
</p>


<div style="display:flex; justify-content:center; margin:35px 0;">
  <iframe
    width="720"
    height="405"
    src="https://www.youtube.com/embed/xgqmUpdp-0A"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>
























