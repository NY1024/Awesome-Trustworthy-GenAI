# Awesome-Trustworthy-GenAI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
<a href=""> <img src="https://img.shields.io/github/stars/NY1024/Awesome-Trustworthy-GenAI?style=flat-square&logo=github" alt="GitHub stars"></a>
<a href=""> <img src="https://img.shields.io/github/forks/NY1024/Awesome-Trustworthy-GenAI?style=flat-square&logo=github" alt="GitHub forks"></a>
<a href=""> <img src="https://img.shields.io/github/last-commit/NY1024/Awesome-Trustworthy-GenAI"></a>
</p>

---
## Categories
- [Paper](paper.md)
  - [LLM](paper/llm.md)
  - [MLLM](paper/mllm.md)
    - Jailbreak
      - Attack
      - Defense
      - Benchmark
      - Survey
    - Poisoning/Backdoor
      - Attack
      - Defense
    - Adversarial
      - Attack
      - Defense
      - Benchmark
    - Hallucination
    - Bias
    - Others
  - [T2I](paper/t2i.md)
    - IP
      - Protection
      - Violation
      - Survey
    - Privacy
      - Attack
      - Defense
      - Benchmark
    - Memorization
    - Deepfake
      - Construction
      - Detection
      - Benchmark
    - Bias
    - Backdoor
      - Attack
      - Defense
    - Adversarial
      - Attack
      - Defense
  - [Agent](paper/agent.md)
- [Book](book.md)
- [Tutorial](tutorial.md)
- [Arena](arena.md)
- [Competition](competition.md)
  
---
Update[06/29/2024]

# MLLM

## Jailbreak

### Attack

| Title                                                        | Author          | Publish | Year | Link                                                         | Source Code                                                  |
| ------------------------------------------------------------ | --------------- | ------- | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Visual Adversarial Examples Jailbreak Large Language Models  | Xiangyu Qi      | AAAI    | 2024 | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/30150/32038) | [github](https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models) |
| Unveiling the Safety of GPT-4o: An Empirical Study using Jailbreak Attacks | Zonghao Ying    | arxiv   | 2024 | https://arxiv.org/abs/2406.06302                             | https://github.com/ny1024/jailbreak_gpt4o                    |
| Jailbreak Vision Language Models via Bi-Modal Adversarial Prompt | Zonghao Ying    | arxiv   | 2024 | https://arxiv.org/abs/2406.04031                             | https://github.com/NY1024/BAP-Jailbreak-Vision-Language-Models-via-Bi-Modal-Adversarial-Prompt |
| Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models | Erfan Shayegani | ICLR    | 2024 | https://openreview.net/forum?id=plmBsXHxgR                   | null                                                         |
| FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts | Yichen Gong     | arxiv   | 2023 | https://arxiv.org/abs/2311.05608                             | https://github.com/ThuCCSLab/FigStep                         |
| Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models | Yifan Li        | arxiv   | 2024 | https://arxiv.org/abs/2403.09792                             | https://github.com/AoiDragon/HADES                           |
| Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks? | Shuo Chen       | arxiv   | 2024 | https://arxiv.org/abs/2404.03411                             | null                                                         |
| Cross-Modality Jailbreak and Mismatched Attacks on Medical Multimodal Large Language Models | Xijie Huang     | arxiv   | 2024 | https://arxiv.org/abs/2405.20775                             | https://github.com/dirtycomputer/O2M_attack                  |
| Visual-RolePlay: Universal Jailbreak Attack on MultiModal Large Language Models via Role-playing Image Character | Siyuan Ma       | arxiv   | 2024 | https://arxiv.org/abs/2405.20773                             | null                                                         |
| Jailbreaking Attack against Multimodal Large Language Model  | Zhenxing Niu    | arxiv   | 2024 | https://arxiv.org/abs/2402.02309                             | https://github.com/abc03570128/Jailbreaking-Attack-against-Multimodal-Large-Language-Model |

### Defense

| Title                                                        | Author              | Publish | Year | Link                             | Source Code                                 |
| ------------------------------------------------------------ | ------------------- | ------- | ---- | -------------------------------- | ------------------------------------------- |
| MLLMGuard: A Multi-dimensional Safety Evaluation Suite for Multimodal Large Language Models | Tianle Gu           | arxiv   | 2024 | https://arxiv.org/abs/2406.07594 | https://github.com/Carol-gutianle/MLLMGuard |
| Cross-Modal Safety Alignment: Is textual unlearning all you need? | Trishna Chakraborty | arxiv   | 2024 | https://arxiv.org/abs/2406.02575 | null                                        |
| Unbridled Icarus: A Survey of the Potential Perils of Image Inputs in Multimodal Large Language Model Security | Yihe Fan            | arxiv   | 2024 | https://arxiv.org/abs/2404.05264 | null                                        |
| AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting | Yu Wang             | arxiv   | 2024 | https://arxiv.org/abs/2403.09513 | https://github.com/rain305f/AdaShield       |
| Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models | Yongshuo Zong       | arxiv   | 2024 | https://arxiv.org/abs/2402.02207 | https://github.com/ys-zong/VLGuard          |
| JailGuard: A Universal Detection Framework for LLM Prompt-based Attacks | Xiaoyu Zhang        | arxiv   | 2024 | https://arxiv.org/abs/2312.10766 | null                                        |

