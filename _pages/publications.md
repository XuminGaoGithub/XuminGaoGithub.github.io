---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

欢迎来到我的 Publications 页面。下面包含我发表的论文（支持图文布局）。

---

## 📝 2025

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 30px;">

  <!-- Left image -->
  <div style="flex: 0 0 220px;">
    <img src="/images/xumin.jpg" alt="Multi-CAP" style="width: 220px; border-radius: 6px;">
  </div>

  <!-- Right content -->
  <div style="flex: 1;">

  ### **Multi-CAP: A Multi-Robot Connectivity-Aware Hierarchical Coverage Path Planning Algorithm for Unknown Environments**

  Zongyuan Shen, Burhanuddin Shirose, **Prasanna Sriganesh**, Bhaskar Vundurthy,  
  Howie Choset, Matthew Travers  
  *arXiv preprint arXiv:2509.14941*, 2025  

  <p>
    <a href="https://arxiv.org/abs/2509.14941" style="margin-right:15px;">📄 Full Paper</a>
    <a href="https://www.youtube.com/watch?v=cp83SsG9wjY" style="margin-right:15px;">🎞️ Video</a>
  </p>

  <details>
    <summary><b>Show Abstract</b></summary>
    <p>
    Efficient coordination of multiple robots for coverage of large, unknown environments is a significant challenge that involves minimizing the total coverage path length while reducing inter-robot conflicts. In this paper, we introduce a Multi-robot Connectivity-Aware Planner (Multi-CAP), a hierarchical coverage path planning algorithm that facilitates multi-robot coordination through a novel connectivity-aware approach. The algorithm constructs and dynamically maintains an adjacency graph that represents the environment as a set of connected subareas. Critically, we make the assumption that the environment, while unknown, is bounded. This allows for incremental refinement of the adjacency graph online to ensure its structure represents the physical layout of the space, both in observed and unobserved areas of the map as robots explore the environment. We frame the task of assigning subareas to robots as a Vehicle Routing Problem (VRP), a well-studied problem for finding optimal routes for a fleet of vehicles. This is used to compute disjoint tours that minimize redundant travel, assigning each robot a unique, non-conflicting set of subareas. Each robot then executes its assigned tour, independently adapting its coverage strategy within each subarea to minimize path length based on real-time sensor observations of the subarea. We demonstrate through simulations and multi-robot hardware experiments that Multi-CAP significantly outperforms state-of-the-art methods in key metrics, including coverage time, total path length, and path overlap ratio. Ablation studies further validate the critical role of our connectivity-aware graph and the global tour planner in achieving these performance gains.
    </p>
  </details>

  </div>

</div>

---


---

### **Evaluation and Incident Prevention in an Enterprise AI Assistant**  
Akash V. Maharaj, David Arbour, Daniel Lee, Uttaran Bhattacharya, Anup Rao, Austin Zane, Kun Qian, **Yunyao Li**  
_IAAI 2025_  
🏅 **DSRI AI Incidents and Best Practices Paper Award**  
[🔗 Paper](https://ojs.aaai.org/index.php/AAAI/article/view/35161)  
[🔗 Blog](https://blog.developer.adobe.com/raising-the-bar-for-ai-assistant-in-adobe-experience-platform-f45dda4b2783)

---

## 📝 2024

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 30px;">

  <!-- Left image -->
  <div style="flex: 0 0 220px;">
    <img src="/images/xumin.jpg" alt="Aphid CNN Project" style="width: 220px; border-radius: 6px;">
  </div>

  <!-- Right text -->
  <div style="flex: 1;">

  ### **Developing a Hybrid Convolutional Neural Network for Automatic Aphid Counting in Sugar Beet Fields**
  **Xumin Gao**, Wei Xue, Chris Lennox, Melissa Stevens, Junfeng Gao  
  *Computers and Electronics in Agriculture*, Vol. 220, 2024, 108910  

  <p>
    <a href="https://www.sciencedirect.com/science/article/pii/S0168169924003016" style="margin-right:15px;">📄 Full Paper</a>
    <a href="https://huggingface.co/spaces/XuminGao/Aphid-Counting" style="margin-right:15px;">🎞️ Online App</a>
  </p>

  </div>

</div>

---






