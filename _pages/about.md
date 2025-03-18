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

# About Me
I am a master student in School of Software from Beihang University now, supervised by <a href="https://lucassheng.github.io/" target="_blank">Prof. Lu Sheng</a>.

My current research interests include deep generative models and their applications, with a particular focus on 3D generation. I am very excited about the recent developments in world generation and world models, and can't wait to dive into them.
<!-- I have published 10+ papers <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international AI conferences such as CVPR, ECCV. -->

I am grateful to all my collaborators and mentors along the way. I first started doing research under the guidance of <a href="https://miaowang.me/" target="_blank">Prof. Miao Wang</a>. Then I started working on deep learning related projects under the supervision of <a href="https://lucassheng.github.io/" target="_blank">Prof. Lu Sheng</a>. Besides, I also successively haved intern at <a href="https://minimaxi.com/" target="_blank">MiniMax</a>, <a href="https://www.shlab.org.cn/" target="_blank">Shanghai AI Lab</a>, and <a href="https://www.tripo3d.ai/" target="_blank">VAST</a>, and I'm fortunate to have worked closely with <a href="https://jtdong.com/" target="_blank">Junting Dong</a>, <a href="https://scholar.google.com/citations?user=b7ZJV9oAAAAJ" target="_blank">Yuan-Chen Guo</a> and <a href="https://yanpei.me/" target="_blank">Yanpei Cao</a>.

