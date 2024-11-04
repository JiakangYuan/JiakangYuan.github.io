---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<div style='font-size:14pt; text-align:justify; font-family:Georgia; margin-top: 50pt'>
  <div style='width: 95%; vertical-align: middle; margin-left: 3%'>
  I am current a third-year Ph.D. student (Sep. 2022 - Jun. 2027, expected) in the School of Information Science and Technology, Fudan University, supervised by Prof. <a href="https://eetchen.github.io/">Tao Chen</a>. I am also fortunate to work closely with Dr. <a hred="https://bobrown.github.io/boZhang.github.io/">Bo Zhang</a> from Shanghai AI Lab. Before this, I obtained my Bachelor’s degree in Electronic Engineering also from Fudan University (Sep. 2018 - Jun. 2022). I work in the fields of deep learning and computer vision, with particular focuses on 3D perception, transfer learning, multi-modal LLM. My research pursues to develop vision-language systems that possess the capacity to comprehend, reason, and envision the physical world and explore using AI for scientific discovery. 
  </div>
</div>

<div style='margin-top: 30pt'></div>

# 🔥 News

  - <p style='text-align:justify'><i>2024.10</i>: &nbsp;🎉🎉 I recieve the <font color="red">national scholarship</font>. </p>
  - <p style='text-align:justify'><i>2024.09</i>: &nbsp;🎉🎉 Two papers (AdaptiveDiffusion and 3DET-Mamba) are accepted by <font color="red">NeurIPS 2024</font>. One is about training-free acceleration of diffusion model, another is about mamba architecture in 3D detection.</p>
  - <p style='text-align:justify'><i>2024.07</i>: &nbsp;🎉🎉 One paper (Reg-TTA3D) is accepted by <font color="red">ECCV 2024</font>. We explore test-time adaptive 3d object detection for the first time.</p>
  - <p style='text-align:justify'><i>2024.01</i>: &nbsp;🎉🎉 One paper (ReSimAD) is accepted by <font color="red">ICLR 2024</font>. We propose a zero-shot generalization framework by reconstructing mesh and simulating target point clouds.</p>
  - <p style='text-align:justify'><i>2023.09</i>: &nbsp;🎉🎉 One Paper (AD-PT) is accepted by <font color="red">NeurIPS 2023</font>.We explore 3D pre-training pipeline to obtain backbones with strong generalization capability.</p>
  - <p style='text-align:justify'><i>2023.02</i>: &nbsp;🎉🎉 Two Papers (Bi3D and Uni3D) are accepted by <font color="red">CVPR 2023</font>. One is about active domain adaptation for 3D object detection, another is about multi-dataset training for 3d object detection.</p>
  - <p style='text-align:justify'><i>2022.07</i>: &nbsp;🎉🎉 One Paper (HelixFormer) is accepted by <font color="red">ACM'MM 2022</font>. We explore Transformer architecture on few-shot fine-grained classification task.</p>

<div style='margin-top: 30pt'></div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/adaptivediffusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Training-Free Adaptive Diffusion with Bounded Difference Approximation Strategy]()

Hancheng Ye<sup>\*</sup>, **<u>Jiakang Yuan</u><sup>\*</sup>**, Renqiu Xia, Xiangchao Yan, Tao Chen, Junchi Yan, Botian Shi, Bo Zhang

[[**Project**]](https://jiakangyuan.github.io/AdaptiveDiffusion-project-page/)[[**Paper**]]()
- Propose AdaptiveDiffusion to adaptively reduce the noise prediction steps during the denoising proces guided by the third-order latent difference. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/3detmamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[3DET-Mamba: State Space Model for End-to-End 3D Object Detection]()

Mingsheng Li<sup>\*</sup>, **<u>Jiakang Yuan</u><sup>\*</sup>**, Sijin Chen, Lin Zhang, Anyu Zhu, Xin Chen, Tao Chen

[[**Project**]]()[[**Paper**]]()
- Exploit the potential of Mamba architecture on 3D scene-level perception for the first time.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/regtta3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reg-TTA3D: Better Regression Makes Better Test-time Adaptive 3D Object Detection]()

