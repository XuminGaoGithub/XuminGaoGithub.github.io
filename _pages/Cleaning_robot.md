---
layout: archive
title: "A Cleaning Robot"
permalink: /Cleaning_robot/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2017
  </span>
  <span>
    🔖 Research Project on Exercise
  </span>
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
In this work, we designed and implemented a cleaning robot from scratch. We first completed the 3D structural modeling and fabricated the required structural components using laser cutting and 3D printing. Subsequently, we installed and integrated components such as motors, sensors, motor driver modules, an Arduino main control board, and cleaning and vacuuming devices to complete the hardware assembly of the robot. On the software side, we developed control programs to achieve automatic obstacle avoidance, simple path traversal, automatic cleaning and vacuuming, and automatic charging functions. 

<div style="
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
  margin: 10px 0;
">

  <!-- 左图容器（稍窄） -->
  <div style="
    width: 500px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
  ">
    <img
      src="/images/cleaning_robot_3D.png"
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
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
  ">
    <img
      src="/images/cleaning_robot.png"
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
Due to the reliance on ultrasonic sensors, complex path planning could not be implemented. Our original plan was to use LiDAR in combination with SLAM to achieve this; however, this approach was not applied to this cleaning robot. Instead, we implemented LiDAR with SLAM in another project focused on an indoor mobile robot. In addition, the exploration of the automatic charging function was not successfully realized. The following video presents the actual testing results. And the original source code has been released on
  <a href="https://github.com/XuminGaoGithub/A-simple-cleaning-robot"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    github.
  </a>
</p>

<div style="display:flex; justify-content:center; margin:35px 0;">
  <iframe
    width="720"
    height="405"
    src="https://www.youtube.com/embed//owIAkqzdEs4"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>

<h3>Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
We gratefully acknowledge the support of the Institute of Robotics and Intelligent Systems at Wuhan University of Science and Technology and Professor Jiang Lin. The team members include Gao Xumin, Wang Han, Ai Chao, and Jiang Lin.
</p>


