# 🔥 News
- *2025.03*: &nbsp;🎉🎉 [*Ouroboros3D*](https://costwen.github.io/Ouroboros3D/) and [*MIDI*](https://huanngzh.github.io/MIDI-Page/) are accepted by CVPR 2025.
- *2024.12*: &nbsp;🎉🎉 [*MV-Adapter*](https://huanngzh.github.io/MV-Adapter-Page/) on multi-view synthesis and texture generation is open source.
- *2024.07*: &nbsp;🎉🎉 [*TELA*](http://jtdong.com/tela_layer/) on clothes disentangled 3D human generation is accepted by ECCV 2024.
- *2024.02*: &nbsp;🎉🎉 [*EpiDiff*](https://huanngzh.github.io/EpiDiff/) on 3D object generation is accepted by CVPR 2024.

# 📝 Publications

## 🧑‍🎨 3D Generation

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/teasers/midi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MIDI: Multi-Instance Diffusion for Single Image to 3D Scene Generation](https://arxiv.org/pdf/2412.03558)

**Zehuan Huang**, Yuan-Chen Guo, Xingqiao An, Yunhan Yang, Yangguang Li, Zi-Xin Zou, Ding Liang, Xihui Liu, Yan-Pei Cao✉, Lu Sheng✉

[**Project Page**](https://huanngzh.github.io/MIDI-Page/) | [**Code**](https://github.com/VAST-AI-Research/MIDI-3D) [![](https://img.shields.io/github/stars/VAST-AI-Research/MIDI-3D?style=social)](https://github.com/VAST-AI-Research/MIDI-3D)
- **TL;DR:** MIDI is a novel paradigm for image to compositional 3D scene generation, which extends pre-trained image-to-3D object generation models to multi-instance diffusion models for generation of multiple 3D instances.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CoRR 2024</div><img src='images/teasers/mvadapter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MV-Adapter: Multi-view Consistent Image Generation Made Easy](https://arxiv.org/pdf/2412.03632)

**Zehuan Huang**, Yuan-Chen Guo, Haoran Wang, Ran Yi, Lizhuang Ma, Yan-Pei Cao✉, Lu Sheng✉

[**Project Page**](https://huanngzh.github.io/MV-Adapter-Page/) | [**Code**](https://github.com/huanngzh/MV-Adapter) [![](https://img.shields.io/github/stars/huanngzh/MV-Adapter?style=social)](https://github.com/huanngzh/MV-Adapter)
- **TL;DR:** An efficient and versatile adapter that adapts any text-to-image model to generate high-fidelity multi-view images under view/geometry guidance for downstream tasks like 3D generation and texture generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/teasers/ouroboros3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ouroboros3D: Image-to-3D Generation via 3D-aware Recursive Diffusion](https://arxiv.org/pdf/2406.03184)

Hao Wen\*, **Zehuan Huang**\*, Yaohui Wang, Xinyuan Chen, Yu Qiao, Lu Sheng

[**Project Page**](https://costwen.github.io/Ouroboros3D/) | CVPR 2025
- **TL;DR:** Transfer the two-stage image-to-3D pipeline into a unified recursive diffusion process, thereby reducing the data bias of each stage and improving the quality of generated 3D.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/teasers/tela.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TELA: Text to Layer-wise 3D Clothed Human Generation](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03566.pdf)

Junting Dong, Qi Fang, **Zehuan Huang**, Xudong Xu, Jingbo Wang, Sida Peng, Bo Dai✉

[**Project Page**](https://jtdong.com/tela_layer/) | ECCV 2024
- **TL;DR:** A layer-wise clothed human representation combined with a progressive optimization strategy, which produces clothes disentangled 3D human models while providing control capacity for the generation process.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/teasers/epidiff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EpiDiff: Enhancing Multi-View Synthesis via Localized Epipolar-Constrained Diffusion](https://openaccess.thecvf.com/content/CVPR2024/papers/Huang_EpiDiff_Enhancing_Multi-View_Synthesis_via_Localized_Epipolar-Constrained_Diffusion_CVPR_2024_paper.pdf)

Zehuan Huang\*, Hao Wen\*, Junting Dong\*, Yaohui Wang, Yangguang Li, Xinyuan Chen, Yan-Pei Cao, Ding Liang, Yu Qiao, Bo Dai✉, Lu Sheng✉

[**Project Page**](https://huanngzh.github.io/EpiDiff/) | CVPR 2024
- **TL;DR:** A localized interactive multi-view diffusion model, that includes epipolar attention blocks to model multi-view consistency.
</div>
</div>

- [Write‐An‐Animation: High‐level Text‐based Animation Editing with Character‐Scene Interaction](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14415), Jia-Qi Zhang, Xiang Xu, Zhi-Meng Shen, **Ze-Huan Huang**, Yang Zhao, Yan-Pei Cao, Pengfei Wan, Miao Wang✉, **PG 2021**

## 🎨 Concept Customization

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CoRR 2024</div><img src='images/teasers/parts2whole.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Parts to Whole: A Unified Reference Framework for Controllable Human Image Generation](https://arxiv.org/pdf/2404.15267)

**Zehuan Huang**\*, Hongxing Fan\*, Lipeng Wang, Lu Sheng✉

[**Project Page**](https://huanngzh.github.io/Parts2Whole/) | ArXiv 2024
- **TL;DR:** Customize each part of human images for controllable portrait generation.
</div>
</div>

# 🎖 Honors and Awards
- *2024.10* China National Scholarship (Top 1%)
- *2024.10* BYD Alumni Scholarship (Top 1%)
- *2024.10* Postgraduate First-Class Scholarship (Top 10%)
- *2023.06* Beijing Outstanding Graduates (Top 1%)

# 📖 Educations
- *2023.09 - 2026.01 (now)*, Master, Beihang University, Beijing.
- *2019.09 - 2023.06*, Undergraduate, School of Software, Beihang University, Beijing.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.12 - Present*, [VAST](https://www.tripo3d.ai/), Beijing. Working on 3D generation and texture generation.
- *2023.08 - 2023.12*, [Shanghai Artificial Intelligence Laboratory](https://www.shlab.org.cn/), Beijing. Working on 3D generation.
- *2022.05 - 2023.06*, [MiniMax](https://minimaxi.com/), Beijing. Working on 3D avatar reconstruction, controllable image generation.

# 💁 Services

## Reviewers
- Conference: CVPR 2025; ICLR 2025
- Journal: TCSVT