### Benchmark

| Title                                                        | Author         | Publish | Year | Link                             | Source Code                                           |
| ------------------------------------------------------------ | -------------- | ------- | ---- | -------------------------------- | ----------------------------------------------------- |
| JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks | Weidi Luo      | arxiv   | 2024 | https://arxiv.org/abs/2404.03027 | https://github.com/EddyLuo1232/JailBreakV_28K         |
| MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models | Xin Liu        | arxiv   | 2023 | https://arxiv.org/abs/2311.17600 | https://github.com/isXinLiu/MM-SafetyBench            |
| Red Teaming Visual Language Models                           | Mukai Li       | arxiv   | 2024 | https://arxiv.org/abs/2401.12915 | [null](https://github.com/EddyLuo1232/JailBreakV_28K) |
| How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs | Haoqin Tu      | arxiv   | 2023 | https://arxiv.org/abs/2311.16101 | https://github.com/UCSC-VLAA/vllm-safety-benchmark    |
| Benchmarking Trustworthiness of Multimodal Large Language Models: A Comprehensive Study | Yichi Zhang    | arxiv   | 2024 | https://arxiv.org/abs/2406.07057 | https://multi-trust.github.io/                        |
| SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model | Yongting Zhang | arxiv   | 2024 | https://arxiv.org/abs/2406.12030 | https://github.com/EchoseChen/SPA-VL-RLHF             |
| MOSSBench: Is Your Multimodal Language Model Oversensitive to Safe Queries? | Xirui Li       | arxiv   | 2024 | https://arxiv.org/abs/2406.17806 | https://turningpoint-ai.github.io/MOSSBench/          |

### Survey

| Title                                                        | Author  | Publish | Year | Link                              | Source Code                                           |
| ------------------------------------------------------------ | ------- | ------- | ---- | --------------------------------- | ----------------------------------------------------- |
| Safety of Multimodal Large Language Models on Images and Texts | Xin Liu | arxiv   | 2024 | https://arxiv.org//abs/2402.00357 | [null](https://github.com/EddyLuo1232/JailBreakV_28K) |

## Poisoning/Backdoor 

### Attack

| Title                                                        | First Author | Publish | Year | Link                             | Source Code                                    |
| ------------------------------------------------------------ | ------------ | ------- | ---- | -------------------------------- | ---------------------------------------------- |
| Shadowcast: Stealthy Data Poisoning Attacks Against Vision-Language Models | Yuancheng Xu | arxiv   | 2024 | https://arxiv.org/abs/2402.06659 | https://github.com/umd-huang-lab/VLM-Poisoning |
| Test-Time Backdoor Attacks on Multimodal Large Language Models | Dong Lu      | arxiv   | 2024 | https://arxiv.org/abs/2402.08577 | https://sail-sg.github.io/AnyDoor/             |
| VL-Trojan: Multimodal Instruction Backdoor Attacks against Autoregressive Visual Language Models | Jiawei Liang | arxiv   | 2024 | https://arxiv.org/abs/2402.13851 | null                                           |
| Physical Backdoor Attack can Jeopardize Driving with Vision-Large-Language Models | Zhenyang Ni  | arxiv   | 2024 | https://arxiv.org/abs/2404.12916 | null                                           |

## Adversarial

### Attack

| Title                                                        | First Author         | Publish         | Year | Link                                     | Source Code                                  |
| ------------------------------------------------------------ | -------------------- | --------------- | ---- | ---------------------------------------- | -------------------------------------------- |
| Understanding Zero-Shot Adversarial Robustness for Large-Scale Models | Chengzhi Mao         | arxiv           | 2022 | https://arxiv.org/abs/2212.07016         | null                                         |
| On Evaluating Adversarial Robustness of Large Vision-Language Models | Yunqing Zhao         | arxiv           | 2023 | https://arxiv.org/abs/2305.16934         | https://github.com/yunqing-me/AttackVLM      |
| On the Adversarial Robustness of Multi-Modal Foundation Models | Christian Schlarmann | ICCV AROW       | 2023 | https://arxiv.org/abs/2308.10741         | null                                         |
| Adversarial Illusions in Multi-Modal Embeddings              | Tingwei Zhang        | USENIX Security | 2023 | https://arxiv.org/abs/2308.11804         | null                                         |
| Image Hijacks: Adversarial Images can Control Generative Models at Runtime | Luke Bailey          | arxiv           | 2023 | https://arxiv.org/abs/2309.00236         | null                                         |
| How Robust is Google's Bard to Adversarial Image Attacks?    | Yinpeng Dong         | arxiv           | 2023 | https://arxiv.org/abs/2309.11751         | https://github.com/thu-ml/Attack-Bard        |
| An Image Is Worth 1000 Lies: Transferability of Adversarial Images across Prompts on Vision-Language Models | Haochen Luo          | ICLR            | 2024 | https://openreview.net/pdf?id=nc5GgFAvtk | https://github.com/Haochen-Luo/CroPA         |
| Inducing High Energy-Latency of Large Vision-Language Models with Verbose Images | Kuofeng Gao          | ICLR            | 2024 | https://openreview.net/pdf?id=BteuUysuXX | https://github.com/KuofengGao/Verbose_Images |
| Hijacking Context in Large Multi-modal Models                | Joonhyun Jeong       | arxiv           | 2023 | https://arxiv.org/abs/2312.07553         | null                                         |
| On the Robustness of Large Multimodal Models Against Image Adversarial Attacks | Xuanming Cui         | arxiv           | 2023 | https://arxiv.org/abs/2312.03777         | null                                         |
| InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models | Xunguang Wang        | arxiv           | 2023 | https://arxiv.org/abs/2312.01886         | https://github.com/xunguangwang/InstructTA   |
| Stop Reasoning! When Multimodal LLMs with Chain-of-Thought Reasoning Meets Adversarial Images |                      | arxiv           | 2024 | https://arxiv.org/abs/2402.14899         | null                                         |

