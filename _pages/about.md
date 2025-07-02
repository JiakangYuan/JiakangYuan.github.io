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

<h2>About Me</h2>

  <div style='width: 95%; vertical-align: middle; margin-left: 3%'>
  I am current a third-year Ph.D. student (Sep. 2022 - Jun. 2027, expected) in the School of Information Science and Technology, Fudan University, supervised by Prof. <a href="https://eetchen.github.io/">Tao Chen</a>. I am also fortunate to work closely with Dr. <a hred="https://bobrown.github.io/boZhang.github.io/">Bo Zhang</a> from Shanghai AI Lab. Before this, I obtained my Bachelor’s degree in Electronic Engineering also from Fudan University (Sep. 2018 - Jun. 2022). I work in the fields of deep learning and computer vision, with particular focuses on 3D perception, transfer learning, multi-modal LLM. My research pursues to develop vision-language systems that possess the capacity to comprehend, reason, and envision the physical world and explore using AI for scientific discovery. 
  </div>
</div>

<div style='margin-top: 30pt'></div>

# 🔥 News
  - <p style='text-align:justify'><i>2025.7</i>: &nbsp;🎉🎉 SPOT is accepted by <font color="red">IEEE T-PAMI 2025</font>.</p>
  - <p style='text-align:justify'><i>2025.6</i>: &nbsp;🎉🎉 Two papers (Lumina Image 2.0 and Chimera) are accepted by <font color="red">ICCV 2025</font>. One is about text-to-image generation, the other is about multimodal reasoning.</p>
  - <p style='text-align:justify'><i>2025.5</i>: &nbsp;🎉🎉 Two papers (SurveyForge and Dolphin) are accepted by <font color="red">ACL 2025</font>. Both are introduced for accelerate scientific research. </p>
  - <p style='text-align:justify'><i>2025.5</i>: &nbsp;🎉🎉 We release NovelSeek, a unified closed-loop multi-agent framework for Automatic Scientific Research.</p>
  - <p style='text-align:justify'><i>2025.2</i>: &nbsp;🎉🎉 One paper (CST-Stereo) is accepted by <font color="red">CVPR 2025</font>. CST-Stereo introduce a unified self-training framework for iterative-based stereo matching models. </p>
  - <p style='text-align:justify'><i>2024.12</i>: &nbsp;🎉🎉 One paper (GeoX) is accepted by <font color="red">ICLR 2025</font>. GeoX reveals the large potential of formalized visual-language pre-training in enhancing geometric problem-solving abilities. </p>
  - <p style='text-align:justify'><i>2024.12</i>: &nbsp;🎉🎉 One paper (AIOStereo) is accepted by <font color="red">AAAI 2025</font>. AIOStereo can transfer knowledge from multiple vision foundation models into a single stereo matching model flexibly.</p>
  - <p style='text-align:justify'><i>2024.10</i>: &nbsp;🎉🎉 I recieve the <font color="red">national scholarship</font>. </p>
  - <p style='text-align:justify'><i>2024.09</i>: &nbsp;🎉🎉 Two papers (AdaptiveDiffusion and 3DET-Mamba) are accepted by <font color="red">NeurIPS 2024</font>. One is about training-free acceleration of diffusion model, another is about mamba architecture in 3D detection.</p>
  - <p style='text-align:justify'><i>2024.07</i>: &nbsp;🎉🎉 One paper (Reg-TTA3D) is accepted by <font color="red">ECCV 2024</font>. We explore test-time adaptive 3d object detection for the first time.</p>
  - <p style='text-align:justify'><i>2024.01</i>: &nbsp;🎉🎉 One paper (ReSimAD) is accepted by <font color="red">ICLR 2024</font>. We propose a zero-shot generalization framework by reconstructing mesh and simulating target point clouds.</p>
  - <p style='text-align:justify'><i>2023.09</i>: &nbsp;🎉🎉 One Paper (AD-PT) is accepted by <font color="red">NeurIPS 2023</font>.We explore 3D pre-training pipeline to obtain backbones with strong generalization capability.</p>
  - <p style='text-align:justify'><i>2023.02</i>: &nbsp;🎉🎉 Two Papers (Bi3D and Uni3D) are accepted by <font color="red">CVPR 2023</font>. One is about active domain adaptation for 3D object detection, another is about multi-dataset training for 3d object detection.</p>
  - <p style='text-align:justify'><i>2022.07</i>: &nbsp;🎉🎉 One Paper (HelixFormer) is accepted by <font color="red">ACM'MM 2022</font>. We explore Transformer architecture on few-shot fine-grained classification task.</p>

<div style='margin-top: 30pt'></div>



# 📝 Publications & Preprints