**<u>Jiakang Yuan</u>**, Bo Zhang, Kaixiong Gong, Xiangyu Yue, Botian Shi, Yu Qiao, Tao Chen

[[**Project**]]()[[**Paper**]]()
- Explore a new task named test-time domain adaptive 3D object detection and propose a pseudo-label-based test-time adaptative 3D object detection method.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/resimad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ReSimAD: Zero-Shot 3D Domain Transfer for Autonomous Driving with Source Reconstruction and Target Simulation](https://arxiv.org/abs/2309.05527)

Bo Zhang<sup>\*</sup>, Xinyu Cai<sup>\*</sup>, **<u>Jiakang Yuan</u>**, Donglin Yang, Jianfei Guo, Xiangchao Yan, Renqiu Xia, Botian Shi, Min Dou, Tao Chen, Si Liu, Junchi Yan, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2309.05527)
- Provide a new perspective and approach of alleviating the domain shifts, by proposing a Reconstruction-Simulation-Perception scheme.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/adpt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AD-PT: Autonomous Driving Pre-Training with Large-scale Point Cloud Dataset](https://arxiv.org/abs/2306.00612)

**<u>Jiakang Yuan</u>**, Bo Zhang, Xiangchao Yan, Tao Chen, Botian Shi, Yikang Li, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2306.00612)
- Build a large-scale pre-training point-cloud dataset with diverse data distribution, and meanwhile learn generalizable representations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/bi3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bi3D: Bi-domain Active Learning for Cross-domain 3D Object Detection](https://arxiv.org/abs/2303.05886)

**<u>Jiakang Yuan</u>**, Bo Zhang, Xiangchao Yan, Tao Chen, Botian Shi, Yikang Li, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2303.05886)
- Propose a Bi-domain active learning approach which select samples from both source and target domain to solve the cross-domain 3D object detection task.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/uni3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Uni3D: A Unified Baseline for Multi-dataset 3D Object Detection](https://arxiv.org/abs/2303.06880)

Bo Zhang, **<u>Jiakang Yuan</u>**, Botian Shi, Tao Chen, Yikang Li, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2303.06880)
- Present a Uni3D which tackle multi-dataset 3D object detection from data-level and semantic-level.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM'MM 2022</div><img src='images/helixformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Cross-Image Object Semantic Relation in Transformer for Few-Shot Fine-Grained Image Classification](https://arxiv.org/abs/2207.00784)

Bo Zhang<sup>\*</sup>, **<u>Jiakang Yuan</u><sup>\*</sup>**, Baopu Li, Tao Chen, Jiayuan Fan, Botian Shi

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2207.00784)
- Propose a Transformer-based double-helix model to achieve the cross-image object semantic relation mining in a bidirectional and symmetrical manner.
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<div style='margin-top: 30pt'></div>

# 📖 Educations
- *2022.09 - Now*, Ph.D. Candidate, School of Information Science and Technology, [Fudan University](https://www.fudan.edu.cn/). 
- *2018.06 - 2022.06*, Bachelor Degree, School of Information Science and Technology, [Fudan University](https://www.fudan.edu.cn/). 

<div style='margin-top: 30pt'></div>

# 💬 Invited Talks
- *2023.09*, Invited talk of **Effcient Pre-training of Autonomous Driving**. [[Video]](https://www.bilibili.com/video/BV1e8411C7ZK/?spm_id_from=333.337.search-card.all.click&vd_source=478510f65af6875433547b21fe148987)
- *2023.07*, Invited talk of **Towards 3D General Representation** at Techbeat. [[Video]](https://www.techbeat.net/talk-info?id=795)
- *2023.03*, Invited talk of **Transferable of Autonomous Driving**. [[Video]](https://www.bilibili.com/video/BV1Vo4y1b7pS/?spm_id_from=333.337.search-card.all.click)

<div style='margin-top: 30pt'></div>

# 💻 Internships

- *2024.10 - Now*, [Shanghai AI Laboratory](), China.
- *2022.08 - 2024.02*, [Shanghai AI Laboratory](), China.

<div style='margin-top: 30pt'></div>

# 📝 Academic Services

- Reviewer of CVPR, ICML, ICLR, ECCV, T-CSVT.