# OtterLLM

Field notes, open atlases, and systems research on **small-model & sparse MoE pretraining** — spanning model architecture, data recipes, multimodal training, and Huawei Ascend 910C systems engineering.

## Public Projects

- **[otter-handbook](https://github.com/OtterLLM/otter-handbook)** — 小模型训练手册 (*Field notes on training small models*). First-hand pretraining observations and literature syntheses organized from tokenizer to deployment.
  - Read online: <https://otterllm.github.io/otter-handbook/>
- **[moe-config-atlas](https://github.com/OtterLLM/moe-config-atlas)** — Open-source MoE architecture & sparsity fingerprint atlas tracking deduplicated 2025–2026 MoE releases across scale tiers.
  - Explore online: <https://otterllm.github.io/moe-config-atlas/>

## Research Focus

- **Architecture & Sparsity**: Fine-grained sparse MoE, hybrid linear/full attention (`KDA` / `MLA` / `Inkling`), residual routing, and depth/width scaling.
- **Data & Multimodal Pretraining**: Data mixture recipes, mid-training curricula, and early/mid-stage vision-language fusion.
- **Ascend 910C Systems**: Custom AscendC / CATLASS kernels, zero-drift training acceleration, and strict paired ABBA numerical verification.
