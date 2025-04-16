# Awesome Fed Reasoning in Large Language Models

[![Awesome](https://awesome.re/badge.svg)](https://github.com/jeffhj/LM-reasoning) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

This repository contains a collection of papers and resources on ***Fed Reasoning in Large Language Models***.

For more details, please refer to [ourwork]()



## Contents

- [Survey](#survey)
- [Training Signal from Raw Data](#training-signal-from-raw-data)
  - [Federated Supervised Pre-Training](#federated-supervised-pre-training)
  - [Federated Supervised Instruction-Tuning](#federated-supervised-instruction-tuning)
  - [Privacy and Safety Risk in Fed-SL of rLLMs](#privacy-and-safety-risk-in-fed-sl-of-rllms)
- [Training Signal from Representation](#training-signal-from-representation)
  - [Federated Prompt Learning](#federated-prompt-learning)
  - [Federated Adapter Learning](#federated-adapter-learning)
  - [Federated Knowledge Distillation](#federated-knowledge-distillation)
  - [Privacy and Safety Risk in Fed-TL of rLLMs](#privacy-and-safety-risk-in-fed-tl-of-rllms)
- [Training Signal From Preference](#training-signal-from-preference)
- [Open Platforms and Applications](#open-platforms-and-applications)



## Survey {#survey}




## Training Signal from Raw Data {#training-signal-from-raw-data}


###  Federated Supervised Pre-Training {#federated-supervised-pre-training}

#### [The future of large language model pre-training is federated](https://neurips.cc/virtual/2024/103959) *Dec 2024 NeurIPS Workshop*

Sai Praneeth Karimireddy, Xiaoxiao Li, Songtao Lu, Stacy Patterson, Pascal Poupart , Han Yu

#### [Ferret: Federated Full-Parameter Tuning at Scale for Large Language Models](https://arxiv.org/abs/2409.06277) *Sep 2024 NeurIPS Workshop*

Yao Shu, Wenyang Hu, See-Kiong Ng, Bryan Kian Hsiang Low, Fei Richard Yu

#### [Federated full-parameter tuning of billion-sized language models with communication cost under 18 kilobytes](https://dl.acm.org/doi/10.5555/3692070.3693756) *Jul 2024 ICML*

Zhen Qin, Daoyuan Chen, Bingchen Qian, Bolin Ding, Yaliang Li, Shuiguang Deng

#### [On the Convergence of Zeroth-Order Federated Tuning for Large Language Models](https://dl.acm.org/doi/10.1145/3637528.3671865)  *Aug 2024 KDD*

Zhenqing Ling, Daoyuan Chen, Liuyi Yao, Yaliang Li, Ying Shen

###  Federated Supervised Instruction-Tuning {#federated-supervised-instruction-tuning}

#### [Towards Building The Federatedgpt: Federated Instruction Tuning](https://ieeexplore.ieee.org/abstract/document/10447454) *Mar 2024 ICASSP*

Jianyi Zhang, Saeed Vahidian, Martin Kuo, Chunyuan Li, Ruiyi Zhang, Tong Yu

#### [Federated Instruction Tuning of LLMs with Domain Coverage Augmentation](https://arxiv.org/html/2409.20135v3) *Sep 2024*
Zezhou Wang, Yaxin Du, Zhuzhong Qian

#### [Data Quality Control in Federated Instruction-tuning of Large Language Models](https://arxiv.org/abs/2410.11540) *Oct 2024*
Yaxin Du, Rui Ye, Fengting Yuchi, Wanru Zhao, Jingjing Qu, Yanfeng Wang, Siheng Chen

#### [Federated Data-Efficient Instruction Tuning for Large Language Models](https://arxiv.org/abs/2410.10926) *Mon 2024*

Zhen Qin, Zhaomin Wu, Bingsheng He, Shuiguang Deng

#### [FewFedPIT: Towards Privacy-preserving and Few-shot Federated Instruction Tuning](https://arxiv.org/abs/2403.06131) *Mar 2024*

Zhuo Zhang, Jingyuan Zhang, Jintao Huang, Lizhen Qu, Hongzhi Zhang, Qifan Wang, Xun Zhou, Zenglin Xu

### Privacy and Safety Risk in Fed-SL of rLLMs {#privacy-and-safety-risk-in-fed-sl-of-rllms}

#### [More Than Enough is Too Much: Adaptive Defenses Against Gradient Leakage in Production Federated Learning](https://ieeexplore.ieee.org/document/10477938) *Mar 2024 Trans. Netw*

Fei Wang, Ethan Hugh, Baochun Li

## Traning Signal from Representation {#training-signal-from-representation}

### Federated Prompt Learning {#federated-prompt-learning}

#### [Flexible and Secure Code Deployment in Federated Learning using Large Language Models: Prompt Engineering to Enhance Malicious Code Detection](https://ieeexplore.ieee.org/document/10475813) *Mar 2024 Trans. Netw*

Fei Wang, Ethan Hugh, Baochun Li

#### [Federated adaptive prompt tuning for multi-domain collaborative learning](https://dl.acm.org/doi/10.1609/aaai.v38i13.29434) *Feb 2024 AAAI*

Shangchao Su, Mingzhao Yang, Bin Li, Xiangyang Xue

#### [Let Federated Participants Cooperatively Learn Prompts Instead of Models](https://dl.acm.org/doi/abs/10.1109/TMC.2023.3302410) *May 2024 IEEE Trans. Mob*

#### [FedBPT: Efficient Federated Black-box Prompt Tuning for Large Language Models](https://icml.cc/virtual/2024/poster/34753) *Mon 2023 ICML*

Jingwei Sun, Ziyue Xu, Hongxu Yin, Dong Yang, Daguang Xu, Yudong Liu, Zhixu Du, Yiran Chen, Holger Roth

#### [Probabilistic Federated Prompt-Tuning with Non-IID and Imbalanced Data](https://proceedings.neurips.cc/paper_files/paper/2024/hash/951877b24b376c5f4612e850251ee85b-Abstract-Conference.html) *Sep 2024 NeurIPS*

Pei-Yau Weng, Minh Hoang, Lam M. Nguyen, My T. Thai, Tsui-Wei Weng, Trong Nghia Hoang

### Federated Adapter Learning {#federated-adapter-learning}

#### [ Improving lora in privacy preserving federated learning](https://iclr.cc/virtual/2024/poster/18792) *Mar 2024 ICLR*

Youbang Sun, Zitao Li, Yaliang Li, Bolin Ding

#### [FLoRA: Federated Fine-Tuning Large Language Models with Heterogeneous Low-Rank Adaptations](https://papers.nips.cc/paper_files/paper/2024/hash/28312c9491d60ed0c77f7fff4ad86dd1-Abstract-Conference.html) *Sep 2024 NeurIPS*

Ziyao Wang, Zheyu Shen, Yexiao He, Guoheng Sun, Hongyi Wang, Lingjuan Lyu, Ang Li

#### [Fisher information based efficient curriculum federated learning with  large language models.](https://aclanthology.org/2024.emnlp-main.587/) *Sep 2024 ACL*

Ji Liu, Jiaxiang Ren, Ruoming Jin, Zijie Zhang, Yang Zhou, Patrick Valduriez, Dejing Dou

#### [Dual-Personalizing Adapter for Federated Foundation Models]([45a30141c6719e9cfedfb51f1c665a37-Paper-Conference.pdf](https://proceedings.neurips.cc/paper_files/paper/2024/file/45a30141c6719e9cfedfb51f1c665a37-Paper-Conference.pdf)) *Mar 2024 NeurIPS*

Yiyuan Yang, Guodong Long, Tao Shen, Jing Jiang, Michael Blumenstein

### Federated Knowledge Distillation {#federated-knowledge-distillation}

#### [ Tunable soft prompts are messengers in federated learning](https://aclanthology.org/2023.findings-emnlp.976/) *Dec 2023 EMNLP*

Chenhe Dong, Yuexiang Xie, Bolin Ding, Ying Shen, Yaliang Li

#### [FedMKT: Federated Mutual Knowledge Transfer for Large and Small Language Models](https://aclanthology.org/2025.coling-main.17/) *Jan 2025 ACL*

Tao Fan, Guoqiang Ma, Yan Kang, Hanlin Gu, Yuanfeng Song, Lixin Fan, Kai Chen, Qiang Yang


#### [FedPFT: Federated Proxy Fine-Tuning of Foundation Models](https://www.ijcai.org/proceedings/2024/0531) *Apr 2024 IJCAI*

Zhaopeng Peng, Xiaoliang Fan, Yufan Chen, Zheng Wang, Shirui Pan, Chenglu Wen, Ruisheng Zhang, Cheng Wang

### Privacy and Safety Risk in Fed-TL of rLLMs {#privacy-and-safety-risk-in-fed-tl-of-rllms}

#### [Emerging Safety Attack and Defense in Federated Instruction Tuning of Large Language Models](https://iclr.cc/virtual/2025/poster/28122) *Apr 2025 ICLR*

Rui Ye, Jingyi Chai, Xiangrui Liu, Yaodong Yang, Yanfeng Wang, Siheng Chen

## Training Signal From Preference {#training-signal-from-preference}

#### [PluralLLM: Pluralistic Alignment in LLMs via Federated Learning](https://arxiv.org/abs/2503.09925) *Mar 2025*

Mahmoud Srewa, Tianyu Zhao, Salma Elmalaki

#### [Towards Federated RLHF with Aggregated Client Preference for LLMs](https://iclr.cc/virtual/2025/poster/28445) *Apr 2025 ICLR*

Feijie Wu, Xiaoze Liu, Haoyu Wang, Xingchen Wang, Lu Su, Jing Gao

#### [Cloud-Edge Collaborative Large Model Services: Challenges and Solutions](https://ieeexplore.ieee.org/document/10634552) **

Yanghe Pan, Zhou Su, Yuntao Wang, Shaolong Guo, Han Liu, Ruidong Li


## OpenPlatforms and Applications {#open-platforms-and-applications}

#### [FederatedScope-LLM: A Comprehensive Package for Fine-tuning Large Language Models in Federated Learning](https://dl.acm.org/doi/abs/10.1145/3637528.3671573) *Sep 23 KDD*

Weirui Kuang, Bingchen Qian, Zitao Li, Daoyuan Chen, Dawei Gao, Xuchen Pan, Yuexiang Xie, Yaliang Li, Bolin Ding, Jingren Zhou

#### [FATE-LLM: A Industrial Grade Federated Learning Framework for Large Language Models](https://arxiv.org/abs/2310.10049) *Oct 2023*

Tao Fan, Yan Kang, Guoqiang Ma, Weijing Chen, Wenbin Wei, Lixin Fan, Qiang Yang

#### [OpenFedLLM: Training Large Language Models on Decentralized Private Data via Federated Learning](https://dl.acm.org/doi/10.1145/3637528.3671582) *Aug 2024 KDD*

Rui Ye, Wenhao Wang, Jingyi Chai, Dihan Li, Zexi Li, Yinda Xu, Yaxin Du, Yanfeng Wang, Siheng Chen


#### [I Can't Share Code, but I need Translation -- An Empirical Study on Code Translation through Federated LLM](https://arxiv.org/abs/2501.05724) *Jan 2025*

Jahnavi Kumar, Venkata Lakshmana Sasaank Janapati, Mokshith Reddy Tanguturi, Sridhar Chimalakonda

## 

#### []() **
#### []() **

## Citation

If you find this repo useful, please kindly cite our survey:

```

```
