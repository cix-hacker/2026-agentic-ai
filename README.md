# 2026 此芯科技 Agentic AI 开发者大赛技术开发指南

本指南面向基于此芯 P1 硬件平台参加 2026 此芯科技 Agentic AI 开发者大赛的开发者，覆盖基础环境部署、端侧 AI 推理、AI 加速卡算力扩展、云端大模型接入与参考资料。

2026.9.29更新维护
YOLO 系列模型已独立维护于cix/ai_model_hub_yolo_series模型仓库。 ai_model_hub_26_Q2主模型仓库中的部分 YOLO 目录可能仅保留inference_npu.py、构建配置等文件，不包含对应的 `.cix` NPU 模型。
在运行 YOLO NPU 推理前，请先从 YOLO Series 模型仓库获取对应的 .cix模型文件，并确认模型文件完整、路径与推理脚本配置一致。https://www.modelscope.cn/models/cix/ai_model_hub_yolo_series/files