### Benchmark

| Title                                                        | First Author | Publish | Year | Link                                                         | Source Code |
| ------------------------------------------------------------ | ------------ | ------- | ---- | ------------------------------------------------------------ | ----------- |
| AVIBench: Towards Evaluating the Robustness of Large Vision-Language Model on Adversarial Visual-Instructions | Hao Zhang    | arxiv   | 2024 | https://arxiv.org/abs/2403.09346                             | null        |
| Transferable Multimodal Attack on Vision-Language Pre-training Models | Haodi Wang   | S&P     | 2024 | https://www.computer.org/csdl/proceedings-article/sp/2024/313000a102/1Ub239H4xyg | null        |

## Hallucination

| Title                                                        | First Author | Publish | Year | Link                                     | Source Code                                     |
| ------------------------------------------------------------ | ------------ | ------- | ---- | ---------------------------------------- | ----------------------------------------------- |
| Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning | Fuxiao Liu   | ICLR    | 2024 | https://openreview.net/pdf?id=J44HfH4JCg | https://github.com/FuxiaoLiu/LRV-Instruction    |
| Analyzing and Mitigating Object Hallucination in Large Vision-Language Models | Yiyang Zhou  | ICLR    | 2024 | https://openreview.net/pdf?id=oZDJKTlOUe | https://github.com/YiyangZhou/LURE              |
| A Survey on Hallucination in Large Vision-Language Models    | Hanchao Liu  | arxiv   | 2024 | https://arxiv.org/abs/2402.00253         | null                                            |
| Mitigating Object Hallucination in Large Vision-Language Models via Classifier-Free Guidance | Linxi Zhao   | arxiv   | 2024 | https://arxiv.org/abs/2402.08680         | null                                            |
| Seeing is Believing: Mitigating Hallucination in Large Vision-Language Models via CLIP-Guided Decoding | Ailin Deng   | arxiv   | 2024 | https://arxiv.org/abs/2402.15300         | https://github.com/d-ailin/CLIP-Guided-Decoding |
| Detecting and Mitigating Hallucination in Large Vision Language Models via Fine-Grained AI Feedback | Wenyi Xiao   | arxiv   | 2024 | https://arxiv.org/abs/2404.14233         | null                                            |
| Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding | Xintong Wang | arxiv   | 2024 | https://arxiv.org/abs/2403.18715         | null                                            |
| HallusionBench: An Advanced Diagnostic Suite for Entangled Language Hallucination and Visual Illusion in Large Vision-Language Models | Tianrui Guan | CVPR    | 2024 | https://arxiv.org/abs/2310.14566         | https://github.com/tianyi-lab/HallusionBench    |

### Bias



| Title                                                        | First Author | Publish | Year | Link                             | Source Code                    |
| ------------------------------------------------------------ | ------------ | ------- | ---- | -------------------------------- | ------------------------------ |
| Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges | Chenhang Cui | arxiv   | 2023 | https://arxiv.org/abs/2311.03287 | https://github.com/gzcch/Bingo |

### Others

| Title                                                        | First Author  | Publish         | Year | Link                             | Source Code |
| ------------------------------------------------------------ | ------------- | --------------- | ---- | -------------------------------- | ----------- |
| Zero shot VLMs for hate meme detection: Are we there yet?    | Naquee Rizwan | arxiv           | 2024 | https://arxiv.org/abs/2402.12198 | null        |
| MemeCraft: Contextual and Stance-Driven Multimodal Meme Generation | Han Wang      | ACM MM          | 2024 | https://arxiv.org/abs/2403.14652 | null        |
| Moderating Illicit Online Image Promotion for Unsafe User-Generated Content Games Using Large Vision-Language Models | Keyan Guo     | USENIX Security | 2024 | https://arxiv.org/abs/2403.18957 | null        |

# T2I

## IP

### Protection

