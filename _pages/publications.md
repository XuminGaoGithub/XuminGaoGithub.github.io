---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
You can also find my articles on
[my Google Scholar profile]({{ https://scholar.google.com/citations?user=bvDizmUAAAAJ&hl=en }}).
{% endif %}



---

<!-- Year Divider -->
<div style="display: flex; align-items: center; margin: 40px 0 20px 0;">
  <div style="flex: 1; height: 3px; background-color: #333;"></div>
  <div style="padding-left: 12px; font-size: 1.4em; font-weight: 700;">2025</div>
</div>

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/Robot_stirring_2.gif">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      A Robotic Stirring Method with Trajectory Optimization and Adaptive Speed Control for Accurate Pest Counting in Water Traps
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>, Mark Stevens, Grzegorz Cielniak
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> arXiv preprint arXiv:2510.21732
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> September, 2025  
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> 
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://arxiv.org/abs/2510.21732" style="margin-right:15px;">📄 Full Paper</a>
      <!-- <a href="https://github.com/XuminGaoGithub/Automatic_aphid_counting___2023" style="margin-right:15px;">💻 Code</a> -->
      <a href="https://www.youtube.com/watch?v=lLbWPpn5N40">🎞️ Video</a>
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        Accurate monitoring of pest population dynamics is crucial for informed decision-making in precision agriculture. Currently, mainstream image-based pest counting methods primarily rely on image processing combined with machine learning or deep learning for pest counting. However, these methods have limitations and struggle to handle situations involving pest occlusion. To address this issue, this paper proposed a robotic stirring method with trajectory optimization and adaptive speed control for accurate pest counting in water traps. First, we developed an automated stirring system for pest counting in yellow water traps based on a robotic arm. Stirring alters the distribution of pests in the yellow water trap, making some of the occluded individuals visible for detection and counting. Then, we investigated the impact of different stirring trajectories on pest counting performance and selected the optimal trajectory for pest counting. Specifically, we designed six representative stirring trajectories, including circle, square, triangle, spiral, four small circles, and random lines, for the robotic arm to stir. And by comparing the overall average counting error and counting confidence of different stirring trajectories across various pest density scenarios, we determined the optimal trajectory. Finally, we proposed a counting confidence-driven closed-loop control system to achieve adaptive-speed stirring. It uses changes in pest counting confidence between consecutive frames as feedback to adjust the stirring speed. To the best of our knowledge, this is the first study dedicated to investigating the effects of different stirring trajectories on object counting in the dynamic liquid environment and to implement adaptive-speed stirring for this type of task. Experimental results show that the four small circles is the optimal stirring trajectory, achieving the lowest overall average counting error of 4.3840 and the highest overall average counting confidence of 0.7204. Furthermore, experimental results show that compared to constant-speed stirring, adaptive-speed stirring demonstrates significant advantages across low, medium, and high pest density scenarios: the average time consumption was reduced by 38.9%, 44.8%, and 36.5%, respectively, while fluctuations were markedly decreased, with the standard deviation reduced by 52.8%, 78.1%, and 70.2%, respectively, reflecting adaptive-speed stirring achieves better efficiency and stability.
      </p>
    </details>

  </div>
</div>

---


---

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/counting_confidence.jpg">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      Counting with Confidence: Accurate Pest Monitoring in Water Traps
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>, Mark Stevens, Grzegorz Cielniak
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> AGRICONTROL 2025
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> August, 2025  
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> Davis, California, U.S.A
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S2405896325024917" style="margin-right:15px;">📄 Full Paper</a>
      <!-- <a href="https://github.com/XuminGaoGithub/Automatic_aphid_counting___2023" style="margin-right:15px;">💻 Code</a> -->
      <!-- <a href="https://www.youtube.com/watch?v=lLbWPpn5N40">🎞️ Video</a> -->
      <a href="/files/Counting with Confidence Accurate Pest Monitoring in Water Traps.pdf" target="_blank">📑 Presentation</a>

    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        Accurate pest population monitoring and tracking their dynamic changes are crucial for precision agriculture decision-making. A common limitation in existing vision-based automatic pest counting research is that models are typically evaluated on datasets with ground truth but deployed in real-world scenarios without assessing the reliability of counting results due to the lack of ground truth. To this end, this paper proposed a method for comprehensively evaluating pest counting confidence in the image, based on information related to counting results and external environmental conditions. First, a pest detection network is used for pest detection and counting, extracting counting result-related information. Then, the pest images undergo image quality assessment, image complexity assessment, and pest distribution uniformity assessment. And the changes in image clarity caused by stirring during image acquisition are quantified by calculating the average gradient magnitude. Notably, we designed a hypothesis-driven multi-factor sensitivity analysis method to select the optimal image quality assessment and image complexity assessment methods. And we proposed an adaptive DBSCAN clustering algorithm for pest distribution uniformity assessment. Finally, the obtained information related to counting results and external environmental conditions is input into a regression model for prediction, resulting in the final pest counting confidence. To the best of our knowledge, this is the first study dedicated to comprehensively evaluating counting confidence in counting tasks, and quantifying the relationship between influencing factors and counting confidence through a model. Experimental results show our method reduces MSE by 31.7% and improves R² by 15.2% on the pest counting confidence test set, compared to the baseline built primarily on information related to counting results.
      </p>
    </details>

  </div>
</div>


---

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/HRIN.png">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      The Human-Robot Interactive Reinforcement Learning for Robot Navigation of The Factory Transportation System in Grid World Environment
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> TechRxiv preprint
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> 2025 （research completed in 2022） 
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> 
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://www.techrxiv.org/users/985215/articles/1350678-the-human-robot-interactive-reinforcement-learning-for-robot-navigation-of-the-factory-transportation-system-in-grid-world-environment" style="margin-right:15px;">📄 Full Paper</a>
      <a href="https://github.com/XuminGaoGithub/Human-Robot-Interactive-Reinforcement-Learning-for-Factory-Robot-Navigation" style="margin-right:15px;">💻 Code</a>
      <!-- <a href="https://www.youtube.com/watch?v=vtq7Nuemw4Q&t=108s">🎞️ Video</a> -->
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        In order to improve the learning ability of robot in factory transportation system and speed up the learning cycle for robots to deal with the changing environment, on the basis of investigating the current research work of robot navigation in factory transportation system, this paper designs three different interactive reinforcement learning (IRL) algorithms and apply them to the navigation task for robots in factory transportation system. We verify the designed algorithms in the discrete grid world. From the experiment results, we can see that the third designed IRL algorithm using modified exploration strategy with the human suggestion and the feedback achieves the best effect, the success rate of completing the task is 90%, and the learning cycle is between other two algorithms. The project code is released at: https://github.com/XuminGaoGithub/Human-Robot-Interactive-Reinforcement-Learning-for-Factory-Robot-Navigation. 
      </p>
    </details>

  </div>
</div>

---

---




<!-- Year Divider -->
<div style="display: flex; align-items: center; margin: 40px 0 20px 0;">
  <div style="flex: 1; height: 3px; background-color: #333;"></div>
  <div style="padding-left: 12px; font-size: 1.4em; font-weight: 700;">2024</div>
</div>


---

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/ICP42024_VAIB.jpg">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      Interactive Image-Based Aphid Counting in Yellow Water Traps under Stirring Actions
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>, Mark Stevens, Grzegorz Cielniak
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> VAIB Workshop at ICPR 2024
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> December, 2024  
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> Kolkata, India
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://homepages.inf.ed.ac.uk/rbf/VAIB24PAPERS/vaib24xg.pdf" style="margin-right:15px;">📄 Full Paper</a>
      <!-- <a href="https://github.com/XuminGaoGithub/Automatic_aphid_counting___2023" style="margin-right:15px;">💻 Code</a> -->
      <!-- <a href="https://www.youtube.com/watch?v=lLbWPpn5N40">🎞️ Video</a> -->
      <a href="/files/Interactive Image-Based Aphid Counting in Yellow Water Traps under Stirring Actions.pdf" target="_blank">📑 Presentation</a>
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        The current vision-based aphid counting methods in water traps suffer from undercounts caused by occlusions and low visibility arising from dense aggregation of insects and other objects. To address this problem, we propose a novel aphid counting method through interactive stirring actions. We use interactive stirring to alter the distribution of aphids in the yellow water trap and capture a sequence of images which are then used for aphid detection and counting through an optimized small object detection network based on Yolov5. We also propose a counting confidence evaluation system to evaluate the confidence of count-ing results. The final counting result is a weighted sum of the counting results from all sequence images based on the counting confidence. Experimental results show that our proposed aphid detection network significantly outperforms the original Yolov5, with improvements of 33.9% in AP@0.5 and 26.9% in AP@[0.5:0.95] on the aphid test set. In addition, the aphid counting test results using our proposed counting confidence evaluation system show significant improvements over the static counting method, closely aligning with manual counting results. 
      </p>
    </details>

  </div>
</div>

---


<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
  <div style="flex: 0 0 300px;">
    <img src="/images/Hybrid aphid counting network architecture.jpg" alt="Hybrid" style="width: 220px; border-radius: 6px;">
  </div>

  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      Developing a hybrid convolutional neural network for automatic aphid counting in sugar beet fields
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>, Wenxin Xue, Callum Lennox, Mark Stevens, Junfeng Gao
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> Computers and Electronics in Agriculture
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> May, 2024  
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> 
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S0168169924003016" style="margin-right:15px;">📄 Full Paper</a>
      <a href="https://github.com/XuminGaoGithub/Automatic_aphid_counting___2023" style="margin-right:15px;">💻 Code</a>
      <a href="https://huggingface.co/spaces/XuminGao/Aphid-Counting">🌐 Online App</a>
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        Aphids can cause direct damage and indirect virus transmission to crops. Timely monitoring and control of their populations are thus critical. However, the manual counting of aphids, which is the most common practice, is labor-intensive and time-consuming. Additionally, two of the biggest challenges in aphid counting are that aphids are small objects and their density distributions are varied in different areas of the field. To address these challenges, we proposed a hybrid automatic aphid counting network architecture which integrates the detection network and the density map estimation network. When the distribution density of aphids is low, it utilizes an improved Yolov5 to count aphids. Conversely, when the distribution density of aphids is high, it switches to CSRNet to count aphids. To the best of our knowledge, this is the first framework integrating the detection network and the density map estimation network for counting tasks. Through comparison experiments of counting aphids, it verified that our proposed approach outperforms all other methods in counting aphids. It achieved the lowest MAE and RMSE values for both the standard and high-density aphid datasets: 2.93 and 4.01 (standard), and 34.19 and 38.66 (high-density), respectively. Moreover, the AP of the improved Yolov5 is 5 % higher than that of the original Yolov5. Especially for extremely small aphids and densely distributed aphids, the detection performance of the improved Yolov5 is significantly better than the original Yolov5. This work provides an effective early warning caused by aphids in sugar beet fields, offering protection for sugar beet growth and ensuring sugar beet yield. The datasets and project code are released at: https://github.com/JunfengGaolab/Counting-Aphids.
      </p>
    </details>

  </div>
</div>

---


---

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/GrapCounting.gif">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      Automatic Detection, Positioning and Counting of Grape Bunches Using Robots
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> arXiv preprint arXiv:2412.10464
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> 2024 （research completed in 2022） 
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> 
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://arxiv.org/abs/2412.10464" style="margin-right:15px;">📄 Full Paper</a>
      <a href="https://github.com/XuminGaoGithub/Grape_bunches_count_using_robots" style="margin-right:15px;">💻 Code</a>
      <a href="https://www.youtube.com/watch?v=vtq7Nuemw4Q&t=108s">🎞️ Video</a>
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        In order to promote agricultural automatic picking and yield estimation technology, this project designs a set of automatic detection, positioning and counting algorithms for grape bunches, and applies it to agricultural robots. The Yolov3 detection network is used to realize the accurate detection of grape bunches, and the local tracking algorithm is added to eliminate relocation. Then it obtains the accurate 3D spatial position of the central points of grape bunches using the depth distance and the spatial restriction method. Finally, the counting of grape bunches is completed. It is verified using the agricultural robot in the simulated vineyard environment. The project code is released at: https://github.com/XuminGaoGithub/Grape_bunches_count_using_robots. 
      </p>
    </details>

  </div>
</div>

---



---

<!-- Year Divider -->
<div style="display: flex; align-items: center; margin: 40px 0 20px 0;">
  <div style="flex: 1; height: 3px; background-color: #333;"></div>
  <div style="padding-left: 12px; font-size: 1.4em; font-weight: 700;">2022</div>
</div>

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/S-SSD.png">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      Lightweight object detection network model suitable for indoor mobile robots
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      Lin Jiang, Wenkang Nie, Jianyang Zhu, <b>Xumin Gao</b>, Bin Lei 
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> Journal of Mechanical Science and Technology
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> February 2022  
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> 
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://link.springer.com/article/10.1007/s12206-022-0138-2" style="margin-right:15px;">📄 Full Paper</a>
      <!-- <a href="https://github.com/XuminGaoGithub/Automatic_aphid_counting___2023" style="margin-right:15px;">💻 Code</a> -->
      <!-- <a href="https://www.youtube.com/watch?v=lLbWPpn5N40">🎞️ Video</a> -->
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        This work proposes a lightweight object detection network model ShuffleNet-SSD (S-SSD) to solve the problem of single shot multibox detector (SSD) network model where it cannot meet the real-time performance requirement in the task of object detection and recognition of indoor mobile robot. This model is suitable for indoor mobile robot by improving the SSD network model based on ShuffleNet network. The main idea of the improvement is that S-SSD replaces VGG-16 network as the basic feature extraction network of SSD network model with ShuffleNet network. The proposed model is based on the design of deep separable convolution, point-by-point grouping convolution, and channel rearrangement. It retains the design idea of multiscale feature graph detection of SSD network model. This model ensures a slight decline in detection accuracy while greatly reduces the amount of computation generated by the network operation, thereby greatly improving the detection rate. A data set for the task of object detection and recognition of indoor mobile robot is made. The S-SSD lightweight network model is superior to the original SSD network model and tiny-YOLO lightweight network model in terms of detection accuracy and detection rate, and can simultaneously meet the requirement of detection accuracy and real-time performance in the task of indoor object detection and recognition of mobile robot. These findings are verified through the comparative experiments of object detection accuracy and detection rate and real-time object detection and recognition of mobile robot under the actual indoor scene.
      </p>
    </details>

  </div>
</div>

---


---

<!-- Year Divider -->
<div style="display: flex; align-items: center; margin: 40px 0 20px 0;">
  <div style="flex: 1; height: 3px; background-color: #333;"></div>
  <div style="padding-left: 12px; font-size: 1.4em; font-weight: 700;">2020</div>
</div>

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/semantic_map.png">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      Real-time indoor semantic map construction combined with the lightweight object detection network
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>, Lin Jiang, Xingyu Guang and Wenkang Nie 
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> Journal of physics: conference series
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> 2020  
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> 
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://iopscience.iop.org/article/10.1088/1742-6596/1651/1/012142/meta" style="margin-right:15px;">📄 Full Paper</a>
      <!-- <a href="https://github.com/XuminGaoGithub/S-SSD" style="margin-right:15px;">💻 Code</a> -->
      <a href="https://www.youtube.com/watch?v=mzSDeYdyUKI">🎞️ Video</a>
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        Aiming at the lack of semantic information of indoor objects in the grid map commonly used in the indoor mobile robot, this paper proposes a real-time indoor semantic map construction method combined with the lightweight object detection network: firstly, we proposes a lightweight object detection network which is called S-SSD (ShuffleNet-SSD) by improving the SSD (Single Shot MultiBox Detector) network, it can be used to extract the semantic information of indoor objects in real time; then the semantic information of indoor objects is transformed into the grid map which is created by mobile robot, so the indoor semantic map is constructed. The effectiveness and superiority of S-SSD in the indoor object detection of mobile robot are verified by the comparative experiment, and the effectiveness of the real-time indoor semantic map construction proposed in this paper is verified by the experiment of semantic map construction.
      </p>
    </details>

  </div>
</div>

---

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/MMUUNET.png">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      MMUU-Net: A Robust and Effective Network for Farmland Segmentation of Satellite Imagery
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>, Long Liu and Huaze Gong 
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> Journal of physics: conference series
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> 2020  
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> 
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://iopscience.iop.org/article/10.1088/1742-6596/1651/1/012189/meta" style="margin-right:15px;">📄 Full Paper</a>
      <a href="https://github.com/XuminGaoGithub/MMUU-Net" style="margin-right:15px;">💻 Code</a>
      <a href="https://www.youtube.com/watch?v=lvSMl95cTJI">🎞️ Video</a>
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        Aiming at the multi-scale characteristics of satellite imagery, and the adhesion phenomenon in the farmland segmentation results which is caused by the close distance between different farmland blocks, this paper proposes a robust and effective network based on U-Net for farmland segmentation of satellite imagery, which is called MMUU-Net. On the basis of adopting the encoder with higher classification accuracy network, adding ASPP (Atrous Spatial Pyramid Pooling) layer in the middle, and designing the multi-scale feature fusion module in the decoder, so that the multi-scale feature information is fully utilized; in order to better fuse multi-scale information, a more robust loss function is designed; finally, we propose a segmentation strategy of the coarse and refined two-stage to eliminate the adhesion phenomenon. Through the comparative experiments, it is verified that MMUU-Net is better than other segmentation networks, and can be effectively applied to the task of farmland segmentation of satellite imagery.
      </p>
    </details>

  </div>
</div>

---


---

<!-- Year Divider -->
<div style="display: flex; align-items: center; margin: 40px 0 20px 0;">
  <div style="flex: 1; height: 3px; background-color: #333;"></div>
  <div style="padding-left: 12px; font-size: 1.4em; font-weight: 700;">2019</div>
</div>

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 40px;">

  <!-- 左侧图片 -->
 <div style="flex: 0 0 300px;">
  <img src="/images/extracing line feature.png">
 </div>

 
  <!-- 右侧内容 -->
  <div style="flex: 1;">

    <!-- Title -->
    <h3 style="margin-top:0; margin-bottom:10px; font-weight: 700;">
      An algorithm of Extracting Line Feature of Laser Radar Combined with SVM 
    </h3>

    <!-- Authors -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">👤👤👤</span>
      <b>Xumin Gao</b>, Lin Jiang , Han Wang, Xingyu Guang
    </p>

    <!-- Publisher -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📚</span> Computer Engineering and Design
    </p>

    <!-- Date + Location -->
    <p style="margin: 5px 0; line-height:1.4em;">
      <span style="margin-right:6px;">📅</span> 2019  
      &nbsp;&nbsp;&nbsp;
      <span style="margin-right:6px;">📍</span> 
    </p>

    <!-- Buttons -->
    <p style="margin: 10px 0;">
      <a href="https://xueshu.baidu.com/ndscholar/browse/detail?paperid=16760eu011440cd03c1b0ce0ax126705&site=xueshu_se" style="margin-right:15px;">📄 Full Paper</a>
      <a href="https://github.com/XuminGaoGithub/An-algorithm-of-extracting-line-feature-of-laser-radar-combined-with-SVM" style="margin-right:15px;">💻 Code</a>
      <!-- <a href="https://www.youtube.com/watch?v=lLbWPpn5N40">🎞️ Video</a> -->
    </p>

    <!-- Abstract collapsible -->
    <details>
      <summary><b>Show Abstract</b></summary>
      <p style="margin-top:5px; text-align: justify; text-justify: inter-word;">
        Aiming at the phenomenon that the fixed segmentation threshold leads to under segmentation and over segmentation in extracting line feature of laser radar data using the IEPF algorithm,a separate and merged extraction algorithm of line feature combined with support vector machine was proposed. In separate stage,the IEPF algorithm was used to segment the data preliminarily. In the merged stage,the threshold value was adjusted to eliminate the line segments of under segmentation as far as possible, and the three features from over segmented line segments and normal line segments which included the adjacent degree, the collinear degree and the overlap degree were extracted respectively as feature vectors to train the SVM model. The SVM model was applied to the actual test, and the classification results which were over segmented line segments were merged. Experimental results show that the proposed algorithm effectively eliminates most of the over segmented line segments and under segmented line segments produced by line segment extraction using IEPF algorithm.
      </p>
    </details>

  </div>
</div>

---














