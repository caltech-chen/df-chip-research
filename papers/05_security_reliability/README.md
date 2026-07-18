# 05_security_reliability — 安全性与可靠性方向论文

本目录收录与 AI 加速器芯片**安全性（Security）**和**可靠性（Reliability/Fault Tolerance）**相关的学术论文。

## 研究方向概述

### 可靠性 / 容错设计
研究 AI 加速器在制造缺陷、辐射粒子翻转、工艺偏差等因素下的故障容忍能力。主要技术路线包括：
- 模块冗余（TMR/DMR）与重配置架构
- 基于 FPGA/可重构阵列的在线故障检测与修复
- 深度神经网络推理容错算法（算法层错误掩蔽）
- Systolic Array / 脉动阵列的容错映射策略

### 硬件安全性
研究 AI 加速器面临的硬件级安全威胁及防护原语，包括：
- 对抗样本（Adversarial Examples）在硬件加速中的鲁棒性增强
- 物理不可克隆函数（PUF）等硬件安全原语的应用
- 侧信道攻击（Side-Channel Attack）与防护
- 木马检测（Hardware Trojan Detection）

## 文件清单

| 文件名 | 标题 | 年份 | 状态 |
|--------|------|------|------|
| `22_FaultTolerant_Reconfigurable_2022.txt` | Fault-Tolerant Design for Reconfigurable AI Accelerators | 2022 | 未找到 PDF，见记录文件 |
| `23_Adversarial_HardwareSecurity_2023.txt` | Adversarial Robustness Acceleration with Hardware Security Primitives | 2023 | 未找到 PDF，见记录文件 |

> 注：`.txt` 文件为下载失败记录，包含搜索历史、失败原因及建议后续查找路径。

## 推荐参考来源

- [arXiv cs.AR](https://arxiv.org/list/cs.AR/recent) — 计算机体系结构预印本
- [arXiv cs.CR](https://arxiv.org/list/cs.CR/recent) — 密码学与安全预印本
- [IEEE Xplore](https://ieeexplore.ieee.org) — IEEE/ACM 付费论文库
- [HOST Symposium](https://www.hostsymposium.org) — IEEE Hardware Oriented Security and Trust
- [DATE Conference](https://www.date-conference.com) — Design, Automation and Test in Europe
