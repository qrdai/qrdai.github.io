---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a senior undergraduate student majoring in Artificial Intelligence at [Fudan University](https://www.fudan.edu.cn/en/), Shanghai. Currently, I work as a research intern at the [Department of Computer Science](https://siebelschool.illinois.edu/) of the [University of Illinois Urbana-Champaign](https://illinois.edu/), fortunately advised by [Prof. Hao Peng](https://haopeng-nlp.github.io/). I also had research internship experience at [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/) under the supervision of [Prof. Dequan Wang](https://dequan.wang/) and [Prof. Zhijie Deng](https://thudzj.github.io/), and exchange experience at the [University of California, Davis](https://www.ucdavis.edu/). 


<!-- <details>
<summary><strong>demo</strong></summary>

**Markdown** content here.

</details> -->


# Research Interests
I am enthusiastic about following latest advances and conducting cutting-edge research in AI, especially at the intersection of natural language processing and machine learning. These days, I have an intense interest in advancing the capabilities as well as our understanding of **large language models (LLMs) from a data-centric perspective**. Here are a few topics I’ve been thinking and excited about:


<details>
<summary><strong>Data Curation and Synthetic Data.</strong></summary>

Today’s capable LLMs are powered by automated data curation pipelines, where large-scale datasets synthesized by LLMs themselves play a crucial role. But the prevalent noise and redundancy contained in synthetic datasets haven’t received enough attention. There’s also a lack of understanding on how various properties of synthetic data, including correctness, diversity and generation sources (e.g., real-world, on-policy or off-policy generators) contribute to the LM’s ultimate learning outcome. 

- Can we build principled data **selection** techniques that not only identify individual data points with favorable properties, but also model the interactions inside a subset of data and their joint influence? 
- Is it possible that certain human-perceived noise and redundancy in synthetic data are actually beneficial to language models? 
- In light of this, how can we further design efficient curation pipelines with better quality and diversity control?

</details>


<br>


<details>
<summary><strong>Data Attribution and Interpretability of Model Behavior.</strong></summary>

Attributing model behavior to specific training data is of vital importance to the trustworthy deployment of LLMs. But the efficiency of traditional data attribution techniques have become a major bottleneck when it comes to LLM-scale applications. It’s also questionable whether they can be well transferred across models of different sizes and architectures, and generalizable across different tasks and application domains. I’m thus interested in designing a more accessible and generalizable data attribution framework tailored to LLMs, and applying such a framework to promote trustworthy applications of LLMs in various scientific domains.

</details>


<br>


<details>
<summary><strong>Data-efficient Learning Algorithms.</strong></summary>

The success of current LLMs is a combined accomplishment of multiple learning paradigms, including unsupervised pre-training, supervised post-training (e.g., instruction tuning and preference learning) and inference-time context optimization (e.g., in-context learning and RAG). But it still remains unclear what the language model essentially learns in these learning stages, and how various forms of data contribute differently to each stage. 

- How can we scientifically study their respective working mechanism? 
- What are the shared and exclusive characteristics of "good" data for different stages? 
- Can we build algorithms that can utilize data more efficiently given the specific mechanism of each learning stage?

The following two lines of work are good examples of building and improving data-efficient learning algorithms:

- **Advance the understanding of in-context learning:** [In-context Vectors](https://arxiv.org/abs/2311.06668).
- **Improve the efficiency of supervision for preference learning:** from [DPO](https://arxiv.org/abs/2305.18290) to [KTO](https://arxiv.org/abs/2402.01306), [NCA](https://arxiv.org/abs/2402.05369), etc.

</details>


<br>


<details>
<summary><strong>Datasets for Trustworthy and Efficient Evaluation.</strong></summary>

What cannot be measured, cannot be improved. I aim to improve the evaluation of LLM capabilities from with respect to both trustworthiness and efficiency.

- How can we improve the robustness of the same evaluation pipeline across different models and hardware conditions? And how well do current evaluation methods truly reflect the LLM’s performance on the capabilities they benchmark?
- There’s also a trade-off between trustworthy and efficient evaluation. Can we maintain the robustness of evaluation results while reducing the cost of exhaustive runs, possibly by removing noisy and over-represented samples in evaluation datasets?

</details>