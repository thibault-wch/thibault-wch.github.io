---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html/
  - /publications.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am in the fourth year of my **direct Ph.D. program** in Biomedical Engineering (BME) at the [Institute of Science and Technology for Brain-inspired Intelligence](https://istbi.fudan.edu.cn/), Fudan University, under the supervision of [Hongming Shan](http://hmshan.io/). I received my Bachelor's degree in Software Engineering (SE) from the [School of Computer Science and Artificial Intelligence](http://cst.whut.edu.cn/) at Wuhan University of Technology in 2021, with a GPA of 4.4 out of 5.0 (<span style="color:blue">Top 0.6%</span>).


My research interest includes AI for neuroscience and AIGC. Here is my <a href="images/ChenhuiWang_CV.pdf">CV<a>.

# 🔥 News
- *2025.05*: &nbsp;🍾🍾 Congrats to Tao. <em>ARSeg for medical image segmentation</em> is early accepted by **MICCAI**. [[link]](https://arxiv.org/abs/2502.20784).
- *2024.11*: &nbsp;🥳🥳 Delighted to have received the <span style="color:blue">**Doctoral National Scholarship**</span>!
- *2024.08*: &nbsp;🍾🍾 Congrats to Zhihao. <em>LEDA for Low-dose CT Denoising</em> is accepted by **BIBM**. [[link]](https://arxiv.org/pdf/2403.06128)
- *2024.07*: &nbsp;🍾🍾 Congrats to Tao. <em>HiDiff for medical image segmentation</em> is accepted by **IEEE TMI** (<span style="color:blue">SCI Q1 Top, IF=8.9</span>). [[link]](https://ieeexplore.ieee.org/document/10587153/)
- *2024.06*: &nbsp;🥳🥳 Profoundly thank the <em>IJCAI Committee</em> for providing the <span style="color:blue">**IJCAI 2024 Travel Grant**</span> in Jeju Island, South Korea.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/FLDM-VTON.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLDM-VTON:Faithful Latent Diffusion Model for Virtual Try-on](https://arxiv.org/abs/2404.14162)

**Chenhui Wang**, Tao Chen, Zhihao Chen, Zhizhong Huang, Taoran Jiang, Qi Wang, Hongming Shan<sup>†</sup>

International Joint Conference on Artificial  Intelligence (IJCAI), 2024 (<span style="color:blue">CCF A</span>)

[[**doi**]](https://arxiv.org/abs/2404.14162) [[**arxiv**]](https://arxiv.org/abs/2404.14162) [[**news**]](https://mp.weixin.qq.com/s?__biz=MzIwNzc2NTk0NQ%3D%3D&mid=2247583547&idx=3&sn=3e38c59b87b6c009c1436628e43bd5a7&ref=openi.cn)  Cooperation with <span style="color:blue">Suzhou Xiangji Technology Service Co., Ltd.</span>
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE JBHI 2024</div><img src='images/HOPE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HOPE: Hybrid-granularity Ordinal Prototype Learning for Progression Prediction of Mild Cognitive Impairment](https://ieeexplore.ieee.org/document/10412338)

**Chenhui Wang**, Yiming Lei, Tao Chen, Junping Zhang, Yuxin Li<sup>†</sup>, Hongming Shan<sup>†</sup>

IEEE Journal of Biomedical and Health Informatics, 2024 (In Press) (<span style="color:blue">SCI Q1</span>)

[[**doi**]](https://ieeexplore.ieee.org/document/10412338) [[**arxiv**]](https://arxiv.org/pdf/2401.10966.pdf) [[**code**]](https://github.com/thibault-wch/HOPE-for-mild-cognitive-impairment)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MedIA 2024</div><img src='images/JL4AD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Joint learning framework of cross-modal synthesis and diagnosis for Alzheimer’s disease by mining underlying shared modality information](https://doi.org/10.1016/j.media.2023.103032)

**Chenhui Wang**, Sirong Piao, Zhizhong Huang, Qi Gao, Junping Zhang, Yuxin Li<sup>†</sup>, Hongming Shan<sup>†</sup>

Medical Image Analysis, 91, 103032, 2024 (<span style="color:blue">SCI Q1 Top</span>)

[[**doi**]](https://doi.org/10.1016/j.media.2023.103032) [[**supp**]](https://github.com/thibault-wch/Joint-Learning-for-Alzheimer-disease/blob/main/readme_files/main_supp.pdf) [[**code**]](https://github.com/thibault-wch/Joint-Learning-for-Alzheimer-disease)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

- [**MICCAI 2025**] Autoregressive Medical Image Segmentation via Next-Scale Mask Prediction, Tao Chen, **Chenhui Wang**, Zhihao Chen, Hongming Shan<sup>†</sup>. (<span style="color:blue">CCF B</span>) [[**arxiv**]](https://arxiv.org/abs/2502.20784)
- [**IEEE TMI 2024**] HiDiff: Hybrid Diffusion Framework for Medical Image Segmentation, Tao Chen, **Chenhui Wang**, Zhihao Chen, Yiming Lei<sup>†</sup>, Hongming Shan<sup>†</sup>. [[**doi**]](https://ieeexplore.ieee.org/document/10587153/) [[**arxiv**]](https://arxiv.org/pdf/2407.03548) [[**code**]](https://github.com/takimailto/HiDiff)
- [**MICCAI 2023**] BerDiff: Conditional Bernoulli Diffusion Model for Medical Image Segmentation, Tao Chen, **Chenhui Wang**, Hongming Shan<sup>†</sup>. (<span style="color:blue">CCF B</span>) [[**doi**]](https://doi.org/10.1007/978-3-031-43901-8_47) [[**arxiv**]](https://arxiv.org/pdf/2304.04429.pdf) [[**code**]](https://github.com/takimailto/BerDiff) 
- [**BIBM 2024**] Low-dose CT Denoising with Language-engaged Dual-space Alignment, Zhihao Chen, Tao Chen, **Chenhui Wang**, Chuang Niu, Ge Wang<sup>†</sup>, Hongming Shan<sup>†</sup>. (short paper) [[**doi**]](https://arxiv.org/pdf/2403.06128) [[**arxiv**]](https://arxiv.org/pdf/2403.06128) [[**code**]](https://github.com/hao1635/LEDA)

# 🎖 Honors and Awards
- *Nov. 2024* <span style="color:blue">Doctoral National Scholarship</span>.
- *June 2024*  <span style="color:blue">Travel Grant</span> from the *IJCAI committee* and <span style="color:blue">Overseas Participation Funding</span> from *Fudan University* to attend IJCAI 2024.
- *2022-2024*  <span style="color:blue">Outstanding Member of the Communist Youth League</span>  at Fudan University. (<span style="color:#9C27B0">**two consecutive years**</span>)
- *May 2021*  <span style="color:blue">Top Ten Outstanding Students</span>  at Wuhan University of Technology. (<span style="color:blue">0.01%</span>)
- *Sep. 2020*  <span style="color:blue">Excellence Scholarship</span> at Wuhan University of Technology. (<span style="color:blue">0.1%</span>)
- *2017-2019*  <span style="color:blue">National Scholarship</span>. (<span style="color:#9C27B0">**two consecutive years, 1%**</span>)


# 💪 Social Activities
- Hobbies: Reading, Thinking, and Hiking.
- Serving as the journal reviewer for  [*MedIA*](https://www.sciencedirect.com/journal/medical-image-analysis), [*PR*](https://www.sciencedirect.com/journal/pattern-recognition), [*IEEE TCSVT*](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=76), [*AI in Medicine*](https://www.sciencedirect.com/journal/artificial-intelligence-in-medicine), [*CAAI TIT*](https://ietresearch.onlinelibrary.wiley.com/journal/24682322), [*PRLETTERS*](https://www.sciencedirect.com/journal/pattern-recognition-letters), [*BMC Medical Imaging*](https://bmcmedimaging.biomedcentral.com/), [*Scientific Reports*](https://www.nature.com/srep/), [*IEEE ACCESS*](https://ieeeaccess.ieee.org/), [*SIGNAL PROCESS-IMAGE*](https://www.sciencedirect.com/journal/signal-processing-image-communication), and [*CCPE*](https://onlinelibrary.wiley.com/journal/15320634).
- Serving as the conference reviewer for [*IJCAI*](https://2025.ijcai.org/), [*SIGGRAPH Asia*](https://asia.siggraph.org/2025/), [*MICCAI (2024 & 2025)*](https://conferences.miccai.org/2024/en),  [*BIBM (2024 & 2025)*](https://ieeebibm.org/BIBM2024/), [*MIDL*](https://www.midl.io/), and [*IJCNN*](https://2025.ijcnn.org/).
- Holding five <span style="color:blue">patents</span> (<span style="color:blue">CN202210748948.X</span>, <span style="color:blue">CN202310278934.0</span>, <span style="color:blue">CN202410412376.7</span>, <span style="color:blue">CN117372796A</span>, <span style="color:blue">CN119991959A</span>).
- Achieving the <span style="color:blue">National First Prize</span> in the [*Chinese Collegiate Computing Competition*](https://jsjds.blcu.edu.cn/) of 2020, and secured the  <span style="color:blue">International Second Prize</span> in the [*ASC20-21 Asian Student Supercomputer Challenge*](http://www.asc-events.org/StudentChallenge/index.html).
- Volunteering as a Teaching Support Instructor in rural Dangyang City, Hubei Province, China, in 2018.





