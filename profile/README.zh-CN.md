# OtterLLM

[English](https://github.com/OtterLLM) | **简体中文**

**小模型与稀疏 MoE 预训练**的实验笔记、开放图谱与系统研究 —— 涵盖模型架构、数据配方、多模态训练，以及华为昇腾 910C 系统工程。

## 公开项目

- **[otter-handbook](https://github.com/OtterLLM/otter-handbook)** —— 小模型训练手册。第一手预训练观察与文献综述，从分词器一路组织到部署。
  - 在线阅读：<https://otterllm.github.io/otter-handbook/zh/>
- **[moe-config-atlas](https://github.com/OtterLLM/moe-config-atlas)** —— 开源 MoE 架构与稀疏度指纹图谱，按规模分档追踪去重后的 2025–2026 年 MoE 发布。
  - 在线浏览：<https://otterllm.github.io/moe-config-atlas/?lang=zh>

## 研究方向

- **架构与稀疏度**：细粒度稀疏 MoE、线性 / 全注意力混合（`KDA` / `MLA` / `Inkling`）、残差路由，以及深度 / 宽度扩展。
- **数据与多模态预训练**：数据混合配方、中期训练课程，以及早期 / 中期视觉-语言融合。
- **昇腾 910C 系统**：自研 AscendC / CATLASS 算子、零漂移训练加速，以及严格成对的 ABBA 数值验证。
