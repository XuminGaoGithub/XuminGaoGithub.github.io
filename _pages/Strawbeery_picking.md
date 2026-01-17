---
layout: archive
title: "Open-Vocabulary Vision–Language Segmentation for Strawberry Harvesting Scene Understanding"
permalink: /Strawbeery_picking/
author_profile: true
---

---
<p style="margin: 0 0 18px 0; color:#666; font-size:0.95em;">
  <span style="margin-right:20px;">
    📅 2025
  </span>
  <span>
    🔖 RA Projects
  </span>
</p>

<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
This RA work is part of a strawberry harvesting efficiency evaluation study led by Dr. Leonardo Guevara at the Lincoln Institute for Agri-Food Technology, University of Lincoln. My primary contribution was to test and compare five SAM-centric and CLIP-centric open-vocabulary vision–language segmentation methods for strawberry harvesting scene understanding. These methods include SAM, FC-CLIP, CLIP-SAM, Grounded-SAM, and Semantic Segment Anything. The primary target objects for recognition include ripe strawberries, unripe strawberries, foliage, trolleys, punnets, and human hands. 

<div style="
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 5px;
  margin: 20px 0;
">

  <!-- 左图容器 -->
  <div style="
    width: 800px;
    display: flex;
    flex-direction: column;
    align-items: center;
  ">
    <div style="
      height: 800px;
      display: flex;
      justify-content: center;
      align-items: center;
    ">
      <img
        src="/images/comparason_strwberry_picking.jpg"
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

<h2>Conclusions</h2> 
<p style="margin-top:5px; text-align: justify; text-justify: inter-word; text-align-last: left;">
SAM achieves fine-grained segmentation but lacks semantic understanding. FC-CLIP is relatively effective at identifying foliage, though it occasionally misclassifies strawberries as foliage and struggles with identifying punnets. SSA offers more detailed recognition, yet suffers from significant confusion among classes. CLIP-SAM demonstrates superior overall recognition performance, though ripe and unripe strawberries, as well as foliage and unripe strawberries, are prone to misclassification. Grounded-SAM exhibits the most balanced performance: despite performing poorly on distant strawberries and occasional failures in identifying punnets and trolleys, it accurately identifies and segments the majority of target objects, making it the most effective method. The following presents the results obtained using Grounded-SAM.

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
      src="/images/strawberry_picking_src.gif"
      alt="strawberry_picking_src"
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
      src="/images/strawberry_picking_results.gif"
      alt="strawberry_picking_result"
      style="
        max-width: 100%;
        max-height: 100%;
        object-fit: contain;
        border-radius: 6px;
      "
    />
  </div>

</div>

  

























