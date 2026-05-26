---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year PhD student in Electrical and Computer Engineering at the **University of Michigan**, advised by [Jeffrey Fessler](https://web.eecs.umich.edu/~fessler/) and [Qing Qu](https://qingqu.engin.umich.edu/) ([DeepThink Lab](https://deepthink-umich.github.io/)). My research interests lie in **generative models** and **representation learning**, with applications in **AI for science** and **computational imaging**.

Before coming to UMich, I received my B.S. in Instrument Science and Technology from **Tsinghua University**. I also hold a secondary degree in Business Administration from Tsinghua.

## News

- **[May 2026]** Four papers are accepted at the [**ICML FoGen Workshop**](https://fdgm-workshop.github.io/FDGM_ICML2026/): [ForcingDAS](https://arxiv.org/abs/2605.14285), [ICR](https://umjiayx.github.io), [MCLR](https://arxiv.org/abs/2603.22364), and [DFD](https://umjiayx.github.io).
- **[May 2026]** I have joined **Bytedance** as a research scientist intern (Seed, GenAI for Science), studying GenAI methods for scientific modeling and discovery.
- **[Apr 2026]** Our paper ["Evaluating the Representation Space of Diffusion Models via Self-Supervised Principles"](https://umjiayx.github.io) is accepted at **ICML 2026**.
- **[Mar 2026]** New preprint: ["MCLR: Establishing the Equivalence between Classifier-Free Guidance and Alignment Objectives"](https://arxiv.org/abs/2603.22364) is now online.
- **[Mar 2026]** Our recent work ["Deep Residual Learning Framework for Scatter Estimation in SPECT Imaging of Alpha Emitters"](/) is accepted at **SNMMI 2026**.
- **[Sep 2025]** Our paper ["FlowDAS"](https://neurips.cc/virtual/2025/loc/san-diego/poster/120192) is accepted at **NeurIPS 2025**.


You can also find my articles on [my Google Scholar profile]({{ site.author.googlescholar }}).

\* Equal contribution &ensp; † Corresponding author

## Highlighted Publications

<div class="pub-entry">
  <div class="pub-teaser">
    <img src="/images/pub/ForcingDAS.png" alt="ForcingDAS teaser">
  </div>
  <div class="pub-text">
    <p class="pub-title"><a href="https://arxiv.org/abs/2605.14285">ForcingDAS: Unified and Robust Data Assimilation via Diffusion Forcing</a></p>
    <p class="pub-authors"><strong>Yixuan Jia</strong>, Siyi Chen, Yida Pan, Xiao Li, Lianghe Shi, Chanyong Jung, Haijie Yuan, Ismail Alkhouri, Yue Cynthia Wu, Saiprasad Ravishankar, Jeffrey Fessler, Qing Qu</p>
    <p class="pub-venue">ICML FoGen Workshop, 2026</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2605.14285">paper</a> / <a href="https://github.com/umjiayx/ForcingDAS">code</a></p>
    <p class="pub-desc">We introduce ForcingDAS, a diffusion-forcing data assimilation framework that learns a joint-trajectory prior to reduce error accumulation, with a single trained model spanning the full filtering-to-smoothing spectrum at inference time.</p>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-teaser">
    <img src="/images/pub/flowdas.png" alt="FlowDAS teaser">
  </div>
  <div class="pub-text">
    <p class="pub-title"><a href="https://neurips.cc/virtual/2025/loc/san-diego/poster/120192">FlowDAS: A Stochastic Interpolant-Based Framework for Data Assimilation</a></p>
    <p class="pub-authors">Siyi Chen*, <strong>Yixuan Jia</strong>*, Qing Qu, He Sun†, Jeffrey Fessler</p>
    <p class="pub-venue">NeurIPS, 2025</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2501.16642">paper</a> / <a href="https://github.com/umjiayx/FlowDAS">code</a></p>
    <p class="pub-desc">We introduce FlowDAS, a generative data assimilation framework that uses stochastic interpolants to learn observation-conditioned state transition dynamics from data, enabling step-by-step state estimation for stochastic dynamical systems without requiring known physical models.</p>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-teaser">
    <img src="/images/pub/sperf.png" alt="SpeRF teaser">
  </div>
  <div class="pub-text">
    <p class="pub-title"><a href="https://link.springer.com/article/10.1186/s40658-025-00762-3">Shorter SPECT Scans Using Self-Supervised Coordinate Learning to Synthesize Skipped Projection Views</a></p>
    <p class="pub-authors">Zongyu Li*, <strong>Yixuan Jia</strong>*†, Xiaojian Xu, Jason Hu, Yuni Dewaraja, Jeffrey Fessler</p>
    <p class="pub-venue">EJNMMI Physics, 2025</p>
    <p class="pub-links"><a href="https://link.springer.com/article/10.1186/s40658-025-00762-3">paper</a> / <a href="https://github.com/umjiayx/sperf">code</a></p>
    <p class="pub-desc">We adapt the neural radiance field (NeRF) concept to SPECT imaging, enabling significant reduction in acquisition time (by 2×, 4×, or 8×) via self-supervised coordinate learning to synthesize skipped projection views.</p>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-teaser">
    <img src="/images/pub/y90.png" alt="Y90 SPECT teaser">
  </div>
  <div class="pub-text">
    <p class="pub-title"><a href="https://link.springer.com/article/10.1186/s40658-023-00598-9">Y90 SPECT Scatter Estimation and Voxel Dosimetry Using a Unified Deep Learning Framework</a></p>
    <p class="pub-authors"><strong>Yixuan Jia</strong>†, Zongyu Li, Azadeh Akhavanallaf, Jeffrey Fessler, Yuni Dewaraja</p>
    <p class="pub-venue">EJNMMI Physics, 2023</p>
    <p class="pub-links"><a href="https://link.springer.com/article/10.1186/s40658-023-00598-9">paper</a> / <a href="https://github.com/umjiayx/spect0">code</a></p>
    <p class="pub-desc">We developed a unified three-stage deep learning framework for clinical Y90 SPECT imaging: CNN-based scatter estimation, SPECT reconstruction with scatter correction, and dose-rate map generation.</p>
  </div>
</div>

## Other Publications

<div class="pub-entry">
  <div class="pub-teaser">
    <img src="/images/pub/mclr.jpeg" alt="MCLR teaser">
  </div>
  <div class="pub-text">
    <p class="pub-title"><a href="https://arxiv.org/abs/2603.22364">MCLR: Improving Conditional Modeling in Visual Generative Models via Inter-Class Likelihood-Ratio Maximization</a></p>
    <p class="pub-authors">Xiang Li, <strong>Yixuan Jia</strong>, Xiao Li, Jeffrey Fessler, Rongrong Wang, Qing Qu</p>
    <p class="pub-venue">arXiv preprint, 2026</p>
    <p class="pub-links"><a href="https://arxiv.org/abs/2603.22364">paper</a></p>
    <p class="pub-desc">We propose MCLR, a principled alignment objective that maximizes inter-class likelihood-ratios during training, enabling diffusion models to achieve classifier-free guidance-like improvements under standard sampling without inference-time guidance. We further establish a formal equivalence between CFG and alignment-based objectives.</p>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-teaser">
    <img src="/images/pub/SAMS.png" alt="SAMS teaser">
  </div>
  <div class="pub-text">
    <p class="pub-title"><a href="https://jnm.snmjournals.org/content/65/supplement_2/241583.abstract">Segment Anything Model for SPECT (SAMS): Novel Implementation in SPECT Imaging for Tumor Segmentation</a></p>
    <p class="pub-authors">Zhonglin Lu, Zongyu Li, <strong>Yixuan Jia</strong>, Gefei Chen, Molly Roseland, Greta Mok, Yuni Dewaraja†</p>
    <p class="pub-venue">Journal of Nuclear Medicine (SNMMI), 2024</p>
    <p class="pub-links"><a href="https://jnm.snmjournals.org/content/65/supplement_2/241583.abstract">paper</a></p>
    <p class="pub-desc">We adapt the Segment Anything Model (SAM) to SPECT imaging, enabling accurate tumor segmentation in nuclear medicine images.</p>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-teaser">
    <img src="/images/pub/progress_of_inertial.png" alt="Inertial microfluidics teaser">
  </div>
  <div class="pub-text">
    <p class="pub-title"><a href="https://www.mdpi.com/1424-8220/18/6/1762">Progress of Inertial Microfluidics in Principle and Application</a></p>
    <p class="pub-authors">Yixing Gou, <strong>Yixuan Jia</strong>, Peng Wang†, Changku Sun</p>
    <p class="pub-venue">Sensors, 2018</p>
    <p class="pub-links"><a href="https://www.mdpi.com/1424-8220/18/6/1762">paper</a></p>
    <p class="pub-desc">A comprehensive review of inertial microfluidics, covering the underlying physical principles and applications in particle manipulation, separation, and biomedical analysis.</p>
  </div>
</div>


## Beyond Work

I have two adorable kittens, Rainier and Mia! In my spare time, I enjoy driving around, playing and watching soccer — huge fan of Leo Messi 🐐.