| Title                                                        | Author          | Publish         | Year | Link                             | Source Code                                         |
| ------------------------------------------------------------ | --------------- | --------------- | ---- | -------------------------------- | --------------------------------------------------- |
|                                                              |                 |                 |      |                                  |                                                     |
| AIGC-Chain: A Blockchain-Enabled Full Lifecycle Recording System for AIGC Product Copyright Management | Jiajia Jiang    | arixv           | 2024 | https://arxiv.org/abs/2406.14966 | null                                                |
| PID: Prompt-Independent Data Protection Against Latent Diffusion Models | Ang Li          | arxiv           | 2024 | https://arxiv.org/abs/2406.15305 | null                                                |
| Glaze: Protecting Artists from Style Mimicry by Text-to-Image Models | Shawn Shan      | USENIX Security | 2023 | https://arxiv.org/abs/2302.04222 | null                                                |
| Generative Watermarking Against Unauthorized Subject-Driven Image Synthesis | Yihan Ma        | arxiv           | 2023 | https://arxiv.org/abs/2306.07754 | null                                                |
| Toward effective protection against diffusion based mimicry through score distillation | Haotian Xue     | arxiv           | 2023 | https://arxiv.org/abs/2311.12832 | https://github.com/xavihart/Diff-Protect            |
| A Watermark-Conditioned Diffusion Model for IP Protection    | Rui Min         | arxiv           | 2024 | https://arxiv.org/abs/2403.10893 | null                                                |
| RAW: A Robust and Agile Plug-and-Play Watermark Framework for AI-Generated Images with Provable Guarantees | Xun Xian        | arxiv           | 2024 | https://arxiv.org/abs/2403.18774 | null                                                |
| A Training-Free Plug-and-Play Watermark Framework for Stable Diffusion | Guokai Zhang    | arxiv           | 2024 | https://arxiv.org/abs/2404.05607 | null                                                |
| Gaussian Shading: Provable Performance-Lossless Image Watermarking for Diffusion Models | Zijin Yang      | arxiv           | 2024 | https://arxiv.org/abs/2404.04956 | null                                                |
| Lazy Layers to Make Fine-Tuned Diffusion Models More Traceable | Haozhe Liu      | arxiv           | 2024 | https://arxiv.org/abs/2405.00466 | null                                                |
| DiffuseTrace: A Transparent and Flexible Watermarking Scheme for Latent Diffusion Model | Liangqi Lei     | arxiv           | 2024 | https://arxiv.org/abs/2405.02696 | null                                                |
| AquaLoRA: Toward White-box Protection for Customized Stable Diffusion Models via Watermark LoRA | Weitao Feng     | arxiv           | 2024 | https://arxiv.org/abs/2405.11135 | null                                                |
| A Recipe for Watermarking Diffusion Models                   | Yunqing Zhao    | arixv           | 2023 | https://arxiv.org/abs/2303.10137 | https://github.com/yunqing-me/WatermarkDM           |
| Watermarking Diffusion Model                                 | Yugeng Liu      | arxiv           | 2023 | https://arxiv.org/abs/2305.12502 | null                                                |
| Tree-Ring Watermarks: Fingerprints for Diffusion Images that are Invisible and Robust | Yuxin Wen       | arxiv           | 2023 | https://arxiv.org/abs/2305.20030 | https://github.com/YuxinWenRick/tree-ring-watermark |
| Generative Models are Self-Watermarked: Declaring Model Authentication through Re-Generation | Aditya Desu     | arxiv           | 2024 | https://arxiv.org/abs/2402.16889 | null                                                |
| Erasing Concepts from Diffusion Models                       | Rohit Gandikota | arxiv           | 2023 | https://arxiv.org/abs/2303.07345 | https://erasing.baulab.info/                        |
| Adversarial Example Does Good: Preventing Painting Imitation from Diffusion Models via Adversarial Examples | Chumeng Liang   | ICML            | 2023 | https://arxiv.org/abs/2302.04578 | https://github.com/mist-project/mist.git            |

### Violation

| Title                                                        | Author       | Publish | Year | Link                                     | Source Code                                               |
| ------------------------------------------------------------ | ------------ | ------- | ---- | ---------------------------------------- | --------------------------------------------------------- |
| A Transfer Attack to Image Watermarks                        | Yuepeng Hu   | arxiv   | 2024 | https://arxiv.org/abs/2403.15365         | null                                                      |
| Disguised Copyright Infringement of Latent Diffusion Models  | Yiwei Lu     | arxiv   | 2024 | https://arxiv.org/abs/2404.06737         | https://github.com/watml/disguised_copyright_infringement |
| Stable Signature is Unstable: Removing Image Watermark from Diffusion Models | Yuepeng Hu   | arxiv   | 2024 | https://arxiv.org/abs/2405.07145         | null                                                      |
| UnMarker: A Universal Attack on Defensive Watermarking       | Andre Kassis | arxiv   | 2024 | https://arxiv.org/abs/2405.08363         | null                                                      |
| FreezeAsGuard: Mitigating Illegal Adaptation of Diffusion Models via Selective Tensor Freezing | Kai Huang    | arxiv   | 2024 | https://arxiv.org/abs/2405.17472         | null                                                      |
| Adversarial Perturbations Cannot Reliably Protect Artists From Generative AI | Robert Hönig | arxiv   | 2024 | https://arxiv.org/abs/2406.12027         | null                                                      |
| EnTruth: Enhancing the Traceability of Unauthorized Dataset Usage in Text-to-image Diffusion Models with Minimal and Robust Alterations | Jie Ren      | arxiv   | 2024 | https://arxiv.org/abs/2406.13933         | null                                                      |
| Leveraging Optimization for Adaptive Attacks on Image Watermarks | Nils Lukas   | ICLR    | 2024 | https://openreview.net/pdf?id=O9PArxKLe1 | null                                                      |

### Survey

| Title                                                        | Author  | Publish | Year | Link                             | Source Code |
| ------------------------------------------------------------ | ------- | ------- | ---- | -------------------------------- | ----------- |
| Copyright Protection in Generative AI: A Technical Perspective | Jie Ren | arxiv   | 2024 | https://arxiv.org/abs/2402.02333 | null        |

