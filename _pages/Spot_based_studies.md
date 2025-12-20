---
layout: archive
title: "Spot-Based Robotic Studies"
permalink: /Spot_based_studies/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2017
  </span>
  <span>
    🔖 Mixed Projects
  </span>
</p>

## 1. From Bark to Bot – Making of a Robotic Shepherd
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This short-term project originated from the AgriFoRwArdS CDT 2025 Summer School, where participants collaboratively explored the design and prototyping of a robotic shepherd system. Further details can be found <a href="https://agriforwards-cdt.blogs.lincoln.ac.uk/2025/07/11/from-bark-to-bot-making-of-a-robotic-shepherd/"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    here.
  </a>
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
    width: 600px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
  ">
    <img
      src="/images/spot_sheep.png"
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
    width: 500px;
    height: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
  ">
    <img
      src="/images/Spot.png"
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
























