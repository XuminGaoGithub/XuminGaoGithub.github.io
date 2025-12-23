---
layout: archive
title: "An automatic weeding robot"
permalink: /weeding_robot/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2020
  </span>
  <span>
    🔖 Product Development Project
  </span>
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
In this work, we designed and developed an automatic weeding robot by integrating computer vision and robotic technologies. In term of hardware, we designed a four-wheel-drive mobile spraying platform from scratch. The robot is equipped with multiple sensors, including an RTK positioning system, cameras and others. In addition, the system incorporates two parallel robotic arm, each with a spray nozzle mounted at the end, allowing accurate control of herbicide spraying. On the software side, the robot performs autonomous navigation using RTK based on a predefined coverage path. During motion, computer vision algorithms are employed to detect target weeds and estimate their positions in real time. The spraying system is then activated to perform point-to-point herbicide spraying, achieving precise weed control while significantly reducing herbicide usage and minimizing environmental impact. The test videos are as below.
</p>

<div style="
  display: flex;
  justify-content: center;
  gap: 10px;
  margin: 10px 0;
  flex-wrap: wrap;
">
  <iframe
    width="420"
    height="300"
    src="https://www.youtube.com/embed/f8TwxdV8Dhk"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>

  <iframe
    width="420"
    height="300"
    src="https://www.youtube.com/embed/Y09G33wrn9c"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>
>



<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
In terms of the hardware system, a quadrotor UAV is used as the carrier, integrating a camera, a wireless image transmission module, an ultrasonic distance sensor, and a wireless data transmission module to achieve synchronized acquisition and remote transmission of crack images and shooting distance information. On the PC side, video streams and distance data are received in real time through the image and data transmission modules, providing a data basis for subsequent analysis.
</p>

<div style="
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  margin: 20px 0;
">

  <!-- 左图容器（稍窄） -->
  <div style="
    width: 300px;
    height: 220px;
    display: flex;
    justify-content: center;
    align-items: center;
  ">
    <img
      src="/images/Crack_drone.jpg"
      alt="Crack Detection UAV"
      style="
        max-width: 100%;
        max-height: 100%;
        object-fit: contain;
        border-radius: 6px;
      "
    />
  </div>

  <!-- 右图容器（更宽） -->
  <div style="
    width: 600px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
  ">
    <img
      src="/images/Crack_framework.jpg"
      alt="System Framework"
      style="
        max-width: 100%;
        max-height: 100%;
        object-fit: contain;
        border-radius: 6px;
      "
    />
  </div>

</div>





<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
In terms of image processing and crack recognition, OpenCV is employed to perform grayscale conversion, filtering, histogram equalization, adaptive thresholding, and morphological operations on the acquired crack images, enabling automatic crack detection and contour extraction. Furthermore, projection features, area features, and distribution density features of cracks are extracted to construct feature vectors, which are then used to train an SVM classifier for automatic identification of crack types, including transverse, longitudinal, diagonal, and reticular cracks. Finally, by calculating the distances between pixel points on both sides of the crack contour and combining ultrasonic distance measurements with pixel-to-real-world scale transformation, the maximum crack width and actual crack area are accurately computed.
</p>

<div style="text-align: center; margin: 25px 0;">
  <img
    src="/images/CrackRec.png"
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
    src="https://www.youtube.com/embed/bnexRIGOKMY"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>

### Acknowledgements
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by a research project led by Associate Professor Lei Bin at the Institute of Robotics and Intelligent Systems, Wuhan University of Science and Technology. The research team members include Gao Xumin, Xu Pengcheng, Yi Wen, Li Kan, Zhen Chaoxue and Lei Bin.
</p>
























