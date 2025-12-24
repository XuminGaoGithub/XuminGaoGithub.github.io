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

<h2>1. From Bark to Bot – Making of a Robotic Shepherd</h2>
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
  <a href="https://github.com/XuminGaoGithub/Spot-Based-Robotic-Studies/tree/main/gps_cmd_vel_navigator"
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

<h3>Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by the Engineering and Physical Sciences Research Council and AgriFoRwArdS CDT [EP/S023917/1]. Thanks to the support of the University of Lincoln.
</p>



<h2>2. Robotic phenotyping</h2>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This short-term project originated from the AgriFoRwArdS CDT 2024 Summer School, jointly hosted with Wageningen University & Research, where participants collaboratively explored robotic phenotyping through hands-on group projects and field experiments. Further details can be found <a href="https://new.express.adobe.com/webpage/68Psphd1Liu5x"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    here.
  </a>
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
As the topic lead for Interactive Perception, I led the design and implementation of a robot manipulation pipeline for occlusion removal in tomato plants based on the Spot quadruped robot. This enables the robot to actively manipulate leaves to reduce fruit occlusion, thereby improving the accuracy and reliability of tomato counting. The specific implementation solution is as follows: First, the Spot robot's onboard camera captures images of tomato plants, and GroundingDINO + Segment Anything Model (SAM) is employed to achieve joint detection and fine segmentation of tomato fruits and leaves. Subsequently, by analyzing the spatial overlap relationship between leaves and tomato fruits, key leaves causing occlusion are identified. Based on the segmentation mask, their geometric centroids and relative directions are calculated. On this basis, the calculated grasping points and movement directions are transmitted to the Spot robot, guiding its robotic arm to perform leaf grasping and displacement operations, thereby actively removing occlusions. The system realizes an interactive perception loop of “perception–decision–action”, creating more optimal visual conditions for subsequent tomato perception and counting tasks. The code has been released on <a href="https://github.com/XuminGaoGithub/Spot-Based-Robotic-Studies/tree/main/Spot_interactive%20perception"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">GitHub</a>.

<!-- 左图 -->
<div style="display:flex; justify-content:center; padding:0; margin:0;">
  <img src="/images/SPOT_interactive perception_1.jpg"
       alt="SPOT_interactive perception"
       style="display:block; max-width:100%; border-radius:6px; object-fit:contain;">
</div>

<!-- 右图 -->
<div style="display:flex; justify-content:center; padding:0; margin:10px 0 0 0;">
  <div style="width:300px; display:flex; justify-content:center; align-items:center;">
    <img src="/images/SPOT_interactive perception.gif"
         alt="System Framework"
         style="display:block; max-width:100%; border-radius:6px; object-fit:contain;">
  </div>
</div>

<h3>Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by the Engineering and Physical Sciences Research Council and AgriFoRwArdS CDT [EP/S023917/1]. Thanks to the support of the University of Lincoln and Wageningen University & Research.
</p>


<h2>3. Do You Remember, Spot? </h2>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This is a personal project driven by my hobby of dancing. In addition, due to the licensing restriction of Spot’s choreography module, which requires an additional fee to unlock, I spent one week programming a dance for the Spot robot without using it, based on the song "September" by Earth, Wind & Fire.. Yes, this is the second time I have choreographed a dance for the robot. Due to time constraints, the final implementation relies on coding preset dance moves that sync with the music’s beats. In the future, if time allows, I plan to develop a more intelligent dancing robot.

<!--图 -->
<div style="display:flex; justify-content:center; padding:0; margin:2px 0 0 0;">
  <div style="
       width: 300px; 
       height: 600px; 
       display:flex; 
       justify-content:center; 
       align-items:center;
  ">
    <img src="/images/Spot_dance.gif"
         alt="System Framework"
         style="
           max-width:100%; 
           max-height:100%; 
           border-radius:6px; 
           object-fit:contain;
         ">
  </div>
</div>


The video is shown below. The code has been released on
  <a href="https://github.com/XuminGaoGithub/Spot-Based-Robotic-Studies/tree/main/Spot_dance"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    github.
  </a>
</p>


<div style="display:flex; justify-content:center; margin:35px 0;">
  <iframe
    width="720"
    height="405"
    src="https://www.youtube.com/embed/41CujYzacJ4"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>

<h3>Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
Thanks to the support of the University of Lincoln.
</p>


<h2>4. The robot dog counts aphids </h2>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work is seen as an important exploration of the potential of Spot robots for the development of cutting-edge agricultural technology, using the example of automatic aphid counting in a sugar beet field. Specifically, Spot went into the sugar beet field and walked to the location of yellow water pans which are used to catch aphids, then the arm of Spot moved to the top of the yellow water pans, took images and then counted aphids using the aphid counting network we proposed. Unfortunately, when we conducted tests, the migration of the aphids had already stopped, so it hardly found any aphids in the yellow water pan. 

<div style="display:flex; justify-content:center; margin:35px 0;">
  <iframe
    width="720"
    height="405"
    src="https://www.youtube.com/embed/Zemh8i3fBTA"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>

<div style="display:flex; justify-content:center; margin:35px 0;">
  <iframe
    width="720"
    height="405"
    src="https://www.youtube.com/embed/4NEYSNmVfww"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>

We have found that Spot can easily walk through crops and causes less damage to crops compared with the wheeled robots, because it uses its leg to move. In this case, crops can also recover quickly. 

<h3>Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by the Engineering and Physical Sciences Research Council [EP/S023917/1], AgriFoRwArdS CDT and BBRO. Thanks to the support of the University of Lincoln.
</p>
























