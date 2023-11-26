# 📝 Publications 
<!-- 加点表情包,直接复制图片即可  https://github.com/guodongxiaren/README/blob/master/emoji.md?tdsourcetag=s_pcqq_aiomsg -->

A full publication list is available on my [google scholar](https://scholar.google.com/citations?user=jQ3bFDMAAAAJ&hl=en&oi=ao) page.

(* denotes equal contribution.)

## Pre-prints ##
- [I2VGen-XL: High-Quality Image-to-Video Synthesis via Cascaded Diffusion Models](https://arxiv.org/abs/2311.04145), Shiwei Zhang*, Jiayu Wang*, Yingya Zhang*, Kang Zhao, **Hangjie Yuan**, Zhiwu Qin, Xiang Wang, Deli Zhao, Jingren Zhou.
- [Few-shot Action Recognition with Captioning Foundation Models](https://arxiv.org/abs/2310.10125), Xiang Wang, Shiwei Zhang, **Hangjie Yuan**, Yingya Zhang, Changxin Gao, Deli Zhao, Nong Sang.
- [Refined Response Distillation for Class-Incremental Player Detection](https://arxiv.org/abs/2305.00620), Liang Bai, **Hangjie Yuan**, Tao Feng, Hong Song, Jian Yang.
- [Progressive Learning without Forgetting](https://arxiv.org/abs/2211.15215), Tao Feng, **Hangjie Yuan**, Mang Wang, Ziyuan Huang, Ang Bian, Jianzhou Zhang.


## Video Generation
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/VideoComposer_overview.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**NeurIPS 2023**] [VideoComposer: Compositional Video Synthesis with Motion Controllability](https://arxiv.org/abs/2306.02018), 
Xiang Wang\*, **Hangjie Yuan**\*, Shiwei Zhang\*, Dayou Chen\*, Jiuniu Wang, Yingya Zhang, Yujun Shen, Deli Zhao, Jingren Zhou.    
[[Project page]](https://videocomposer.github.io/) [[机器之心]](https://mp.weixin.qq.com/s/4LVGj0KQDPJDGn5SVZfW1w) [[CVer]](https://mp.weixin.qq.com/s/rpmXd-nkE9oSG4bZsKKfpw)

- VideoComposer pioneers controllable video synthesis, seamlessly integrating textual, spatial, and crucially, temporal conditions, through a unified interface for information injection.
- VideoComposer can craft videos using various input control signals, from intricate hand-drawn sketches to defined motions.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical report</div><img src='images/ModelScopeT2V_overview.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ModelScope Text-to-Video Technical Report](https://arxiv.org/abs/2308.06571),
Jiuniu Wang\*, **Hangjie Yuan**\*, Dayou Chen\*, Yingya Zhang\*, Xiang Wang, Shiwei Zhang.    [[Project page]](https://modelscope.cn/models/damo/text-to-video-synthesis/summary)

- ModelScope is the **first** publicly-available diffusion-based text-to-video model at scale, which has been utilized by **hundreds of thousands of people**.

</div>
</div>


## HOI Detection / Scene Graph Generation
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/RLIPv2_overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RLIPv2: Fast Scaling of Relational Language-Image Pre-training](https://arxiv.org/abs/2308.09351),
**Hangjie Yuan**, Shiwei Zhang, Xiang Wang, Samuel Albanie, Yining Pan, Tao Feng, Jianwen Jiang, Dong Ni, Yingya Zhang, Deli Zhao.    [[code]](https://github.com/JacobYuan7/RLIPv2) 

- RLIPv2 elevates RLIP by leveraging a new language-image fusion mechanism, designed for expansive data scales.
- The most advanced pre-trained RLIPv2 (Swin-L) matches the performance of RLIPv1 (R50) while utilizing a mere 1% of the data.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022 Spotlight</div><img src='images/RLIP_overview.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RLIP: Relational Language-Image Pre-training for Human-Object Interaction Detection](https://arxiv.org/abs/2209.01814) <span style="color:red"><strong>Spotlight (Top 5%)</strong></span> \\
**Hangjie Yuan**, Jianwen Jiang, Samuel Albanie, Tao Feng, Ziyuan Huang, Dong Ni and Mingqian Tang.    [[code]](https://github.com/JacobYuan7/RLIP) [[video talk]](https://recorder-v3.slideslive.com/?share=73193&s=67557178-73e9-48d1-af1c-4aacc162164b)  

- RLIP is the first work to use **relation texts** as a language-image pre-training signal.
- RLIP-ParSe achieves SOTA results on fully-finetuned, few-shot, zero-shot HOI detetction benchmarks and learning from noisy labels.
</div>
</div>
<!-- - ParSe is a SOTA HOI/relation detection framework without bells and whistles.-->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/OCN_overview.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [Detecting Human-Object Interactions with Object-Guided Cross-Modal Calibrated Semantics](https://arxiv.org/abs/2202.00259) \\
**Hangjie Yuan**, Mang Wang, Dong Ni and Liangpeng Xu.    [[code]](https://github.com/JacobYuan7/OCN-HOI-Benchmark) [[video talk]](https://aaai-2022.virtualchair.net/poster_aaai1979)

- OCN proposes a two-stage HOI detection method by decoupling entity detection and relation inference.
- OCN incorporates language and statistical prior to facilitate verb inference.
</div>
</div>
<!-- - OCN achieves SOTA results on HICO-DET and V-COCO benchmarks.-->


## Video Understanding
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/DIN_overview.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spatio-Temporal Dynamic Inference Network for Group Activity Recognition]([https://arxiv.org/abs/2202.00259](https://openaccess.thecvf.com/content/ICCV2021/papers/Yuan_Spatio-Temporal_Dynamic_Inference_Network_for_Group_Activity_Recognition_ICCV_2021_paper.pdf)) \\
**Hangjie Yuan**, Dong Ni and Mang Wang.    [[code]](https://github.com/JacobYuan7/DIN-Group-Activity-Recognition-Benchmark) [[知乎]](https://zhuanlan.zhihu.com/p/408883301) [[将门创投]](https://www.techbeat.net/article-info?id=2719) [[video talk]](https://zjueducn-my.sharepoint.com/:v:/g/personal/hj_yuan_zju_edu_cn/ETNLr67L5glAhOibIzbfSEsBuIKsCmYhftrf1pct-WkoWQ?e=LSaAcz)

- DIN proposes to perform spatio-temporal dynamic inference.
- DIN achieves SOTA results on Volleyball and CAD benchmarks while costing **much less computational overhead** of the reasoning module.
</div>
</div>
<!-- ICCV 2021 virtual video talk: https://www.eventscribeapp.com/live/videoPlayer.asp?lsfp=L2hQanMxaXBuamluR0IwamNhWEtwaGY5Zy80TmJuN0ZLcm9ZeWNBc08yVlRVcGlicDd1MW9uVjJXRHlWMkw0Yg==
But we must log in to watch. -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2021</div><img src='images/context_overview_2.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Visual Context for Group Activity Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/16437)) \\
**Hangjie Yuan** and Dong Ni. [[video talk]](https://papertalk.org/papertalks/30909)

- This paper proposes to incorporate visual context when recognizing activities. This should work for other related problems as well.
- This paper achieves SOTA results on Volleyball and CAD benchmarks.
</div>
</div>



## Incremental / Continual Learning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/ERD_overview.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overcoming Catastrophic Forgetting in Incremental Object Detection via Elastic Response Distillation](https://openaccess.thecvf.com/content/CVPR2022/html/Feng_Overcoming_Catastrophic_Forgetting_in_Incremental_Object_Detection_via_Elastic_Response_CVPR_2022_paper.html) \\
Tao Feng, Mang Wang and **Hangjie Yuan**.  [[code]](https://github.com/Hi-FT/ERD)

- This paper proposes a response-only distillation method for Incremental Object Detection, dubbed Elastic Response Distillation.
- This paper achieves SOTA results on COCO benchmarks while utilizing much fewer responses for distillation.
</div>
</div>

<!-- - [**CVPR 2022**] [Overcoming Catastrophic Forgetting in Incremental Object Detection via Elastic Response Distillation](https://openaccess.thecvf.com/content/CVPR2022/html/Feng_Overcoming_Catastrophic_Forgetting_in_Incremental_Object_Detection_via_Elastic_Response_CVPR_2022_paper.html), Tao Feng, Mang Wang and **Hangjie Yuan**  [[code]](https://github.com/Hi-FT/ERD) -->

## Other Interesting Topics
- [From Denoising Training to Test-Time Adaptation: Enhancing Domain Generalization for Medical Image Segmentation](https://arxiv.org/abs/2310.20271), Ruxue Wen, **Hangjie Yuan**, Dong Ni, Wenbo Xiao, Yaoyao Wu, In **WACV 2024**. [[code]](https://github.com/WenRuxue/DeTTA)


  

  
<!-- # 📝 Publications 
## 🎙 Speech Synthesis


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2019</div><img src='images/fs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastSpeech: Fast, Robust and Controllable Text to Speech](https://papers.nips.cc/paper/8580-fastspeech-fast-robust-and-controllable-text-to-speech.pdf) \\
**Yi Ren**, Yangjun Ruan, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

[**Project**](https://speechresearch.github.io/fastspeech/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- FastSpeech is the first fully parallel end-to-end speech synthesis model.
- **Academic Impact**: This work is included by many famous speech synthesis open-source projects, such as [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet). Our work are promoted by more than 20 media and forums, such as [机器之心](https://mp.weixin.qq.com/s/UkFadiUBy-Ymn-zhJ95JcQ)、[InfoQ](https://www.infoq.cn/article/tvy7hnin8bjvlm6g0myu).
- **Industry Impact**: FastSpeech has been deployed in [Microsoft Azure TTS service](https://techcommunity.microsoft.com/t5/azure-ai/neural-text-to-speech-extends-support-to-15-more-languages-with/ba-p/1505911) and supports 49 more languages with state-of-the-art AI quality. It was also shown as a text-to-speech system acceleration example in [NVIDIA GTC2020](https://resources.nvidia.com/events/GTC2020s21420).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2021</div><img src='images/fs2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastSpeech 2: Fast and High-Quality End-to-End Text to Speech](https://arxiv.org/abs/2006.04558) \\
**Yi Ren**, Chenxu Hu, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

[**Project**](https://speechresearch.github.io/fastspeech2/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong>
  - This work is included by many famous speech synthesis open-source projects, such as [PaddlePaddle/Parakeet ![](https://img.shields.io/github/stars/PaddlePaddle/PaddleSpeech?style=social)](https://github.com/PaddlePaddle/PaddleSpeech), [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet) and [fairseq ![](https://img.shields.io/github/stars/pytorch/fairseq?style=social)](https://github.com/pytorch/fairseq).
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2021</div><img src='images/portaspeech.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PortaSpeech: Portable and High-Quality Generative Text-to-Speech](https://arxiv.org/abs/2109.15166) \\
**Yi Ren**, Jinglin Liu, Zhou Zhao

[**Project**](https://portaspeech.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=Code+Stars)](https://github.com/NATSpeech/NATSpeech) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/PortaSpeech)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/diffsinger.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffSinger: Singing Voice Synthesis via Shallow Diffusion Mechanism](https://arxiv.org/abs/2105.02446) \\
Jinglin Liu, Chengxi Li, **Yi Ren**, Feiyang Chen, Zhou Zhao

[**Project**](https://diffsinger.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=DiffSpeech Stars)](https://github.com/NATSpeech/NATSpeech) \| [![](https://img.shields.io/github/stars/MoonInTheRiver/DiffSinger?style=social&label=DiffSinger Stars)](https://github.com/MoonInTheRiver/DiffSinger) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/DiffSpeech)
</div>
</div>

- [ProDiff: Progressive Fast Diffusion Model for High-Quality Text-to-Speech](), Rongjie Huang, Zhou Zhao, Huadai Liu, Jinglin Liu, Chenye Cui, **Yi Ren**, **ACM-MM 2022**
- [SingGAN: Generative Adversarial Network For High-Fidelity Singing Voice Generation](https://arxiv.org/abs/2110.07468), Rongjie Huang, Chenye Cui, Chen Feiayng, **Yi Ren**, Jinglin Liu, Zhou Zhao, Baoxing Huai, Zhefeng Wang, **ACM-MM 2022**
- [SyntaSpeech: Syntax-Aware Generative Adversarial Text-to-Speech](), Zhenhui Ye, Zhou Zhao, **Yi Ren**, Fei Wu, **IJCAI 2022**
- [EditSinger: Zero-Shot Text-Based Singing Voice Editing System with Diverse Prosody Modeling](), Lichao Zhang, Zhou Zhao, **Yi Ren**, Liqun Deng, **IJCAI 2022** <span style="color:red">(Oral)</span>
- [FastDiff: A Fast Conditional Diffusion Model for High-Quality Speech Synthesis](), Rongjie Huang, Max W. Y. Lam, Jun Wang, Dan Su, Dong Yu, **Yi Ren**, Zhou Zhao, **IJCAI 2022** <span style="color:red">(Oral)</span>
- [Revisiting Over-Smoothness in Text to Speech](https://arxiv.org/abs/2202.13066), **Yi Ren**, Xu Tan, Tao Qin, Zhou Zhao, Tie-Yan Liu, **ACL 2022**
- [Learning the Beauty in Songs: Neural Singing Voice Beautifier](https://arxiv.org/abs/2202.13277), Jinglin Liu, Chengxi Li, **Yi Ren**, Zhiying Zhu, Zhou Zhao, **ACL 2022** \| [![](https://img.shields.io/github/stars/MoonInTheRiver/NeuralSVB?style=social&label=Code+Stars)](https://github.com/MoonInTheRiver/NeuralSVB)
- [ProsoSpeech: Enhancing Prosody With Quantized Vector Pre-training in Text-to-Speech](https://prosospeech.github.io/), **Yi Ren**, Ming Lei, Zhiying Huang,  Shiliang Zhang, Qian Chen, Zhijie Yan, Zhou Zhao, **ICASSP 2022**
- [EMOVIE: A Mandarin Emotion Speech Dataset with a Simple Emotional Text-to-Speech Model](https://arxiv.org/abs/2106.09317), Chenye Cui, **Yi Ren**, Jinglin Liu, Feiyang Chen, Rongjie Huang, Ming Lei and Zhou Zhao, **INTERSPEECH 2021**
- [WSRGlow: A Glow-based Waveform Generative Model for Audio Super-Resolution](https://arxiv.org/abs/2106.08507), Kexun Zhang, **Yi Ren**, Changliang Xu and Zhou Zhao, **INTERSPEECH 2021** <span style="color:red">(best student paper award candidate)</span>
- [Denoising Text to Speech with Frame-Level Noise Modeling](https://arxiv.org/abs/2012.09547), Chen Zhang, **Yi Ren**, Xu Tan, Jinglin Liu, Kejun Zhang, Tao Qin, Sheng Zhao, Tie-Yan Liu, **ICASSP 2021** \| [**Project**](https://speechresearch.github.io/denoispeech/)
- [Multi-Singer: Fast Multi-Singer Singing Voice Vocoder With A Large-Scale Corpus](https://arxiv.org/pdf/2112.10358), Rongjie Huang, Feiyang Chen, **Yi Ren**, Jinglin Liu, Chenye Cui, Zhou Zhao, **ACM-MM 2021** <span style="color:red">(Oral)</span>
- [FedSpeech: Federated Text-to-Speech with Continual Learning](https://www.ijcai.org/proceedings/2021/527), Ziyue Jiang, **Yi Ren**, Ming Lei and Zhou Zhao, **IJCAI 2021**
- [DeepSinger: Singing Voice Synthesis with Data Mined From the Web](https://dl.acm.org/doi/abs/10.1145/3394486.3403249), **Yi Ren**, Xu Tan, Tao Qin, Jian Luan, Zhou Zhao, Tie-Yan Liu, **KDD 2020** \| [**Project**](https://speechresearch.github.io/deepsinger/)
- [LRSpeech: Extremely Low-Resource Speech Synthesis and Recognition](https://dl.acm.org/doi/abs/10.1145/3394486.3403331), Jin Xu, Xu Tan, **Yi Ren**, Tao Qin, Jian Li, Sheng Zhao, Tie-Yan Liu, **KDD 2020** \| [**Project**](https://speechresearch.github.io/lrspeech/)
- [MultiSpeech: Multi-Speaker Text to Speech with Transformer](https://www.isca-speech.org/archive/Interspeech_2020/pdfs/3139.pdf), Mingjian Chen, Xu Tan, **Yi Ren**, Jin Xu, Hao Sun, Sheng Zhao, Tao Qin, **INTERSPEECH 2020** \| [**Project**](https://speechresearch.github.io/multispeech/)
- [Almost Unsupervised Text to Speech and Automatic Speech Recognition](https://pdfs.semanticscholar.org/9075/a3e6271e5ef4953491488d1776527e632408.pdf), **Yi Ren**, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu, **ICML 2019** <span style="color:red">(Oral)</span> \| [**Project**](https://speechresearch.github.io/unsuper/) 

## 👄 Lip Generation/Understanding
- [Parallel and High-Fidelity Text-to-Lip Generation](https://arxiv.org/abs/2107.06831), Jinglin Liu, Zhiying Zhu, **Yi Ren**, Wencan Huang, Baoxing Huai, Nicholas Yuan, Zhou Zhao, **AAAI 2022** \| [![](https://img.shields.io/github/stars/Dianezzy/ParaLip?style=social&label=ParaLip Stars)](https://github.com/Dianezzy/ParaLip)
- Flow-based Unconstrained Lip to Speech Generation, Jinzheng He, Zhou Zhao, **Yi Ren**, Jinglin Liu, Baoxing Huai, Nicholas Yuan, **AAAI 2022**
- [FastLR: Non-Autoregressive Lipreading Model with Integrate-and-Fire](https://dl.acm.org/doi/10.1145/3394171.3413740), Jinglin Liu, **Yi Ren**, Zhou Zhao, Chen Zhang, Baoxing Huai, Jing Yuan, **ACM-MM 2020**

## 📚 Machine Translation 
- [UWSpeech: Speech to Speech Translation for Unwritten Languages](https://arxiv.org/abs/2006.07926), Chen Zhang, Xu Tan, **Yi Ren**, Tao Qin, Kejun Zhang, Tie-Yan Liu, **AAAI 2021** \| [**Project**](https://speechresearch.github.io/uwspeech/)
- [Task-Level Curriculum Learning for Non-Autoregressive Neural Machine Translation](https://www.ijcai.org/Proceedings/2020/0534.pdf), Jinglin Liu, **Yi Ren**, Xu Tan, Chen Zhang, Tao Qin, Zhou Zhao and Tie-Yan Liu, **IJCAI 2020**
- [SimulSpeech: End-to-End Simultaneous Speech to Text Translation](https://www.aclweb.org/anthology/2020.acl-main.350), **Yi Ren**, Jinglin Liu, Xu Tan, Chen Zhang, Qin Tao, Zhou Zhao, Tie-Yan Liu, **ACL 2020**
- [A Study of Non-autoregressive Model for Sequence Generation](https://arxiv.org/abs/2004.10454), **Yi Ren**, Jinglin Liu, Xu Tan, Zhou Zhao, Sheng Zhao, Tie-Yan Liu, **ACL 2020**
- [Multilingual Neural Machine Translation with Knowledge Distillation](https://openreview.net/forum?id=S1gUsoR9YX), Xu Tan, **Yi Ren**, Di He, Tao Qin, Zhou Zhao, Tie-Yan Liu, **ICLR 2019**


## 🎼 Music Generation 
- [SongMASS: Automatic Song Writing with Pre-training and Alignment Constraint](https://arxiv.org/abs/2012.05168), Zhonghao Sheng, Kaitao Song, Xu Tan, **Yi Ren**, Wei Ye, Shikun Zhang, Tao Qin, **AAAI 2021**
- [PopMAG: Pop Music Accompaniment Generation](https://dl.acm.org/doi/10.1145/3394171.3413721), **Yi Ren**, Jinzheng He, Xu Tan, Tao Qin, Zhou Zhao, Tie-Yan Liu, **ACM-MM 2020** <span style="color:red">(Oral)</span> \| [**Project**](https://speechresearch.github.io/popmag/)

## 🧑‍🎨 Generative Model
- [Pseudo Numerical Methods for Diffusion Models on Manifolds](https://openreview.net/forum?id=PlKWVd2yBkY), Luping Liu, **Yi Ren**, Zhijie Lin, Zhou Zhao, **ICLR 2022** \| [![](https://img.shields.io/github/stars/luping-liu/PNDM?style=social&label=Code+Stars)](https://github.com/luping-liu/PNDM) \| [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/pseudo-numerical-methods-for-diffusion-models-1/image-generation-on-celeba-64x64)](https://paperswithcode.com/sota/image-generation-on-celeba-64x64?p=pseudo-numerical-methods-for-diffusion-models-1)

## Others
- [Video-Guided Curriculum Learning for Spoken Video Grounding](), Yan Xia, Zhou Zhao, Shangwei Ye, Yang Zhao, Haoyuan Li, **Yi Ren**, **ACM-MM 2022** -->
