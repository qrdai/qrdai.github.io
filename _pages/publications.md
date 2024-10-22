---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---
<style>
    .bullet::before {
        content: "• "; /* Unicode character for a bullet */
        font-size: 1em; /* Adjust the size as needed */
    }
</style>

# Preprints

<div style="display: flex; align-items: center; margin-bottom: 50px;">
  <img src="{{ site.baseurl }}/images/DGS.png" alt="Image" style="width: 40%; margin-right: 40px;">
  <div>
    <h3>Demonstration Distillation for Efficient In-Context Learning</h3>
    <p>Tong Chen, <strong>Qirun Dai</strong>, Zhijie Deng, Dequan Wang</p>
    <p><em>Submitted to ICLR 2024</em></p>
    <p class="bullet">Through meticulous prompt engineering, we develop a training-free framework that leverages multiple LLM agents to iteratively compress the given demonstrations.</p>
    <p class="bullet">It achieves up to a 4.3x compression ratio and a 5% accuracy improvement on various QA tasks, demonstrating efficacy in reducing computational overheads while boosting inference performance.</p>
    <div style="display: flex; margin-top: 20px;">
      <a href="https://openreview.net/forum?id=Y8DClN5ODu" target="_blank" style="text-decoration: none;">
        <button style="background-color: white; border: 1px solid #ccc; border-radius: 10px; padding: 8px 40px; font-size: 14px; cursor: pointer;">Paper</button>
      </a>
      <a href="https://github.com/CTDancer/DGS_Demonstration-Distillation" target="_blank" style="text-decoration: none; margin-left: 10px;">
        <button style="background-color: white; border: 1px solid #ccc; border-radius: 10px; padding: 8px 40px; font-size: 14px; cursor: pointer;">Code</button>
      </a>
    </div>
  </div>
</div>