<style>
.toggleButton {
  background-color: #007BFF; /* 按钮的背景颜色 */
  color: white; /* 按钮的文字颜色 */
  border: none; /* 去掉按钮的边框 */
  padding: 8px 20px; /* 调整后的内边距 */
  text-align: center; /* 文本居中 */
  text-decoration: none; /* 去掉文本装饰 */
  display: inline-block; /* 使按钮在行内显示 */
  font-size: 14px; /* 调整后的字体大小 */
  margin: 4px 2px; /* 外边距 */
  cursor: pointer; /* 鼠标悬停时显示手型光标 */
  border-radius: 20px; /* 胶囊形状 */
  transition-duration: 0.4s; /* 过渡效果 */
}

.toggleButton:hover {
  background-color: white; /* 鼠标悬停时的背景颜色 */
  color: black; /* 鼠标悬停时的文字颜色 */
  border: 1px solid #007BFF; /* 鼠标悬停时的边框颜色 */
}
</style>

<div style="display: flex; gap: 10px; margin-bottom: 10px;">
  <button class="toggleButton" data-target="publications">publications</button>
  <button class="toggleButton" data-target="preprints">preprints</button>
</div>

<div id="publications" style="display: block; margin-top: 10px;">
<!-- publications -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/chimera.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Chimera: Improving Generalist Model with Domain-Specific Experts](https://arxiv.org/abs/2412.05983)

Tianshuo Peng<sup>\*</sup>, Mingsheng Li<sup>\*</sup>, **<u>Jiakang Yuan</u>**, Hongbin Zhou, Renqiu Xia, Renrui Zhang, Lei Bai, Song Mao, Bin Wang, Aojun Zhou, Botian Shi, Tao Chen, Bo Zhang, Xiangyu Yue

[[**Project**]](https://alpha-innovator.github.io/chimera_page/)[[**Paper**]](https://arxiv.org/abs/2412.05983)
- a scalable and low-cost multi-modal pipeline designed to boost the ability of existing LMMs with domain-specific experts.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/lumina.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Lumina-Image 2.0: A Unified and Efficient Image Generative Framework](https://arxiv.org/abs/2503.21758)

Qi Qin, Le Zhuo, Yi Xin, Ruoyi Du, Zhen Li, Bin Fu, Yiting Lu, **<u>Jiakang Yuan</u>**, Xinyue Li, Dongyang Liu, Xiangyang Zhu, Manyuan Zhang, Will Beddow, Erwann Millon, Victor Perez, Wenhai Wang, Conghui He, Bo Zhang, Xiaohong Liu, Hongsheng Li, Yu Qiao, Chang Xu, Peng Gao

[[**Project**]](https://github.com/Alpha-VLLM/Lumina-Image-2.0)[[**Paper**]](https://arxiv.org/abs/2503.21758)
- State-of-the-art text-to-image generation model.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/dolphin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dolphin: Moving Towards Closed-loop Auto-research through Thinking, Practice, and Feedback](https://arxiv.org/pdf/2501.03916)

**<u>Jiakang Yuan</u>**, Xiangchao Yan, Shiyang Feng, Bo Zhang, Tao Chen, Botian Shi, Wanli Ouyang, Yu Qiao, Lei Bai, Bowen Zhou

[[**Project**]](https://alpha-innovator.github.io/Dolphin-project-page/)[[**Paper**]](https://arxiv.org/pdf/2501.03916)
- Propose Dolphin, a closed-loop auto-research framework.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/surveyforge.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SurveyForge: On the Outline Heuristics, Memory-Driven Generation, and Multi-dimensional Evaluation for Automated Survey Writing](https://arxiv.org/abs/2503.04629)

Xiangchao Yan<sup>\*</sup>, Shiyang Feng<sup>\*</sup>, **<u>Jiakang Yuan</u>**, Renqiu Xia, Bin Wang, Bo Zhang, Lei Bai

[[**Project**]](https://github.com/Alpha-Innovator/SurveyForge)[[**Paper**]](https://arxiv.org/abs/2503.04629)
- Propose SurveyForge which can automatically generate and refine the content of survey.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cststereo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Consistency-aware Self-Training for Iterative-based Stereo Matching]()

Jingyi Zhou<sup>\*</sup>, Peng Ye<sup>\*</sup>, Haoyu Zhang, **<u>Jiakang Yuan</u>** (Project Leader), Qiang Rao, YangChenXu Liu, Cailin Wu, Feng Xu, Tao Chen

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2503.23747)
- Propose CST-Stereo, which achieves impressive results in various scenarios, including in domain, domain adaptive and domain generalization,
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/geox.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GeoX: Geometric Problem Solving Through Unified Formalized Vision-Language Pre-training](https://arxiv.org/pdf/2412.11863v1)

Renqiu Xia<sup>\*</sup>, Mingsheng Li<sup>\*</sup>, Hancheng Ye, Wenjie Wu, Hongbin Zhou, **<u>Jiakang Yuan</u>**, Tianshuo Peng, Xinyu Cai, Xiangchao Yan, Bin Wang, Conghui He, Botian Shi, Tao Chen, Junchi Yan, Bo Zhang

[[**Project**]]()[[**Paper**]](https://arxiv.org/pdf/2412.11863v1)
- Propose GeoX, a multi-modal large model focusing on geometric understanding and reasoning tasks which reveals the large potential of formalized visual-language pre-training in enhancing geometric problem-solving abilities.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/aiostereo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[All-in-One: Transferring Vision Foundation Models into Stereo Matching](https://arxiv.org/abs/2412.09912)

Jingyi Zhou<sup>\*</sup>, Haoyu Zhang<sup>\*</sup>, **<u>Jiakang Yuan</u>**<sup>\*</sup>, Peng Ye, Tao Chen, Hao Jiang, Meiya Chen, Yangyang Zhang

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2412.09912)
- Propose AIOStereo to flexibly select and transfer knowledge from multiple heterogeneous VFMs to a single stereo matching model. (<font color="red">Rank 1st</font> on [Middlebury Stereo Evaluation](https://vision.middlebury.edu/stereo/eval3/)) 
</div>
</div>

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
</div>
<div style='margin-top: 30pt'></div>

<!-- Preprints -->
<div id="preprints" style="display: none; margin-top: 10px;">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/mmereasoning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MME-Reasoning: A Comprehensive Benchmark for Logical Reasoning in MLLMs](https://arxiv.org/abs/2505.21327)

**<u>Jiakang Yuan</u><sup>\*</sup>**, Tianshuo Peng<sup>\*</sup>, Yilei Jiang, Yiting Lu, Renrui Zhang, Kaituo Feng, Chaoyou Fu, Tao Chen, Lei Bai, Bo Zhang, Xiangyu Yue

[[**Project**]](https://alpha-innovator.github.io/mmereasoning.github.io/)[[**Paper**]](https://arxiv.org/pdf/2505.21327)[[**Huggingface**]](https://huggingface.co/datasets/U4R/MME-Reasoning)[[**Learderboard**]](https://alpha-innovator.github.io/mmereasoning.github.io/#leaderboard)
- Introduce MME-Reasoning, a comprehensive benchmark specifically designed to evaluate the reasoning capability of MLLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/novelseek.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NovelSeek: When Agent Becomes the Scientist -- Building Closed-Loop System from Hypothesis to Verification](https://arxiv.org/abs/2505.16938)

NovelSeek Team: Bo Zhang, Shiyang Feng, Xiangchao Yan, **<u>Jiakang Yuan</u>** (Core contributor), Zhiyin Yu, Xiaohan He, Songtao Huang, Shaowei Hou, Zheng Nie, Zhilong Wang, Jinyao Liu, Runmin Ma, Tianshuo Peng, Peng Ye, Dongzhan Zhou, Shufei Zhang, Xiaosong Wang, Yilan Zhang, Meng Li, Zhongying Tu, Xiangyu Yue, Wangli Ouyang, Bowen Zhou, Lei Bai

[[**Project**]](https://alpha-innovator.github.io/NovelSeek-project-page/)[[**Paper**]](https://arxiv.org/abs/2505.16938)
- Introduce NovelSeek, a unified closed-loop multi-agent framework for Automatic Scientific Research.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/omnicaptioner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniCaptioner: One Captioner to Rule Them All](https://arxiv.org/abs/2504.07089)

Yiting Lu<sup>\*</sup>, **<u>Jiakang Yuan</u><sup>\*</sup>**, Zhen Li, Shitian Zhao, Qi Qin, Xinyue Li, Le Zhuo, Licheng Wen, Dongyang Liu, Yuewen Cao, Xiangchao Yan, Xin Li, Botian Shi, Tao Chen, Zhibo Chen, Lei Bai, Bo Zhang, Peng Gao

[[**Project**]](https://alpha-innovator.github.io/OmniCaptioner-project-page/)[[**Paper**]](https://arxiv.org/abs/2504.07089)
- Propose Omnicaption, an all-in-one visual to text mapping tool.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/prototta.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bidirectional Prototype-Reward co-Evolution for Test-Time Adaptation of Vision-Language Models](https://www.arxiv.org/abs/2503.09394)

Xiaozhen Qiao, Peng Huang, **<u>Jiakang Yuan</u>**, Xianda Guo, Bowen Ye, Zhe Sun, Xuelong Li

[[**Project**]](https://www.arxiv.org/abs/2503.09394)[[**Paper**]](https://www.arxiv.org/abs/2503.09394)
- Novel TTA framework for VLMs.
</div>
</div>


</div>

<script>
  // 获取所有按钮并添加点击事件
  document.querySelectorAll(".toggleButton").forEach(button => {
    button.addEventListener("click", function() {
      const targetId = this.getAttribute("data-target");
      // 隐藏所有内容块
      document.querySelectorAll("#publications, #preprints").forEach(content => {
        content.style.display = "none";
      });
      // 显示对应的内容块
      const targetContent = document.getElementById(targetId);
      if (targetContent) {
        targetContent.style.display = "block";
      }
    });
  });
</script>

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

- Reviewer of CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR, T-IP, T-CSVT, T-MM.