## Privacy

### Attack

| Title                                                        | Author              | Publish | Year | Link                                     | Source Code                                 |
| ------------------------------------------------------------ | ------------------- | ------- | ---- | ---------------------------------------- | ------------------------------------------- |
| Recovering the Pre-Fine-Tuning Weights of Generative Models  | Eliahu Horwitz      | arxiv   | 2024 | https://arxiv.org/abs/2402.10208         | null                                        |
| Membership Inference Attacks Against Text-to-image Generation Models | Yixin Wu            | arxiv   | 2022 | https://arxiv.org/abs/2210.00968         | null                                        |
| Class Attribute Inference Attacks: Inferring Sensitive Class Information by Diffusion-Based Attribute Manipulations | Lukas Struppek      | arxiv   | 2023 | https://arxiv.org/abs/2303.09289         | null                                        |
| White-box Membership Inference Attacks against Diffusion Models | Yan Pang            | arxiv   | 2023 | https://arxiv.org/abs/2308.06405         | null                                        |
| An Efficient Membership Inference Attack for the Diffusion Model by Proximal Initialization | Fei Kong            | ICLR    | 2024 | https://openreview.net/pdf?id=rpH9FcCEV6 | https://github.com/kong13661/PIA            |
| Black-box Membership Inference Attacks against Fine-tuned Diffusion Models | Yan Pang            | arxiv   | 2023 | https://arxiv.org/abs/2312.08207         | null                                        |
| Prompt Stealing Attacks Against Text-to-Image Generation Models | Xinyue Shen         | arxiv   | 2023 | https://arxiv.org/abs/2302.09923         | null                                        |
| Shake to Leak: Fine-tuning Diffusion Models Can Amplify the Generative Privacy Risk | Zhangheng Li        | arxiv   | 2024 | https://arxiv.org/html/2403.09450v1      | https://github.com/VITA-Group/Shake-to-Leak |
| Is Diffusion Model Safe? Severe Data Leakage via Gradient-Guided Diffusion Model | Jiayang Meng        | arxiv   | 2024 | https://arxiv.org/abs/2406.09484         | null                                        |
| Extracting Training Data from Unconditional Diffusion Models | Yunhao Chen         | arxiv   | 2024 | https://arxiv.org/abs/2406.12752         | null                                        |
| Extracting Training Data from Diffusion Models               | Nicholas Carlini    | arxiv   | 2023 | https://arxiv.org/abs/2301.13188         | null                                        |
| Towards Black-Box Membership Inference Attack for Diffusion Models | Jingwei Li          | arxiv   | 2024 | https://arxiv.org/abs/2405.20771         | null                                        |
| Visual Privacy Auditing with Diffusion Models                | Kristian Schwethelm | arxiv   | 2024 | https://arxiv.org/abs/2403.07588         | null                                        |
| Membership Inference on Text-to-Image Diffusion Models via Conditional Likelihood Discrepancy | Shengfang Zhai      | arxiv   | 2024 | https://arxiv.org/abs/2405.14800         | null                                        |
| Extracting Prompts by Inverting LLM Outputs                  | Collin Zhang        | arxiv   | 2024 | https://arxiv.org/abs/2405.15012         | null                                        |

### Defense

| Title                                                        | Author        | Publish | Year | Link                                     | Source Code                                          |
| ------------------------------------------------------------ | ------------- | ------- | ---- | ---------------------------------------- | ---------------------------------------------------- |
| Differentially Private Fine-Tuning of Diffusion Models       | Yu-Lin Tsai   | arxiv   | 2024 | https://arxiv.org/abs/2406.01355         | https://anonymous.4open.science/r/DP-LORA-F02F       |
| Privacy-Preserving Diffusion Model Using Homomorphic Encryption | Yaojian Chen  | arxiv   | 2024 | https://arxiv.org/abs/2403.05794         | null                                                 |
| Efficient Differentially Private Fine-Tuning of Diffusion Models | Jing Liu      | arxiv   | 2024 | https://arxiv.org/abs/2406.05257         | null                                                 |
| Differentially Private Synthetic Data via Foundation Model APIs 1: Images | Zinan Lin     | ICLR    | 2024 | https://openreview.net/pdf?id=YEhQs8POIo | https://github.com/microsoft/DPSDA                   |
| Anti-DreamBooth: Protecting users from personalized text-to-image synthesis | Thanh Van Le  | ICCV    | 2023 | https://arxiv.org/abs/2303.15433         | https://github.com/VinAIResearch/Anti-DreamBooth.git |
| Unlearnable Examples for Diffusion Models: Protect Data from Unauthorized Exploitation | Zhengyue Zhao | arxiv   | 2023 | https://arxiv.org/abs/2306.01902         | null                                                 |
| Can Protective Perturbation Safeguard Personal Data from Being Exploited by Stable Diffusion? | Zhengyue Zhao | arxiv   | 2023 | https://arxiv.org/abs/2312.00084         | null                                                 |
| MetaCloak: Preventing Unauthorized Subject-driven Text-to-image Diffusion-based Synthesis via Meta-learning | Yixin Liu     | arxiv   | 2023 | https://arxiv.org/abs/2311.13127         | https://github.com/liuyixin-louis/MetaCloak          |

### Benchmark

