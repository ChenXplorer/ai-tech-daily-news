# Naive-N0.5-Flash 权重与推理代码已在 GitHub / Hugging Face 上线

- 来源：GitHub / NaiveAI-Labs
- 链接：https://github.com/NaiveAI-Labs/Naive-N0.5-Flash
- 发布时间：2026-09-27 22:14 +08:00
- 抓取时间：2026-09-28 07:55 +08:00
- 标签：开源模型、推理、NaiveAI

NaiveAI-Labs 在 GitHub 发布 Naive-N0.5-Flash 仓库，模型卡写明 48 层 Transformer、39 层滑动窗口注意力加 9 层 DSA，滑动窗口 128 token，DSA 为 backbone 选择 top 2048 token。官方称配套推理系统 NaiveRT 在 Standard 模式约 50 token/s/用户，Ultrafast 模式最高约 2000 token/s。FP8 权重大约 315GB。该条目与官方研究博客为同一发布事件的代码落地确认，不构成第二起独立产品发布。
