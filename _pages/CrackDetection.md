---
layout: archive
title: "Crack Detection Project"
permalink: /CrackDetection/
author_profile: true
---


---
<h2 style="margin-bottom:6px;">
  Crack Detection System Based on Drone Vision
</h2>

<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 Nov 2017
  </span>
  <span>
    🔖 Research Project
  </span>
</p>

<p>
Unmanned Aerial Vehicles (UAVs) have constraints on battery life that affect their
time-of-flight. This is especially important for coverage applications in forests,
where a drone might not be recoverable from failure. In this work, we developed
and implemented a planning strategy for UAVs to plan an emergency landing on one
of landing zones in an environment which will maximize coverage within battery
life constraints.
</p>

<p>
We proposed a system consisting of two planners: a coverage planner and an emergency
planner, integrated within a behavior executive that intelligently switches modes
based on the UAV’s remaining battery life. The landing planner was based on a 3D A*
algorithm that also considered covered area as part of the cost function. Code available on
<a href="https://github.com/XuminGaoGithub/Crack-Detection-System-Based-on-Drone-Vision"
   target="_blank"
   style="color:#1a0dab; text-decoration:underline;">
  GitHub
</a>.
</p>

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 25px 0;">
  <img
    src="/images/S-SSD.png"
    alt="Simulation Environment"
    style="width: 340px; height: auto; border-radius:6px;"
  />
  <img
    src="/images/S-SSD.png"
    alt="System Architecture"
    style="width: 300px; height: auto; border-radius:6px;"
  />
</div>

<p>
Through simulations, our proposed planning system demonstrated an increase in
coverage compared to a naive closest-landing-zone planner. On average, the system
achieved approximately 10% better coverage. The planner also adapts when battery
life drops mid-flight, as demonstrated in the video below.
</p>

<div style="margin: 35px 0; text-align: center;">
  <iframe
    width="720"
    height="405"
    src="https://www.youtube.com/embed/xgqmUpdp-0A"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
    style="max-width:100%; border-radius:8px;">
  </iframe>
</div>

<p style="text-align:center; margin-top:20px;">
  🔗 Code available on
  <a href="https://github.com/XuminGaoGithub/Crack-Detection-System-Based-on-Drone-Vision" target="_blank">
    GitHub
  </a>
</p>


