| Title                                                        | Author      | Publish | Year | Link                             | Source Code                              |
| ------------------------------------------------------------ | ----------- | ------- | ---- | -------------------------------- | ---------------------------------------- |
| Raccoon: Prompt Extraction Benchmark of LLM-Integrated Applications | Junlin Wang | arxiv   | 2024 | https://arxiv.org/abs/2406.06737 | https://github.com/M0gician/RaccoonBench |

## Memorization

| Title                                                        | Author       | Publish | Year | Link                                     | Source Code                                               |
| ------------------------------------------------------------ | ------------ | ------- | ---- | ---------------------------------------- | --------------------------------------------------------- |
| SalUn: Empowering Machine Unlearning via Gradient-based Weight Saliency in Both Image Classification and Generation | Chongyu Fan  | ICLR    | 2024 | https://openreview.net/pdf?id=gn0mIhQGNM | https://github.com/OPTML-Group/Unlearn-Saliency           |
| Ring-A-Bell! How Reliable are Concept Removal Methods For Diffusion Models? | Yu-Lin Tsai  | ICLR    | 2024 | https://openreview.net/pdf?id=lm7MRcsFiS | https://github.com/chiayi-hsu/Ring-A-Bell                 |
| Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models | Yimeng Zhang | arxiv   | 2024 | https://arxiv.org/abs/2405.15234         | https://github.com/OPTML-Group/AdvUnlearn                 |
| Espresso: Robust Concept Filtering in Text-to-Image Models   | Anudeep Das  | arxiv   | 2024 | https://arxiv.org/abs/2404.19227         | null                                                      |
| Machine Unlearning for Image-to-Image Generative Models      | Guihong Li   | arxiv   | 2024 | https://arxiv.org/abs/2402.00351         | https://github.com/jpmorganchase/l2l-generator-unlearning |
| MACE: Mass Concept Erasure in Diffusion Models               | Shilin Lu    | arxiv   | 2024 | https://arxiv.org/abs/2403.06135         | https://github.com/Shilin-LU/MACE                         |
| Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention | Jie Ren      | arxiv   | 2024 | https://arxiv.org/abs/2403.11052         | https://github.com/renjie3/MemAttn                        |
| Could It Be Generated? Towards Practical Analysis of Memorization in Text-To-Image Diffusion Models | Zhe Ma       | arxiv   | 2024 | https://arxiv.org/abs/2405.05846         | null                                                      |

## Deepfake

### Construction

| Title                                                        | Author                  | Publish | Year | Link                                     | Source Code                                           |
| ------------------------------------------------------------ | ----------------------- | ------- | ---- | ---------------------------------------- | ----------------------------------------------------- |
| An Analysis of Recent Advances in Deepfake Image Detection in an Evolving Threat Landscape | Sifat Muhammad Abdullah | S&P     | 2024 | https://arxiv.org/abs/2404.16212         | null                                                  |
| Robustness of AI-Image Detectors: Fundamental Limits and Practical Attacks | Mehrdad Saberi          | ICLR    | 2024 | https://openreview.net/pdf?id=dLoAdIKENc | https://github.com/mehrdadsaberi/watermark_robustness |

### Detection

| Title                                                        | Author                  | Publish | Year | Link                             | Source Code |
| ------------------------------------------------------------ | ----------------------- | ------- | ---- | -------------------------------- | ----------- |
| DeepFake-O-Meter v2.0: An Open Platform for DeepFake Detection | Yan Ju                  | arxiv   | 2024 | https://arxiv.org/abs/2404.13146 | null        |
| DE-FAKE: Detection and Attribution of Fake Images Generated by Text-to-Image Generation Models | Zeyang Sha              | arxiv   | 2022 | https://arxiv.org/abs/2210.06998 | null        |
| Organic or Diffused: Can We Distinguish Human Art from AI-generated Images? | Anna Yoo Jeong Ha       | arxiv   | 2024 | https://arxiv.org/abs/2402.03214 | null        |
| Watermark-based Detection and Attribution of AI-Generated Content | Zhengyuan Jiang         | arxiv   | 2024 | https://arxiv.org/abs/2404.04254 | null        |
| An Analysis of Recent Advances in Deepfake Image Detection in an Evolving Threat Landscape | Sifat Muhammad Abdullah | S&P     | 2024 | https://arxiv.org/abs/2404.16212 | null        |

### Benchmark

| Title                                                        | Author    | Publish | Year | Link                             | Source Code |
| ------------------------------------------------------------ | --------- | ------- | ---- | -------------------------------- | ----------- |
| The Adversarial AI-Art: Understanding, Generation, Detection, and Benchmarking | Yuying Li | arxiv   | 2024 | https://arxiv.org/abs/2404.14581 | null        |

## Bias

| Title                                                        | Author      | Publish | Year | Link                                     | Source Code                                        |
| ------------------------------------------------------------ | ----------- | ------- | ---- | ---------------------------------------- | -------------------------------------------------- |
| Finetuning Text-to-Image Diffusion Models for Fairness       | Xudong Shen | ICLR    | 2024 | https://openreview.net/pdf?id=hnrB5YHoYu | https://sail-sg.github.io/finetune-fair-diffusion/ |
| ViSAGe: A Global-Scale Analysis of Visual Stereotypes in Text-to-Image Generation | Akshita Jha | arxiv   | 2024 | https://arxiv.org/abs/2401.06310         | null                                               |

## Backdoor

