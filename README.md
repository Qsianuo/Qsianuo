<div align="center">

# Qsianuo

**AI Machine Vision · Industrial Imaging · Vision Inference**

专注 AI 机器视觉应用，围绕工业成像、视觉方案设计、目标检测与模型推理部署持续实践。

[核心项目](#featured-project) · [技术实验](#experiments) · [工程方法](#engineering-approach)

</div>

---

## Focus

| 方向 | 关注内容 |
|---|---|
| **Industrial Machine Vision** | 相机 / 镜头 / 光源选型、视野与精度分析、成像方案设计 |
| **Computer Vision** | YOLO 目标检测、样本质量检查、模型评估与错误分析 |
| **Inference & Deployment** | PyTorch、AMD ROCm、OpenVINO、CPU / GPU 推理验证 |

## Featured Project

### [Vision Spec Generator](https://github.com/Qsianuo/vision-spec-generator)

**机器视觉成像方案自动生成器**

从图纸、样张和检测需求出发，生成相机、镜头、光源与控制器的组合方案。

- **图像诊断**：分析灰度差、过曝 / 欠曝与清晰度，为成像判断提供依据。
- **工程计算**：根据视野、精度、工作距离和运动条件推导关键硬件指标。
- **方案自检**：将结果代回公式复算，检查景深、曝光、工作距离与控制器通道冲突。
- **可追溯输出**：展示计算过程、参数依据和限制条件，生成可打印的方案书。

**[在线体验](https://qsianuo.github.io/vision-spec-generator/)** · **[查看源码](https://github.com/Qsianuo/vision-spec-generator)**

## Experiments

围绕目标检测、AMD GPU 计算与推理加速开展实验，重点关注真实环境验证和可复核的数据。

- **[YOLO26 ROCm Day 1 Labs](https://github.com/Qsianuo/yolo26-rocm-day1-labs)**  
  环境验证、目标检测推理、数据集质量检查、GPU 训练、mAP 评估与受控 A/B 实验。仓库记录了 RX 7900 XTX 环境下的 Notebook 验证结果。

- **[YOLO26 OpenVINO × ROCm Day 2 Labs](https://github.com/Qsianuo/yolo26-openvino-rocm-day2-labs)**  
  对比 AMD CPU / GPU 推理路径，实践 OpenVINO、INT8 量化、ROCm GPU 优化与 CPU-GPU 异步流水线。

<sub>说明：以上 YOLO26 实验仓库为 Fork / 实验记录；上游项目与原始贡献归属以各仓库信息为准。主页将其作为技术验证经历展示，不列为原创主项目。</sub>

## Engineering Approach

**需求量化 → 样本验证 → 方案计算 → 实现与测试 → 结果复核**

我更关注工程结论能否被复现和检查：关键参数有计算依据，实验数据有记录，测试结果与已知限制明确区分。

---

<div align="center">
<sub>Building practical vision systems with measurable results.</sub>
</div>
