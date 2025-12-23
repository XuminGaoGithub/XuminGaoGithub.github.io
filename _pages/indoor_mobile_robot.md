---
layout: archive
title: "An indoor mobile robot platform"
permalink: /indoor_mobile_robot/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2018
  </span>
  <span>
    🔖 Research Project
  </span>
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
In this project, we designed and developed an indoor mobile robot platform from scratch, integrating SLAM technologies and deep learning. In terms of hardware, the robot chassis is equipped with two rear active wheels driven by GW4058-555 DC motors and a front passive omni-directional wheel, enabling basic mobility. The platform is also equipped with an LMS111 LiDAR sensor and a Kinect v2 RGB-D camera for environmental perception, while a laptop or NUC serves as the main control system. On the software side, SLAM is implemented using ROS packages, including Gmapping for mapping and AMCL for localization, while navigation is performed using A* for global path planning and DWA for local path planning. For perception, Caffe, combined with CUDA and cuDNN, is used to deploy deep learning models for indoor object detection. The team members included Gao Xumin, Wang Han, Guang Xingyu, Nie Wenkang, and Jiang Lin.
</p>



<div style="
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
  margin: 10px 0;
  flex-wrap: nowrap;
">
  <!-- 左图 -->
  <div style="
    width: 500px;
    height: 350px;
    display: flex;
    justify-content: center;
    align-items: center;
  ">
    <img
      src="/images/indoor_robot.jpg"
      alt="Indoor Mobile Robot"
      style="
        max-width: 100%;
        max-height: 100%;
        object-fit: contain;
        border-radius: 6px;
      "
    />
  </div>

  <!-- 右视频 -->
  <iframe
    width="500"
    height="350"
    src="https://www.youtube.com/embed/mzSDeYdyUKI"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="border-radius:8px;">
  </iframe>
</div>


<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This autonomous mobile platform served as a foundational basis for my subsequent Master’s research, providing support for studies such as <a href="https://github.com/XuminGaoGithub/An-algorithm-of-extracting-line-feature-of-laser-radar-combined-with-SVM/tree/main"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    line feature extraction of laser radar and indoor local structured environment recognition using line features </a>, and <a href="https://iopscience.iop.org/article/10.1088/1742-6596/1651/1/012142/meta"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    indoor object detection and semantic map construction. </a> 



<h3> Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by a research project led by Professor Jiang Lin at the Institute of Robotics and Intelligent Systems, Wuhan University of Science and Technology.
</p>
