### Attack

| Title                                                        | Author         | Publish | Year | Link                             | Source Code |
| ------------------------------------------------------------ | -------------- | ------- | ---- | -------------------------------- | ----------- |
| Rickrolling the Artist: Injecting Backdoors into Text Encoders for Text-to-Image Synthesis | Lukas Struppek | ICCV    | 2023 | https://arxiv.org/abs/2211.02408 | null        |
| Generating Potent Poisons and Backdoors from Scratch with Guided Diffusion | Hossein Souri  | arxiv   | 2024 | https://arxiv.org/abs/2403.16365 | null        |

### Defense

| Title                                                        | Author        | Publish          | Year | Link                             | Source Code                                                  |
| ------------------------------------------------------------ | ------------- | ---------------- | ---- | -------------------------------- | ------------------------------------------------------------ |
| Diffusion Denoising as a Certified Defense against Clean-label Poisoning | Sanghyun Hong | arxiv            | 2024 | https://arxiv.org/abs/2403.11981 | null                                                         |
| Leveraging Diffusion-Based Image Variations for Robust Training on Poisoned Data |               | NeurIPS Workshop | 2023 | https://arxiv.org/abs/2310.06372 | null                                                         |
| UFID: A Unified Framework for Input-level Backdoor Detection on Diffusion Models | Zihan Guan    | arxiv            | 2024 | https://arxiv.org/abs/2404.01101 | https://github.com/GuanZihan/official_UFID                   |
| Invisible Backdoor Attacks on Diffusion Models               |               | arxiv            | 2024 | https://arxiv.org/abs/2406.00816 | https://github.com/invisibleTriggerDiffusion/invisible_triggers_for_diffusion |
| Watch the Watcher! Backdoor Attacks on Security-Enhancing Diffusion Models | Changjiang Li | arxiv            | 2024 | https://arxiv.org/abs/2406.09669 | null                                                         |
| Injecting Bias in Text-To-Image Models via Composite-Trigger Backdoors | Ali Naseh     | arxiv            | 2024 | https://arxiv.org/abs/2406.15213 | null                                                         |

## Adversarial

### Attack

| Title                                                        | Author         | Publish | Year | Link                             | Source Code                                                  |
| ------------------------------------------------------------ | -------------- | ------- | ---- | -------------------------------- | ------------------------------------------------------------ |
| Diffusion-Based Adversarial Sample Generation for Improved Stealthiness and Controllability | Haotian Xue    | NeurIPS | 2023 | https://arxiv.org/abs/2305.16494 | https://github.com/xavihart/Diff-PGD                         |
| Stable Diffusion is Unstable                                 | Chengbin Du    | arxiv   | 2023 | https://arxiv.org/abs/2306.02583 | null                                                         |
| DiffAttack: Evasion Attacks Against Diffusion-Based Adversarial Purification | Mintong Kang   | NeurIPS | 2023 | https://arxiv.org/abs/2311.16124 | null                                                         |
| Exploring Adversarial Attacks against Latent Diffusion Model from the Perspective of Adversarial Transferability | Junxi Chen     | arxiv   | 2024 | https://arxiv.org/abs/2401.07087 | null                                                         |
| Revealing Vulnerabilities in Stable Diffusion via Targeted Attacks | Chenyu Zhang   | arxiv   | 2024 | https://arxiv.org/abs/2401.08725 | https://github.com/datar001/Revealing-Vulnerabilities-in-Stable-Diffusion-via-Targeted-Attacks |
| Cheating Suffix: Targeted Attack to Text-To-Image Diffusion Models with Multi-Modal Priors | Dingcheng Yang | arxiv   | 2024 | https://arxiv.org/abs/2402.01369 | https://github.com/ydc123/MMP-Attack                         |
| Groot: Adversarial Testing for Generative Text-to-Image Models with Tree-based Semantic Transformation | Yi Liu         | arxiv   | 2024 | https://arxiv.org/abs/2402.12100 | null                                                         |
| BSPA: Exploring Black-box Stealthy Prompt Attacks against Image Generators | Yu Tian        | arxiv   | 2024 | https://arxiv.org/abs/2402.15218 | null                                                         |
| Perturbing Attention Gives You More Bang for the Buck: Subtle Imaging Perturbations That Efficiently Fool Customized Diffusion Models | Jingyao Xu     | arxiv   | 2024 | https://arxiv.org/abs/2404.15081 | null                                                         |
| Investigating and Defending Shortcut Learning in Personalized Diffusion Models | Yixin Liu      | arxiv   | 2024 | https://arxiv.org/abs/2406.18944 | null                                                         |
| Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models | Yiting Qu      | arxiv   | 2024 | https://arxiv.org/abs/2305.13873 | null                                                         |
| ART: Automatic Red-teaming for Text-to-Image Models to Protect Benign Users |                | arxiv   | 2024 | https://arxiv.org/abs/2405.19360 | https://github.com/GuanlinLee/ART                            |

### Defense

