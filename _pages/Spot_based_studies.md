---
layout: archive
title: "Spot-Based Robotic Studies"
permalink: /Spot_based_studies/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2023-2025
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
      src="/images/dog_shepherd.gif"
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
In this work, my primary contribution was the design and implementation of a GPS-based autonomous navigation system on a Spot quadruped robot running ROS 2. The final implementation involved creating a ROS 2 navigation node that subscribes to a GPS topic to obtain positioning data and determine the robot’s current latitude and longitude. Based on the relationship between the current position and a predefined target location, the Haversine formula was used to compute the geographic distance between the two points, while bearing calculation was applied to determine the desired direction of motion toward the target. The distance and direction information were then converted into cmd_vel velocity control commands, enabling the Spot robot to gradually approach the target using a control strategy that combines rotation and forward motion, thereby achieving GPS-based point-to-point autonomous navigation. We also attempted to implement a more complete and refined navigation solution using the Nav2 framework; however, due to project time constraints and the complexity of system integration and debugging, this approach did not be successfully deployed. 
  
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
The following video shows the actual test results. Due to the absence of a gyroscope sensor, the robot’s pose could not be accurately estimated, resulting in sluggish movement. In addition, the GPS module used exhibited significant drift, causing the robot to fail to precisely reach the designated target point, even though the GPS feedback indicated that it was within 1.5 meters of the goal. The code has been released on
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
    src="https://www.youtube.com/embed/FiAzW4aQwps"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>

## Acknowledgements
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by the Engineering and Physical Sciences Research Council and AgriFoRwArdS CDT [EP/S023917/1]. Thanks to the support of the University of Lincoln.
</p>







## 2. Robotic phenotyping
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This short-term project originated from the AgriFoRwArdS CDT 2024 Summer School, jointly hosted with Wageningen University & Research, where participants collaboratively explored robotic phenotyping through hands-on group projects and field experiments. Further details can be found <a href="https://new.express.adobe.com/webpage/68Psphd1Liu5x"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    here.
  </a>
</p>


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
      src="/images/dog_shepherd.gif"
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
In this work, my primary contribution was the design and implementation of a GPS-based autonomous navigation system on a Spot quadruped robot running ROS 2. The final implementation involved creating a ROS 2 navigation node that subscribes to a GPS topic to obtain positioning data and determine the robot’s current latitude and longitude. Based on the relationship between the current position and a predefined target location, the Haversine formula was used to compute the geographic distance between the two points, while bearing calculation was applied to determine the desired direction of motion toward the target. The distance and direction information were then converted into cmd_vel velocity control commands, enabling the Spot robot to gradually approach the target using a control strategy that combines rotation and forward motion, thereby achieving GPS-based point-to-point autonomous navigation. We also attempted to implement a more complete and refined navigation solution using the Nav2 framework; however, due to project time constraints and the complexity of system integration and debugging, this approach did not be successfully deployed. 
  
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
The following video shows the actual test results. Due to the absence of a gyroscope sensor, the robot’s pose could not be accurately estimated, resulting in sluggish movement. In addition, the GPS module used exhibited significant drift, causing the robot to fail to precisely reach the designated target point, even though the GPS feedback indicated that it was within 1.5 meters of the goal. The code has been released on
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
    src="https://www.youtube.com/embed/FiAzW4aQwps"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>

## Acknowledgements
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by the Engineering and Physical Sciences Research Council and AgriFoRwArdS CDT [EP/S023917/1]. Thanks to the support of the University of Lincoln.
</p>
























