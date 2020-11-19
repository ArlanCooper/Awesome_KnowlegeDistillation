# Awesome_KnowledgeDistillation
这里收集了一些关于知识蒸馏  - Knowledge Distillation (KD) 的介绍和研究现状。

如果你找到了相关领域 remarkable (开山之作、详尽survey、高引用量) 的 paper，可以在 issue 中留言。

如果对你有帮助，请三连支持👍！

## DRL 基础

- 大神总结 | 强化学习线路 [[post]](https://mp.weixin.qq.com/s/E2va_w2Lh_x3n_1XnOY0ZA)
- Policy Gradient Algorithms [[post]](https://lilianweng.github.io/lil-log/2018/04/08/policy-gradient-algorithms.html#ddpg)
- Deterministic Policy Gradient Algorithms [[paper]](http://proceedings.mlr.press/v32/silver14.pdf)
- Continuous Control with Deep Reinforcement Learning [[paper]](https://arxiv.org/pdf/1509.02971.pdf?source=post_page---------------------------)

## KD 概述

- Knowledge Distillation（知识蒸馏）Review--20篇paper回顾 [[post]](https://zhuanlan.zhihu.com/p/160206075)
- 知识蒸馏 | 模型压缩利器_良心总结 [[post]](https://zhuanlan.zhihu.com/p/138210881)
- Knowledge Distillation: A Survey [[paper]](https://arxiv.org/pdf/2006.05525.pdf)
- Knowledge Distillation and Student-Teacher Learning for Visual Intelligence: A Review and New Outlooks [[paper]](https://arxiv.org/pdf/2004.05937.pdf)

## KD 方法

### Logits(Response)-Based 

- Distilling the Knowledge in a Neural Network [[paper]](https://arxiv.org/pdf/1503.02531.pdf)
- Deep Mutual Learning [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Deep_Mutual_Learning_CVPR_2018_paper.pdf)
- On the Efficacy of Knowledge Distillation [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Cho_On_the_Efficacy_of_Knowledge_Distillation_ICCV_2019_paper.pdf)
- Self-training with Noisy Student improves ImageNet classification [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xie_Self-Training_With_Noisy_Student_Improves_ImageNet_Classification_CVPR_2020_paper.pdf)
- Training deep neural networks in generations: A more tolerant teacher educates better students [[paper]](https://www.cs.jhu.edu/~alanlab/Pubs19/yang2019training.pdf)
- Distillation-Based Training for Multi-Exit Architectures [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Phuong_Distillation-Based_Training_for_Multi-Exit_Architectures_ICCV_2019_paper.pdf)
- Knowledge Extraction with No Observable Data [[paper]](https://papers.nips.cc/paper/2019/file/596f713f9a7376fe90a62abaaedecc2d-Paper.pdf) [[code]](https://github.com/snudatalab/KegNet)

### Feature-Based

- 

### Relation-Based

- 

### Online Distillation

- 

### Self-Distilllation

- 

### Adversarial KD

- MEAL: Multi-Model Ensemble via Adversarial Learning [[paper]](https://www.aaai.org/ojs/index.php/AAAI/article/download/4417/4295)
- Feature-map-level Online Adversarial Knowledge Distillation [[paper]](https://arxiv.org/pdf/2002.01775.pdf)
- Data-Free Learning of Student Networks [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Data-Free_Learning_of_Student_Networks_ICCV_2019_paper.pdf)
- KDGAN: Knowledge Distillation with Generative Adversarial Networks [[paper]](http://papers.neurips.cc/paper/7358-kdgan-knowledge-distillation-with-generative-adversarial-networks.pdf)

### Multi-Teacher KD

- 

### Cross-Modal KD

- 

### Graph-Based KD

- 

### Attention-Based KD

- 

### Data-Free KD

- 

### Quantized KD

- 

### LifeLong KD

- 

### NAS-based KD

- 

## KD 应用

### In Reinforcement Learning

- Policy Distillation [[paper]](https://arxiv.org/pdf/1511.06295.pdf)
- Distilling Policy Distillation [[paper]](https://arxiv.org/pdf/1902.02186.pdf)
- PoPS: Policy Pruning and Shrinking for Deep Reinforcement Learning [[paper]](https://arxiv.org/pdf/2001.05012.pdf) [[code]](https://github.com/dorlivne/PoPS)
- Distillation Strategies for Proximal Policy Optimization [[paper]](https://arxiv.org/pdf/1901.08128.pdf)

## 相关仓库

- dkozlov/awesome-knowledge-distillation [[awesome]](https://github.com/dkozlov/awesome-knowledge-distillation)
- danielmcpark/awesome-knowledge-distillation [[awesome]](https://github.com/danielmcpark/awesome-knowledge-distillation)
- FLHonker/Awesome-Knowledge-Distillation [[awesome]](https://github.com/FLHonker/Awesome-Knowledge-Distillation)
- peterliht/knowledge-distillation-pytorch [[code]](https://github.com/peterliht/knowledge-distillation-pytorch)