| Title                                                        | Author        | Publish | Year | Link                             | Source Code                     |
| ------------------------------------------------------------ | ------------- | ------- | ---- | -------------------------------- | ------------------------------- |
| Raising the Cost of Malicious AI-Powered Image Editing       | Hadi Salman   | arxiv   | 2023 | https://arxiv.org/abs/2302.06588 | null                            |
| Adversarial Examples are Misaligned in Diffusion Model Manifolds | Peter Lorenz  | arxiv   | 2024 | https://arxiv.org/abs/2401.06637 | null                            |
| Universal Prompt Optimizer for Safe Text-to-Image Generation | Zongyu Wu     | NAACL   | 2024 | https://arxiv.org/abs/2402.10882 | https://github.com/wzongyu/POSI |
| Adversarial Nibbler: An Open Red-Teaming Method for Identifying Diverse Harms in Text-to-Image Generation | Jessica Quaye | arxiv   | 2024 | https://arxiv.org/abs/2403.12075 | null                            |
| SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models | Xinfeng Li    | arxiv   | 2024 | https://arxiv.org/abs/2404.06666 | null                            |


# Competition

| Title                                                        | Organizer               | Year | Link                                                         | Category |
| ------------------------------------------------------------ | ----------------------- | ---- | ------------------------------------------------------------ | -------- |
|                                                              |                         |      |                                                              |          |
| Machine Learning Model Attribution Challenge                 | MITRE                   | 2022 | https://mlmac.io/                                            | Privacy  |
| Training Data Extraction Challenge                           | Google                  | 2022 | https://github.com/google-research/lm-extraction-benchmark   | Privacy  |
| Find the Trojan: Universal Backdoor Detection in Aligned LLMs | ETHZ                    | 2024 | https://github.com/ethz-spylab/rlhf_trojan_competition       | Security |
| LLM - Detect AI Generated Text                               | The Learning Agency Lab | 2023 | https://www.kaggle.com/competitions/llm-detect-ai-generated-text/overview | Deepfake |
| Deepfake Detection Challenge                                 | Kaggle                  | 2019 | https://www.kaggle.com/c/deepfake-detection-challenge        | Deepfake |
| Large Language Model Capture-the-Flag (LLM CTF) Competition  | Kaggle                  | 2024 | https://ctf.spylab.ai/                                       | Safety   |

# Leaderboard

| Title                                                        | First Author       | Publish | Year | Link                                                         |
| ------------------------------------------------------------ | ------------------ | ------- | ---- | ------------------------------------------------------------ |
| LLM Safety Leaderboard                                       | Boxin Wang         | NeurIPS | 2023 | https://huggingface.co/spaces/AI-Secure/llm-trustworthy-leaderboard |
| Hallucinations Leaderboard                                   | Pasquale Minervini | null    | 2023 | https://huggingface.co/spaces/hallucinations-leaderboard/leaderboard |
| [JailbreakBench](https://jailbreakbench.github.io/)          | Patrick Chao       | arxiv   | 2024 | https://jailbreakbench.github.io/                            |
| A Comprehensive Study of Trustworthiness in Large Language Models. | Lichao Sun         | arxiv   | 2024 | https://trustllmbenchmark.github.io/TrustLLM-Website/leaderboard.html |
| PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts | Kaijie Zhu         | arxiv   | 2023 | https://llm-eval.github.io/pages/leaderboard/advprompt.html  |
| Leaderboard Comparing LLM Performance at Producing Hallucinations when Summarizing Short Documents | Vectara            | github  | 2023 | https://github.com/vectara/hallucination-leaderboard         |

# Arena

| Title                                                        | Institution     | Year | Link                                                       |
| ------------------------------------------------------------ | --------------- | ---- | ---------------------------------------------------------- |
| LMSYS Chatbot Arena (Multimodal): Benchmarking LLMs and VLMs in the Wild | LMSYS Org       | 2024 | https://arena.lmsys.org/                                   |
| 中文大模型竞技场                                             | ModelScope      | 2024 | https://modelscope.cn/studios/LLMZOO/Chinese-Arena/summary |
| 司南 OpenCompass 大模型竞技场                                | Shanghai AI Lab | 2024 | https://opencompass.org.cn/arena                           |
| 模型广场                                                     | Coze            | 2024 | https://www.coze.cn/model/arena                            |

# Book

| Title                                                        | Author             | Publish        | Year | Link                                                        |
| ------------------------------------------------------------ | ------------------ | -------------- | ---- | ----------------------------------------------------------- |
| Adversarial Machine Learning A Taxonomy and Terminology of Attacks and Mitigations | Apostol Vassilev   | online         | 2024 | https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2023.pdf |
| 人工智能安全                                                 | 方滨兴             | 电子工业出版社 | 2022 | null                                                        |
| 人工智能安全                                                 | 曾剑平             | 清华大学出版社 | 2022 | null                                                        |
| 人工智能安全                                                 | 陈左宁             | 电子工业出版社 | 2024 | null                                                        |
| AI安全:技术与实战                                            | 腾讯安全朱雀实验室 | 电子工业出版社 | 2022 | null                                                        |
| Trustworthy Machine Learning                                 | Kush R. Varshney   | null           | 2022 | null                                                        |
| 人工智能:数据与模型安全                                      | 姜育刚             | 机械工业出版社 | 2024 | null                                                        |

---




---

[![Star History Chart](https://api.star-history.com/svg?repos=NY1024/Awesome-Trustworthy-GenAI&type=Date)](https://star-history.com/#NY1024/Awesome-Trustworthy-GenAI&Date)

---
- Organizers: [Zonghao Ying(应宗浩)](https://elwood.me/)

<p align="center"><img src="figs/1.png"/></p>
