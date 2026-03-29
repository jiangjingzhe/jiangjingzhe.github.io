<div align="right">
  <a href="#中文版">📖 中文版</a>
</div>

---

<h1 align="center">Hi, I'm Jingzhe Jiang (姜景哲) 👋</h1>

<p align="center">
  <a href="mailto:jiangjingzhe2003@gmail.com">
    <img src="https://img.shields.io/badge/Email-jiangjingzhe2003%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/jiangjingzhe">
    <img src="https://img.shields.io/badge/GitHub-jiangjingzhe-181717?style=flat-square&logo=github" />
  </a>
</p>

I am a fourth-year undergraduate in Computer Science at **Northeastern University** (China) — including a gap year with an exchange semester at TU Delft — and an incoming **MPhil student** at the **School of Data Science, The Chinese University of Hong Kong, Shenzhen** (September 2025), advised by [Prof. Pinjia He](https://pinjiahe.github.io) (primary) and [Prof. Minchen Yu](https://mincyu.github.io/) (co-supervisor).

My research interests lie at the intersection of **Systems for AI** and **AI for Software Engineering** — building efficient, reliable infrastructure and tooling for large-scale AI workloads.

---

## 🎓 Education

| Period | Degree | Institution |
|--------|--------|-------------|
| Sep 2025 – (expected) | MPhil in Computer Science | The Chinese University of Hong Kong, Shenzhen |
| Sep 2024 – Jan 2025 | Exchange Program | Delft University of Technology (QS Top 50) |
| Sep 2021 – Jun 2026 | B.Sc. in Computer Science & Technology | Northeastern University (985/211), China |

**Academic Performance @ NEU:** GPA 4.2 / 5 &nbsp;·&nbsp; Average Score 92.03 &nbsp;·&nbsp; Rank **18 / 191** (Top 9.42%)

---

## 🔬 Research

### JANUS: Disaggregating Attention and Experts for Scalable MoE Inference

*Zhexiang Zhang\*, Ye Wang\*, Xiangyu Wang, Yumiao Zhao, **Jingzhe Jiang**, Qizhen Weng, Shaohuai Shi, Yin Chen, Minchen Yu*

> **Under Submission** &nbsp;·&nbsp; [arXiv:2512.13525](https://arxiv.org/abs/2512.13525)

JANUS is a scalable MoE inference system that disaggregates attention and expert computations onto separate GPU sub-clusters, enabling independent scaling and precise resource allocation. Key contributions:

- **Adaptive two-phase communication** — exploits intra- and inter-node bandwidth hierarchies to reduce cross-cluster transfer overhead
- **Activation load-balanced scheduling** — implemented as a GPU kernel with ~100 µs overhead, eliminating CPU–GPU synchronization
- **Activation-aware expert management** — dynamically adjusts expert replication and placement based on co-activation patterns
- Achieves up to **3.9× higher per-GPU throughput** than state-of-the-art systems (SGLang) while meeting per-token latency SLOs; reduces GPU resource cost by **25%** compared to monolithic deployments

---

### JittorGeometric: Graph Machine Learning Library

*Project Lead &nbsp;·&nbsp; Nov 2024 – Jan 2025*

[![GitHub](https://img.shields.io/badge/GitHub-AlgRUC%2FJittorGeometric-181717?style=flat-square&logo=github)](https://github.com/AlgRUC/JittorGeometric)

Led development of graph partitioning and graph loading in **JittorGeometric 1.0**, built on the Jittor deep learning framework. Achieved **10%–50% speed improvement** over PyTorch Geometric (PyG) and Deep Graph Library (DGL) across multiple graph learning tasks by optimizing graph storage, computation, and GNN execution pipelines.

---

## 🛠️ Projects

### 🏆 Baka Operating System

[![GitHub](https://img.shields.io/badge/GitHub-caiyih%2Fbakaos-181717?style=flat-square&logo=github)](https://github.com/caiyih/bakaos)

A novel OS for **RISC-V & LoongArch64** that applies software engineering best practices to kernel development:

- Re-architected the kernel using **Dependency Injection (DI)** and **Inversion of Control (IoC)**, transforming it from a monolithic "black box" into a modular, verifiable system with clear interfaces
- Pioneered a **natively testable kernel paradigm**: enabled user-space unit tests, mock tests, and fuzz tests entirely decoupled from hardware
- **National Second Prize**, OS Kernel Implementation Track, National Collegiate Computer System & Capability Challenge (2025)

---

### numc

[![GitHub](https://img.shields.io/badge/GitHub-numc-181717?style=flat-square&logo=github)](https://github.com/jiangjingzhe/numc)

High-performance matrix operations library in C, with SIMD intrinsics and cache-aware optimizations. (UC Berkeley CS61C)

---

### classify-by-risc-v

[![GitHub](https://img.shields.io/badge/GitHub-classify--by--risc--v-181717?style=flat-square&logo=github)](https://github.com/jiangjingzhe/classify-by-risc-v)

Neural network forward-pass (argmax classifier) implemented entirely in **RISC-V assembly**. (UC Berkeley CS61C)

---

### global-illumination


[![GitHub](https://img.shields.io/badge/GitHub-global--illumination-181717?style=flat-square&logo=github)](https://github.com/jiangjingzhe/global-illumination)

Path tracing renderer implementing global illumination algorithms in C.

---

## 🏅 Honors & Awards

- 🥈 **National Second Prize** — OS Kernel Implementation Track, National Collegiate Computer System & Capability Challenge (2025)
- ⭐ **University Merit-Based "Triple-A" Student** — Northeastern University
- 👨‍🏫 **Teaching Assistant** — Operating Systems, LoongArch Architecture Track, Northeastern University

---

---
---

<a id="中文版"></a>

<div align="right">
  <a href="#top">🔝 Back to English</a>
</div>

<h1 align="center">你好，我是姜景哲 👋</h1>

<p align="center">
  <a href="mailto:jiangjingzhe2003@gmail.com">
    <img src="https://img.shields.io/badge/邮箱-jiangjingzhe2003%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/jiangjingzhe">
    <img src="https://img.shields.io/badge/GitHub-jiangjingzhe-181717?style=flat-square&logo=github" />
  </a>
</p>

我是**东北大学**计算机科学与技术专业大四学生（其中 Gap 一年，包含在代尔夫特理工大学的半年交换），即将于 2025 年 9 月入读**香港中文大学（深圳）数据科学学院**攻读计算机科学硕士研究生（MPhil），主导师为 [何品佳教授](https://pinjiahe.github.io)，副导师为 [余旻晨教授](https://mincyu.github.io/)。

研究方向聚焦于 **AI 系统**与**面向 AI 的软件工程**的交叉领域——致力于为大规模 AI 工作负载构建高效、可靠的底层基础设施与工具链。

---

## 🎓 教育背景

| 时间 | 学位 | 院校 |
|------|------|------|
| 2025.09 – （预计）| 计算机科学 MPhil | 香港中文大学（深圳）|
| 2024.09 – 2025.01 | 交换生 | 代尔夫特理工大学（QS Top 50）|
| 2021.09 – 2026.06 | 计算机科学与技术 学士 | 东北大学（985/211）|

**东北大学学业成绩：** GPA 4.2 / 5 &nbsp;·&nbsp; 均分 92.03 &nbsp;·&nbsp; 排名 **18 / 191**（前 9.42%）

---

## 🔬 科研经历

### JANUS：面向可扩展 MoE 推理的 Attention 与 Expert 解耦系统

*Zhexiang Zhang\*, Ye Wang\*, Xiangyu Wang, Yumiao Zhao, **姜景哲**, Qizhen Weng, Shaohuai Shi, Yin Chen, 余旻晨*

> **投稿中** &nbsp;·&nbsp; [arXiv:2512.13525](https://arxiv.org/abs/2512.13525)

JANUS 是一个可扩展的 MoE 推理系统，将 Attention 与 Expert 计算解耦部署至独立的 GPU 子集群，实现精细化资源分配与独立弹性伸缩。核心贡献：

- **自适应两阶段通信** — 充分利用节点内/间带宽层次结构，显著降低跨集群传输开销
- **激活负载均衡调度** — 以 GPU Kernel 实现，调度开销约 100 µs，消除 CPU–GPU 同步瓶颈
- **激活感知专家管理** — 依据共激活模式动态调整专家副本数量与放置策略
- 相比 SOTA 系统（SGLang）实现最高 **3.9× 单 GPU 吞吐量提升**，满足 Token 级延迟 SLO；相比整体部署方案节省 **25%** GPU 资源

---

### JittorGeometric：图机器学习库

*项目负责人 &nbsp;·&nbsp; 2024.11 – 2025.01*

[![GitHub](https://img.shields.io/badge/GitHub-AlgRUC%2FJittorGeometric-181717?style=flat-square&logo=github)](https://github.com/AlgRUC/JittorGeometric)

主导 **JittorGeometric 1.0** 图分区与图加载模块的开发，基于计图（Jittor）深度学习框架构建。通过优化图存储、计算与 GNN 执行流水线，在多项图学习任务上相比 PyTorch Geometric（PyG）和 Deep Graph Library（DGL）实现 **10%–50% 的速度提升**。

---

## 🛠️ 项目经历

### 🏆 Baka 操作系统

[![GitHub](https://img.shields.io/badge/GitHub-caiyih%2Fbakaos-181717?style=flat-square&logo=github)](https://github.com/caiyih/bakaos)

面向 **RISC-V 与 LoongArch64** 架构设计的新型操作系统，将软件工程最佳实践引入内核开发：

- 将**依赖注入（DI）**与**控制反转（IoC）**引入内核架构，将内核从难以验证的"黑盒"改造为具备高模块化、清晰接口与强可测试性的"白盒"
- 开创**原生可测试内核范式**：支持在用户态对内核逻辑进行单元测试、Mock 测试与模糊测试，完全无需真实硬件
- 荣获 **2025 年全国大学生计算机系统能力大赛操作系统内核实现赛道全国二等奖**

---

### numc

[![GitHub](https://img.shields.io/badge/GitHub-numc-181717?style=flat-square&logo=github)](https://github.com/jiangjingzhe/numc)

基于 SIMD 指令与缓存优化的高性能矩阵运算库（C 语言，UC Berkeley CS61C 项目）。

---

### classify-by-risc-v

[![GitHub](https://img.shields.io/badge/GitHub-classify--by--risc--v-181717?style=flat-square&logo=github)](https://github.com/jiangjingzhe/classify-by-risc-v)

完全用 **RISC-V 汇编**实现的神经网络前向推理（Argmax 分类器）。（UC Berkeley CS61C）

---

### global-illumination

[![GitHub](https://img.shields.io/badge/GitHub-global--illumination-181717?style=flat-square&logo=github)](https://github.com/jiangjingzhe/global-illumination)

基于路径追踪算法的全局光照渲染器（C 语言）。

---

## 🏅 荣誉奖项

- 🥈 **全国二等奖** — 全国大学生计算机系统能力大赛操作系统内核实现赛道（2025）
- ⭐ **校级三好学生** — 东北大学
- 👨‍🏫 **课程助教** — 东北大学操作系统课程（LoongArch 架构方向）

---

