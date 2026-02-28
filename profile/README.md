# 模型与任务的多层次自主适配

*Multi-level autonomous adaptation of models and tasks*

## 通用视觉模型自主适配算法库

本 GitHub 仓库为通用视觉模型自主适配算法库，汇聚「非完备条件视觉感知」项目课题一“模型与任务的多层次自主适配”的相关成果。算法库聚焦通用视觉模型在数据稀缺、精细标注成本高等条件下，如何面向多样化下游任务实现**高效、自主适配**；覆盖多任务适配与参数高效微调（Prompt/Adapter/MoE 等）、视觉-语言交互与适配、场景图生成等方向。

## 算法库简介

论文与项目代码见组织仓库：[**Repositories**](https://github.com/orgs/Incomplete-Condition-Visual-Perception/repositories)

| 仓库                                                                                              | 简介                                                                            | 课题子任务                       |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | -------------------------------- |
| [PETL_Base_Framework](https://github.com/Incomplete-Condition-Visual-Perception/PETL_Base_Framework) | 多任务层次化协同适配、混合稀疏专家网络统一适配（任务关联性度量 / 任务关联驱动） | 模型与任务的关联性表达           |
| [GIP](https://github.com/Incomplete-Condition-Visual-Perception/GIP)                                 | 门控交互提示，视觉-语言参数高效微调（ICASSP）[1]                                | 模型与任务的关联性表达           |
| [RMAdapter](https://github.com/Incomplete-Condition-Visual-Perception/RMAdapter)                     | 基于 Adapter 的参数高效微调（AAAI 2026 Oral）[2]                                | 通用视觉模型引导的多层次协同学习 |
| [DRM](https://github.com/Incomplete-Condition-Visual-Perception/DRM)                                 | 场景图生成（CVPR 2024）[3]                                                      | 通用视觉模型引导的多层次协同学习 |

> 1. Xiang Lin, Weixin Li, Shuo Guo, Lihong Wang, Di Huang. *GIP: Gated Interaction Prompt for Parameter Efficient Vision-Language Fine-Tuning* [C]. ICIP, 2025.
> 2. Xiang Lin, Weixin Li, Shu Guo, Lihong Wang, Di Huang. *RMAdapter: Reconstruction-based Multi-modal Adapter for Vision-Language Models* [C]. AAAI, 2026. (CCF A)
> 3. Jiankai Li, Yunhong Wang, Xiefan Guo, Ruijie Yang, Weixin Li. *Leveraging Predicate and Triplet Learning for Scene Graph Generation* [C]. CVPR, 2024. (CCF A)

## 欢迎合作与引用。
