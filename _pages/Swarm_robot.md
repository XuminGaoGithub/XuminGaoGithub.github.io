---
layout: archive
title: "Swarm Robot Exploration Based on a Custom-Designed STM32 Platform"
permalink: /Swarm_robot/
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
This work was part of a swarm robotics research project led by Associate Professor Lei Bin at the Institute of Robotics and Intelligent Systems, Wuhan University of Science and Technology. The project focused on exploring swarm robotic behaviors using custom-designed STM32-based PCB. Representative behaviors investigated included group walking, cooperative object transportation, and firefly-inspired synchronized flashing. 

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
      src="/images/dance_robot.png"
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
      src="/images/dance_robot.gif"
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
My primary contribution was the design of a custom STM32-based circuit board specifically for firefly-inspired synchronized flashing experiments. The board integrates Bluetooth communication, a camera module, an LCD display, and other modules. By leveraging color recognition and Bluetooth-based communication, the system mimics the collective synchronization of flashing behavior observed in natural firefly swarms. Specifically, in the swarm robotic system, each robot maintains an internal phase variable that increases over time. Using an onboard camera and color recognition algorithms, the robot perceives flashing signals emitted by neighboring robots. When a nearby robot’s flash is detected, the current phase is recorded and incorporated into subsequent phase update calculations. Once the phase reaches a predefined threshold, the robot triggers its own LED to emit a flash. Through continuous phase adjustment and visual interaction, the system ultimately achieves collective synchronized flashing behavior analogous to that observed in natural firefly swarms. The PCB schematics and code have been released on
  <a href="https://github.com/XuminGaoGithub/Swarm-Robot-Exploration-Based-on-a-Custom-Designed-STM32-Platform/tree/main?tab=readme-ov-file"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    github.
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
      src="/images/PCB_AD.jpg"
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
      src="/images/PCB.jpg"
      alt="System Framework"
      style="
        max-width: 100%;
        max-height: 100%;
        object-fit: contain;
        border-radius: 6px;
        transform: rotate(90deg);
      "
    />
  </div>

</div>


<h3>Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by a research project led by Associate Professor Lei Bin at the Institute of Robotics and Intelligent Systems, Wuhan University of Science and Technology. The team members include Gao Xumin, Li Kan, Leibin.
</p>


























