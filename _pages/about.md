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

Hi there! My name is Rui-Chen Zheng (郑瑞晨).<br/>
I am currently a Ph.D. candidate at <a href='http://nelslip.ustc.edu.cn/main.htm'>National Engineering Research Center for Speech and Language Information Processing </a> of <a href='http://en.ustc.edu.cn/'>University of Science and Technology of China</a>, supervised by Prof. <a href='http://staff.ustc.edu.cn/~zhling/#!index.md'>Zhen-Hua Ling</a>.
I also closely collaborate with Dr. <a href='https://faculty.ustc.edu.cn/aiyang/en/index.htm'>Yang Ai</a>.
My main research interests include speech coding, articulatory-acoustic relationship in speech synthesis, and deep learning for speech synthesis. <br/>
My **CV** can be downloaded <a href="assets/RuichenZheng-CV-2025-06.pdf">here</a>.<a href="assets/RuichenZheng-CV-2025-06-CN.pdf">中文版简历</a>.<br/>
<!-- <font color=Blue>Looking for 6-12 months of visiting opportunities in speech synthesis! Please contact me if you have an appropriate position :) </font> -->


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.1*: &nbsp;🎉🎉 I am thrilled to announce that **three** papers have been accepted to ICASSP 2026! These include [one first-author paper](https://arxiv.org/abs/2509.19025), [one co-first-author paper](https://arxiv.org/abs/2509.23755), and [one co-authored work](https://arxiv.org/abs/2601.12757). Heartfelt thanks to all my incredible co-authors for their collaboration and support!
- *2025.11*: &nbsp;🎉🎉 My first-authored paper, "<a href='https://arxiv.org/abs/2509.04685'>Say More with Less: Variable‑Frame‑Rate Speech Tokenization via Adaptive Clustering and Implicit Duration Coding</a>", has been accepted as an **oral** presentation at **AAAI 2026**! We have open-sourced the <a href='https://github.com/FunAudioLLM/FunResearch/tree/main/VARSTok'>code</a> and <a href='https://huggingface.co/ZhengRachel/VARSTok/tree/main'>model weights</a>.
- *2025.10*: &nbsp;🎉🎉 I am thrilled to announce that I have received the 2025 National Graduate Scholarship! This achievement would not have been possible without the guidance and support of my supervisor, Prof. Ling, my collaborator, Dr. Ai, and my fellow lab mates. I am proud to share this honor with them. The official announcement can be found <a href='https://sist.ustc.edu.cn/2025/1010/c5142a703956/page.htm'>here</a>.
- *2025.09*: &nbsp;🎉🎉 I am thrilled to announce that I have started an 8-month visiting position at the <a href='https://www.cstr.ed.ac.uk/'>Centre for Speech Technology Research (CSTR)</a> at the University of Edinburgh. I am hosted by Dr. <a href='https://homepages.inf.ed.ac.uk/korin/sitenew/index.html'>Korin Richmond</a> and funded by the <a href='https://nrc.canada.ca/en/research-development/research-collaboration/programs/speech-generation-indigenous-language-education'>Speech generation for Indigenous language education (SGILE)</a> project. I'm incredibly grateful to Korin for this wonderful opportunity and look forward to the exciting research ahead. 

# 📖 Educations
- *2021.09 - 2026.06 (Expected)*, **Ph.D. Candidate** in Information and Comunication Engineering, *University of Science and Technology of China*
  - Supervised by Prof. Zhen-Hua Ling.
  - GPA: 3.9/4.3 (Top 3%).
- *2017.09 - 2021.06*, **Bachelor's Degree** of Electronic Information Engineering, *University of Science and Technology of China*  
  - Thesis: Method and Practice on Text-to-speech Without Text.
  - GPA: 3.89/4.3, 90.46/100 (Top 5%).
  - Minor in Business Administration.

# 💼 Experiences
- *2025.09 - 2026.04 (Expected)*, **Visiting Student** in <a href='https://www.cstr.ed.ac.uk/'>Centre for Speech Technology Research (CSTR)</a>, *University of Edinburgh*
  - Hosted by Dr. <a href='https://homepages.inf.ed.ac.uk/korin/sitenew/index.html'>Korin Richmond</a>. 
  - Funded by the <a href='https://nrc.canada.ca/en/research-development/research-collaboration/programs/speech-generation-indigenous-language-education'>Speech generation for Indigenous language education (SGILE)</a> project.
- *2025.03 - 2025.08*, **Research Intern**, <a href='https://tongyi.aliyun.com/welcome'>*Tongyi Speech Group, Alibaba Inc.*</a>  
  - Advised by Dr. <a href='https://scholar.google.com.tw/citations?user=8eosmSQAAAAJ&hl=zh-CN&oi=sra'>Qian Chen</a>, Mr. <a href='https://scholar.google.com.tw/citations?user=RnRnE3gAAAAJ&hl=zh-CN&oi=sra'>Chong Deng</a>, and Mr. Qinglin Zhang.



# 📝 Publications 

## 🎈 Speech Coding

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/varstok.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Say More with Less: Variable-Frame-Rate Speech Tokenization via Adaptive Clustering and Implicit Duration Coding](https://arxiv.org/abs/2509.04685)

**Rui-Chen Zheng**, Wenrui Liu, Hui-Peng Du, Qinglin Zhang, Chong Deng, Qian Chen, Wen Wang, Yang Ai, Zhen-Hua Ling

<div class="paper-links">
  <a href="https://zhengrachel.github.io/VARSTok/" class="paper-link-button" target="_blank" rel="noopener noreferrer">
    <i class="fas fa-desktop"></i> Demo
  </a>
  <a href="https://github.com/FunAudioLLM/FunResearch/tree/main/VARSTok" class="paper-link-button" target="_blank" rel="noopener noreferrer">
    <i class="fab fa-github"></i> Code
  </a>
  <a href="https://huggingface.co/ZhengRachel/VARSTok/tree/main" class="paper-link-button" target="_blank" rel="noopener noreferrer">
    <i class="fas fa-download"></i> Model
  </a>
</div>
- Existing speech tokenizers typically assign a fixed number of tokens per second, regardless of the varying information density or temporal fluctuations in the speech signal. This uniform token allocation mismatches the intrinsic structure of speech, where information is distributed unevenly over time. To address this, we propose VARSTok, a VAriable-frame-Rate Speech Tokenizer that adapts token allocation based on local feature similarity. VARSTok introduces two key innovations: (1) a temporal-aware density peak clustering algorithm that adaptively segments speech into variable-length units, and (2) a novel implicit duration coding scheme that embeds both content and temporal span into a single token index, eliminating the need for auxiliary duration predictors. Extensive experiments show that VARSTok significantly outperforms strong fixed-rate baselines. Notably, it achieves superior reconstruction naturalness while using up to 23% fewer tokens than a 40 Hz fixed-frame-rate baseline. VARSTok further yields lower word error rates and improved naturalness in zero-shot text-to-speech synthesis. To the best of our knowledge, this is the first work to demonstrate that a fully dynamic, variable-frame-rate acoustic speech tokenizer can be seamlessly integrated into downstream speech language models. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TASLP 2025</div><img src='images/ERVQ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ERVQ: Enhanced Residual Vector Quantization with Intra-and-Inter-Codebook Optimization for Neural Audio Codecs](https://ieeexplore.ieee.org/document/11031216)

**Rui-Chen Zheng**, Hui-Peng Du, Xiao-Hang Jiang, Yang Ai, Zhen-Hua Ling

[**Demo Page**](https://zhengrachel.github.io/ERVQ/)
- Current neural audio codecs typically use residual vector quantization (RVQ) to discretize speech signals. However, they often experience codebook collapse, which reduces the effective codebook size and leads to suboptimal performance. To address this problem, we introduce ERVQ, Enhanced Residual Vector Quantization, a novel enhancement strategy for the RVQ framework in neural audio codecs. ERVQ mitigates codebook collapse and boosts codec performance through both intra- and inter-codebook optimization. Intra-codebook optimization incorporates an online clustering strategy and a code balancing loss to ensure balanced and efficient codebook utilization. Inter-codebook optimization improves the diversity of quantized features by minimizing the similarity between successive quantizations. Our experiments show that ERVQ significantly enhances audio codec performance across different models, sampling rates, and bitrates, achieving superior quality and generalization capabilities. Further experiments indicate that audio codecs improved by the ERVQ strategy can improve unified speech-and-text large language models (LLMs). 
</div>
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">Accepted by ICASSP 2026</span> [Enhancing Noise Robustness for Neural Speech Codecs through Resource-Efficient Progressive Quantization Perturbation Simulation](https://arxiv.org/abs/2509.19025), **Rui-Chen Zheng**, Yang Ai, Hui-Peng Du, Li-Rong Dai.

<div class='paper-box-text' markdown="1">
- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">Accepted by ICASSP 2026</span> [CodeSep: Low-Bitrate Codec-Driven Speech Separation with Base-Token Disentanglement and Auxiliary-Token Serial Prediction](https://arxiv.org/abs/2601.12757), Hui-Peng Du, Yang Ai, Xiao-Hang Jiang, **Rui-Chen Zheng**, Zhen-Hua Ling.

<div class='paper-box-text' markdown="1">
- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">IEEE Signal Processing Letters</span> [Is GAN Necessary for Mel-Spectrogram-based Neural Vocoder?](https://ieeexplore.ieee.org/abstract/document/11123758), Hui-Peng Du, Yang Ai, **Rui-Chen Zheng**, Ye-Xin Lu, Zhen-Hua Ling.

- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">INTERSPEECH 2025</span> [Vision-Integrated High-Quality Neural Speech Coding](https://arxiv.org/abs/2505.23379), Yao Guo, Yang Ai, **Rui-Chen Zheng**, Hui-Peng Du, Xiao-Hang Jiang, Zhen-Hua Ling.

- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">IEEE Signal Processing Letters</span> [A Streamable Neural Audio Codec With Residual Scalar-Vector Quantization for Real-Time Communication](https://ieeexplore.ieee.org/abstract/document/10962534), Xiao-Hang Jiang, Yang Ai, **Rui-Chen Zheng**, Zhen-Hua Ling.

- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">ISCSLP 2024</span> [APCodec+: A Spectrum-Coding-Based High-Fidelity and High-Compression-Rate Neural Audio Codec with Staged Training Paradigm](https://ieeexplore.ieee.org/abstract/document/10800013), Hui-Peng Du, Yang Ai, **Rui-Chen Zheng**, Zhen-Hua Ling.

- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">SLT 2024</span> [MDCTCodec: A Lightweight MDCT-based Neural Audio Codec towards High Sampling Rate and Low Bitrate Scenarios](https://ieeexplore.ieee.org/abstract/document/10832214), Xiao-Hang Jiang, Yang Ai, **Rui-Chen Zheng**, Hui-Peng Du, Zhen-Hua Ling.

- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">SLT 2024</span> [Stage-Wise and Prior-Aware Neural Speech Phase Prediction](https://ieeexplore.ieee.org/abstract/document/10832188), Fei Liu, Yang Ai, Hui-Peng Du, Ye-Xin Lu, **Rui-Chen Zheng**, Zhen-Hua Ling

- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">INTERSPEECH 2024</span> [A Low-Bitrate Neural Audio Codec Framework with Bandwidth Reduction and Recovery for High-Sampling-Rate Waveforms](https://www.isca-archive.org/interspeech_2024/ai24b_interspeech.pdf), Yang Ai, Ye-Xin Lu, Xiao-Hang Jiang, Zheng-Yan Sheng, **Rui-Chen Zheng**, Zhen-Hua Ling.


## 🎈 Articulation-Acoustic Relationship

### 🔑 Articulation-to-Speech Synthesis

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Multimedia 2024</div><img src='images/Diff-ATS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Speech Reconstruction from Silent Lip and Tongue Articulation by Diffusion Models and Text-Guided Pseudo Target Generation](https://dl.acm.org/doi/abs/10.1145/3664647.3680770)

**Rui-Chen Zheng**, Yang Ai, Zhen-Hua Ling

[**Demo Page**](https://zhengrachel.github.io/Diff-A2A/)
- This paper studies the task of speech reconstruction from ultrasound tongue images and optical lip videos, with a particular focus on a silent speaking mode, where people only activate their intra-oral and extra-oral articulators without producing real speech. We introduce a novel pseudo target generation strategy, integrating the text modality to align with articulatory movements, thereby guiding the generation of pseudo acoustic features for supervised training on speech reconstruction from silent articulation. Furthermore, we propose to employ a diffusion model as the fundamental architecture for the A2A conversion task and train the model with the pseudo acoustic features generated by the proposed pseudo target generation strategy using a combined training approach. Experiments show that our proposed method significantly improves the intelligibility and naturalness of the reconstructed speech in the silent speaking mode compared to all baseline methods. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023</div><img src='images/ImprovedTaLNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Speech Reconstruction from Silent Tongue and Lip Articulation By Pseudo Target Generation and Domain Adversarial Training](https://ieeexplore.ieee.org/document/10096920)

**Rui-Chen Zheng**, Yang Ai, Zhen-Hua Ling

[**Demo Page**](https://zhengrachel.github.io/ImprovedTaLNet-demo/)
- This paper studies the task of speech reconstruction from ultrasound tongue images and optical lip videos recorded in a silent speaking mode, where people only activate their intra-oral and extra-oral articulators without producing sound. We propose to employ a method built on pseudo target generation and domain adversarial training with an iterative training strategy to improve the intelligibility and naturalness of the speech recovered from silent tongue and lip articulation. Experiments show that our proposed method significantly improves the intelligibility and naturalness of the reconstructed speech in silent speaking mode compared to the baseline TaLNet model.
</div>
</div>


### 🔑 Audio-Articulation Speech Enhancement

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE/ACM TASLP 2024</div><img src='images/IUTIforAVSE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Incorporating Ultrasound Tongue Images for Audio-Visual Speech Enhancement](https://ieeexplore.ieee.org/document/10418525)

**Rui-Chen Zheng**, Yang Ai, Zhen-Hua Ling

[**Demo Page**](https://zhengrachel.github.io/IUTIforAVSE-demo/)
- This paper proposes the incorporation of ultrasound tongue images to improve the performance of lip-based audio-visual speech enhancement (AV-SE) systems. To address the challenge of acquiring ultrasound tongue images during inference, we first propose to employ knowledge distillation during training to investigate the feasibility of leveraging tongue-related information without directly inputting ultrasound tongue images. To better model the alignment between the lip and tongue modalities, we further propose the introduction of a lip-tongue key-value memory network into the AV-SE model. This network enables the retrieval of tongue features based on readily available lip features, thereby assisting the subsequent speech enhancement task. Experimental results demonstrate that both methods significantly improve the quality and intelligibility of the enhanced speech compared to traditional lip-based AV-SE baselines. Furthermore, phone error rate (PER) analysis of automatic speech recognition (ASR) reveals that while all phonemes benefit from introducing ultrasound tongue images, palatal and velar consonants benefit most.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INTERSPEECH 2023</div><img src='images/UTIforAVSE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Incorporating Ultrasound Tongue Images for Audio-Visual Speech Enhancement through Knowledge Distillation](https://arxiv.org/abs/2305.14933)

**Rui-Chen Zheng**, Yang Ai, Zhen-Hua Ling

[**Demo Page**](https://zhengrachel.github.io/UTIforAVSE-demo/)
- Audio-visual speech enhancement (AV-SE) aims to enhance degraded speech along with extra visual information such as lip videos, and has been shown to be more effective than audio-only speech enhancement. This paper proposes further incorporating ultrasound tongue images to improve lip-based AV-SE systems’ performance. Knowledge distillation is employed at the training stage to address the challenge of acquiring ultrasound tongue images during inference, enabling an audio-lip speech enhancement student model to learn from a pre-trained audiolip-tongue speech enhancement teacher model. Experimental results demonstrate significant improvements in the quality and intelligibility of the speech enhanced by the proposed method compared to the traditional audio-lip speech enhancement baselines. Further analysis using phone error rates (PER) of automatic speech recognition (ASR) shows that palatal and velar consonants benefit most from the introduction of ultrasound tongue images.
</div>
</div>

## 💬 End-to-end Spoken Dialogue System
<div class='paper-box-text' markdown="1">
- <span style="background-color: #00369f; color: white; padding: 1px 4px; border-radius: 2px;">Accepted by ICASSP 2026</span> [Understanding Textual Capability Degradation in Speech LLMs via Parameter Importance Analysis](https://arxiv.org/abs/2509.23755), Chao Wang\*, **Rui-Chen Zheng\***(\*Equal Contribution), Yang Ai, Zhen-Hua Ling.


</div>





# 🎖 Honors and Awards
- *2025.10* National Graduate Scholarship.
- *2024.12* JAC-NIO Scholarship.
- *2021.06* Honor Rank for Top 5% Graduates of USTC. 
- *2020.12* Huawei Scholarship. 
- *2019.12* Top-Notch Program Funding.
- *2019.12* USTC Outstanding Student Scholarship, Gold Award.


# 🔍 Services
Invited Reviewers for *Speech Communication*, *IEEE Signal Processing Letters* and *IEEE/ACM Transactions on Audio, Speech, and Language Processing*.


# 📚 Teaching Assistant Experience
- *2022 Fall*, Fundamentals of Speech Signal Processing, USTC (Prof. Zhen-Hua Ling)
- *2021 Fall*, Fundamentals of Speech Signal Processing, USTC (Prof. Zhen-Hua Ling)
- *2020 Fall*, Computer Programing Design A, USTC (Lecturer. Hu Si)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->