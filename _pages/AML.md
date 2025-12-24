---
layout: archive
title: "Research on Autonomous Decision-Making Agents for Super Mario Bros Based on Various Deep DQN Architectures"
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
This work is the final project for the Advanced ML course at the University of Lincoln. This project implements and compares five DQN-based agents with different network architectures for autonomous gameplay in the Super Mario Bros environment. The implemented agents include Nature DQN (CNN), Nature DQN (RNN), Nature DQN (Transformer), Double DQN (<a href="https://pytorch.org/tutorials/intermediate/mario_rl_tutorial.html"
     target="_blank"
     style="color:#1a0dab; text-decoration:none;">From the PyTorch official tutorial</a>), and Dueling DQN. All models are value-based deep reinforcement learning methods grounded in Q-learning, approximating the action-value function \( Q(s, a) \) using deep neural networks. During training, the agents leverage experience replay (Replay Buffer), ε-greedy exploration, and target networks to improve training stability and sample efficiency. Under a constrained training budget of 3000 episodes, Dueling DQN achieved the highest average reward, while the Transformer-based architecture outperformed traditional CNNs in terms of average reward, highlighting its potential for future DRL research. These findings suggest that integrating Dueling structures with Transformer-based networks may lead to more effective deep reinforcement learning agents. More details about this work, please check this <a href="/files/AML.pdf"
   target="_blank"
   style="color:#1a0dab; text-decoration:underline;">
  report</a>. The code has been released on
  <a href="https://github.com/XuminGaoGithub/Research-on-Autonomous-Decision-Making-Agents-Based-on-Various-Deep-DQN-Architectures"
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
        src="/images/DDQN-1.gif"
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
    </div>
  </div>

</div>



<h3> Acknowledgements</h3>
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This work was supported by the Engineering and Physical Sciences Research Council and AgriFoRwArdS CDT [EP/S023917/1]. Thanks to the support of the University of Lincoln.
</p>
























