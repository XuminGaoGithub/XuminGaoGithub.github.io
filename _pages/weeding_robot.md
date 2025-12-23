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
In this work, we designed and developed an automatic weeding robot prototype by integrating computer vision and robotic technologies. In term of hardware, we designed a four-wheel-drive mobile spraying platform from scratch. The robot is equipped with multiple sensors, including an RTK positioning system, cameras and others. In addition, the system incorporates two parallel robotic arms, each with a spray nozzle mounted at the end, allowing accurate control of herbicide spraying. On the software side, the robot performs autonomous navigation using RTK based on a predefined coverage path. During motion, computer vision algorithms are employed to detect target weeds and estimate their positions in real time. The spraying system is then activated to perform point-to-point herbicide spraying, achieving precise weed control while significantly reducing herbicide usage and minimizing environmental impact. The test videos are as below.
</p>

<div style="
  display: flex;
  justify-content: center;
  gap: 20px;
  margin: 35px 0;
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

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
My main contributions to this project were integrating an industrial-grade camera with a compact computing controller (Jetson Nano) and deploying a lightweight YOLO model for the detection of specific poisonous weeds. At the same time, I debugged the socket-based communication between the vision perception computer and the parallel robotic arm controller. In addition, I participated in the overall system integration, debugging, and testing of the robotic platform.
</p>



<h3>Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by Beijing Mcfly Technology Co. Ltd and Jinan Robot Phoenix Technology Co., Ltd.
</p>
























