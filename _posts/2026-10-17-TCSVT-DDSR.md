---
title: "DDSR has been accepted by IEEE TCSVT!"
date: 2026-10-17T11:33:33-03:00
categories:
  - Paper
tags:
  - Journal
  - TCSVT
---

祝贺张哲同学的研究成果被《IEEE Transactions on Circuits and Systems for Video Technology》（TCSVT）录用。张哲为 2024 级硕士研究生，由陈胜勇教授与我联合指导。本篇录用论文是他硕士阶段取得的第一项研究成果，研究方向为黑盒域自适应。IEEE TCSVT 是 IEEE 旗下旗舰期刊，聚焦图像与视频的表征、处理、分析、合成、学习与理解，在中科院期刊分区表中位列 Q1 区。

论文题目：Adaptive Dual-Teacher Distillation with Subnetwork Rectification for Bridging Semantic Gaps in Black-Box Domain Adaptation.

论文摘要如下：黑盒域自适应（BBDA）设定下，源域数据与源模型参数均不可获取，是一类具备极高实用价值、同时极具挑战性的任务。在该场景中，可迁移知识仅能从黑盒源模型的预测输出中获取。现有方法一般通过伪标签优化或利用视觉语言模型（ViL）挖掘这类知识，但往往难以调和黑盒模型输出的任务专属知识与视觉语言模型具备的对齐语言语义先验之间固有的差异，造成两类知识融合效果不佳，域自适应性能下降。针对该难题，本文提出**带子网校正的自适应双教师蒸馏框架（DDSR）**，该框架能够显式地协调这两组互补但存在冲突的知识源。DDSR 采用自适应预测融合策略，融合黑盒源模型与视觉语言模型的预测结果，为目标域生成可靠伪标签；基于子网的正则化机制通过约束输出一致性与梯度差异性，缓解模型对噪声监督信号的过拟合问题。此外，持续迭代优化得到的目标域预测结果会不断优化伪标签与视觉语言模型提示词，进一步强化语义对齐。最后，借助类别原型，通过自训练进一步优化目标域预测结果。在多组基准数据集上开展大量实验，结果表明：DDSR 在现有的黑盒域自适应方法中取得了当前最优性能，同时相比许多能够访问源域数据或源模型参数的方法，本方法依然具备不俗竞争力。代码开源地址：[https://github.com/iamjingli/DDSR.](https://github.com/iamjingli/DDSR)

Congratulations to Zhe Zhang for having his research accepted by IEEE Transactions on Circuits and Systems for Video Technology (TCSVT). Zhe Zhang is a master student enrolled in 2024, co-supervised by Professor Shengyong Chen and me. This accepted paper marks his 1st research achievement during his master studies, focusing on black-box domain adaptation. IEEE TCSVT is a flagship journal of the IEEE covering image/video representation, processing, analysis and synthesis, learning and understanding. It is ranked Q1 in the Journal Partition Table of Chinese Academy of Sciences. 

The title of the paper is "Adaptive Dual-Teacher Distillation with Subnetwork Rectification for
Bridging Semantic Gaps in Black-Box Domain Adaptation". The abstract of this paper is given as follows: Assuming that neither source data nor source-model parameters are accessible, black-box domain adaptation (BBDA) represents a highly practical yet challenging setting, where transferable knowledge is limited to the predictions of a black-box source model. Existing approaches exploit such knowledge via pseudo-label refinement or by leveraging vision-language models (ViLs), but they often fail to reconcile the inherent discrepancy between task-specific knowledge from black-box models and language-aligned semantic priors of ViLs, resulting in suboptimal integration and degraded adaptation performance. To address this challenge, we propose adaptive Dual-Teacher Distillation with Subnetwork Rectification (DDSR), a framework that explicitly reconciles these complementary yet inconsistent knowledge sources. DDSR employs an adaptive prediction fusion strategy to integrate predictions from the black-box source model and a ViL, generating reliable pseudo-labels for the target domain. A subnetwork-based regularization mechanism mitigates overfitting to noisy supervision by enforcing output consistency and gradient divergence. Furthermore, progressively improved target predictions iteratively refine both pseudo-labels and ViL prompts, enhancing semantic alignment. Finally, class-wise prototypes are used to further optimize target predictions via self-training. {Extensive experiments on multiple benchmarks demonstrate that DDSR achieves state-of-the-art performance among existing BBDA methods and remains competitive with many approaches that have access to source data or source-model parameters. Our code is available at https://github.com/iamjingli/DDSR.
