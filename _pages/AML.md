---
layout: archive
title: "Tallon AI: Probabilistic Decision-Making in Mean Arena"
permalink: /AML/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2022
  </span>
  <span>
    🔖 Course project
  </span>
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work is the final project for the Advanced AI course at the University of Lincoln. I designed an AI decision-making agent based on probabilistic reasoning and optimal policy planning, integrating Markov Decision Processes, value iteration, belief state updates and others to enable rational sequential decision-making under both fully observable and partially observable environments. Under fully observable conditions, the game is modeled as a Markov Decision Process (MDP), in which a state transition model and a reward function are constructed, and the optimal policy is obtained using value iteration. Within this framework of maximizing expected long-term reward, Tallon is encouraged to avoid enemies and pits while prioritizing the collection of bonuses. Under partially observable conditions, the problem is further extended to a Partially Observable Markov Decision Process (POMDP), where belief states over enemy locations are maintained and combined with a prediction mechanism to approximate the incomplete information and map it back to an MDP for decision-making. In addition, reward shaping strategies based on distance and aggregated risk are introduced to enhance survivability and overall performance. Experimental results demonstrate that the proposed approach exhibits good robustness and adaptability across different map sizes and parameter configurations. More details about this work, please check this <a href="/files/mean-Gao-Xumin.pdf"
   target="_blank"
   style="color:#1a0dab; text-decoration:underline;">
  report</a>. The code has been released on
  <a href="https://github.com/XuminGaoGithub/Tallon-AI-Probabilistic-Decision-Making-in-Mean-Arena"
     target="_blank"
     style="color:#1a0dab; text-decoration:underline;">
    github.
  </a>


<div style="
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  margin: 20px 0;
">

  <!-- 左图容器 -->
  <div style="
    width: 400px;
    display: flex;
    flex-direction: column;
    align-items: center;
  ">
    <div style="
      height: 300px;
      display: flex;
      justify-content: center;
      align-items: center;
    ">
      <img
        src="/images/fullMDP.gif"
        alt="Crack Detection UAV"
        style="
          max-width: 100%;
          max-height: 100%;
          object-fit: contain;
          border-radius: 6px;
        "
      />
    </div>
    <div style="
      margin-top: 8px;
      text-align: center;
      font-size: 16px;
    ">
      Fully observable environment
    </div>
  </div>

  <!-- 右图容器 -->
  <div style="
    width: 400px;
    display: flex;
    flex-direction: column;
    align-items: center;
  ">
    <div style="
      height: 300px;
      display: flex;
      justify-content: center;
      align-items: center;
    ">
      <img
        src="/images/partMDP.gif"
        alt="System Framework"
        style="
          max-width: 100%;
          max-height: 100%;
          object-fit: contain;
          border-radius: 6px;
        "
      />
    </div>
    <div style="
      margin-top: 8px;
      text-align: center;
      font-size: 16px;
    ">
      Partially observable environment
    </div>
  </div>

</div>




<h3> Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by the Engineering and Physical Sciences Research Council and AgriFoRwArdS CDT [EP/S023917/1]. Thanks to the support of the University of Lincoln.
</p>
























