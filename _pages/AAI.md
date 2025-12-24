---
layout: archive
title: "Tallon AI: Probabilistic Decision-Making in Mean Arena"
permalink: /AAI/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2018
  </span>
  <span>
    🔖 Competition work
  </span>
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
To address the limitations of hand gesture interaction methods in practical scenarios, such as the complexity of sensor-based interaction and the high cost and distance constraints of 3D vision reconstruction, this work developed an intelligent human–robot interactive mobile grasping robot based on monocular vision–based hand gesture detection and recognition.
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
In terms of the hardware system, a tracked mobile platform is employed as the carrier, integrating an Arduino control board, a servo-driven mechanical gripper, a PcDuino with a camera module for real-time visual monitoring, and wireless communication technology. The Arduino is responsible for executing motion commands of the tracked vehicle and controlling the opening and closing of the mechanical gripper. The PcDuino captures environmental video and transmits the video stream to the PC via mjpg-streamer, thereby enabling remote monitoring of the robot. On the PC side, corresponding hand gestures are performed based on the remotely monitored environment and then recognized, after which the information is transmitted wirelessly to the Arduino board to interactively control the robot's movement and grasping.
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
    width: 400px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
  ">
    <img
      src="/images/HRHandpose_robot.png"
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
      src="/images/HRHandpose_frame.png"
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
In terms of hand gesture detection and recognition, a lightweight SSD-based network is adopted to achieve real-time detection and recognition of multiple hand gestures, including oplam (open_palm), cplam (close_palm), fist, and ok. Specifically, the cplam gesture is used to control the motion of the tracked mobile robot, where the relative position of the gesture center with respect to the image center determines the movement direction. The oplam, fist, and ok gestures are employed to control the opening and closing of the mechanical gripper and to stop the motion of the mobile robot, respectively.
</p>

<div style="text-align: center; margin: 25px 0;">
  <img
    src="/images/HRHandpose_reg.png"
    alt="Crack Recognition Results"
    style="width: 800px; max-width: 100%; border-radius:6px;"
  />
</div>


<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
The following video is a test demo, and the original source code has been released on
  <a href="https://github.com/XuminGaoGithub/An-Intelligent-Human-Robot-Interactive-Mobile-Grasping-Robot-Based-on-Visual-Gesture-Recognition"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    github.
  </a>
</p>


<div style="display:flex; justify-content:center; margin:35px 0;">
  <iframe
    width="720"
    height="405"
    src="https://www.youtube.com/embed//ItFX8F2m2y4"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>

### Acknowledgements
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
Thanks to the support of the Institute of Robotics and Intelligent Systems, Wuhan University of Science and Technology, and Associate Professor Lei Bin. The team members include Gao Xumin, Xiao Chao, Wang Huayu, and Lei Bin.
</p>
























