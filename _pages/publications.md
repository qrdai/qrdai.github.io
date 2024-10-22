---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---
<!-- <style>
    .bullet::before {
        content: "• "; /* Unicode character for a bullet */
        font-size: 1em; /* Adjust the size as needed */
    }
</style> -->

# Preprints

<div style="display: flex; align-items: center; margin-bottom: 50px;">
  <img src="{{ site.baseurl }}/images/BIDS_stats.png" alt="Image" style="width: 40%; margin-right: 40px;">
  <div>
    <h3>Improving Influence-based Instruction Tuning Data Selection for Balanced Learning of Diverse Capabilities</h3>
    <p><strong>Qirun Dai</strong>, Dylan Zhang, Jiaqi W. Ma, Hao Peng</p>
    <p><em>Under Review</em></p>
    <p>When instruction tuning LLMs for learning multiple diverse tasks, we identify the poor performance of data selection methods built upon gradient-based influence estimation techniques, and attribute this problem to an inherent bias in cross-task influence.</p>
    <p>We then propose BIDS, a simple and effective influence-based <strong>D</strong>ata <strong>S</strong>election algorithm that selects <strong>I</strong>nfluential data for <strong>B</strong>alanced capability learning.</p>
    <p>When training on <a href="https://huggingface.co/datasets/openbmb/UltraInteract_sft">UltraInteract</a>, a SOTA high-quality dataset designed to enhance diverse reasoning capabilities, we show that a 15% subset selected by BIDS can outperform full-dataset training in terms of the overall performance on 7 benchmarks spanning coding, math, STEM, logical reasoning and instruction following. We further provide in-depth analyses on what might be the good properties of a balanced set of influential data.</p>
    <div style="display: flex; margin-top: 20px;">
      <a href="{{ site.baseurl }}/files/BIDS-10_13-preprint.pdf" target="_blank" style="text-decoration: none;">
        <button style="background-color: white; border: 1px solid #ccc; border-radius: 10px; padding: 8px 40px; font-size: 14px; cursor: pointer;">Paper</button>
      </a>
      <!-- <a href="https://github.com/CTDancer/DGS_Demonstration-Distillation" target="_blank" style="text-decoration: none; margin-left: 10px;">
        <button style="background-color: white; border: 1px solid #ccc; border-radius: 10px; padding: 8px 40px; font-size: 14px; cursor: pointer;">Code</button>
      </a> -->
    </div>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 50px;">
  <img src="{{ site.baseurl }}/images/DGS.png" alt="Image" style="width: 40%; margin-right: 40px;">
  <div>
    <h3>Demonstration Distillation for Efficient In-Context Learning</h3>
    <p>Tong Chen, <strong>Qirun Dai</strong>, Zhijie Deng, Dequan Wang</p>
    <p><em>Submitted to ICLR 2024</em></p>
    <p>In order to optimize context efficiency for LLM in-context learning, we develop DGS, a multi-LLM-agent framework that iteratively compresses the given demonstrations with <strong>D</strong>istillist, <strong>G</strong>eneralist and <strong>S</strong>pecialist.</p>
    <p>DGS achieves up to a 4.3x compression ratio and a 5% accuracy improvement on various QA tasks, reducing inference overheads while eliciting stronger reasoning capabilities.</p>
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

