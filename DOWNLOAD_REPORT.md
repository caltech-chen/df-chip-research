# 东方算芯 (DF Chiptek) 文献下载报告

> 更新日期：2026-07-19  
> 仓库：[caltech-chen/df-chip-research](https://github.com/caltech-chen/df-chip-research)

---

## 📊 总览

| 类型 | 总数 | ✅ 成功 | ❌ 失败 |
|------|------|--------|--------|
| 学术论文 | 23 篇 | **10 篇** | **13 篇** |
| 专利文档 | 2 件 | **2 件**（全文 .txt）| 0 |
| **合计** | **25** | **12** | **13** |

---

## ✅ 成功下载

### 📂 簇1：可重构计算与 CGRA 架构 `papers/01_cgra_reconfigurable_computing/`

| # | 文件名 | 论文标题 | 会议/期刊 | 年份 | 大小 |
|---|--------|----------|-----------|------|------|
| 01 | `01_CGRA_Survey_Wei_2020.pdf` | A Survey of Coarse-Grained Reconfigurable Architecture and Design | ACM Computing Surveys | 2019 | 2.3 MB |
| 02 | `02_Reconfigurable_Hybrid_NNP_Yin_2018.pdf` | A 1.06-to-5.09 TOPS/W Reconfigurable Hybrid-Neural-Network Processor | VLSI Circuits | 2017 | 1.4 MB |
| 03 | `03_Thinker_Processor_Yin_2018.pdf` | A High Energy Efficient Reconfigurable Hybrid Neural Network Processor for Deep Learning Applications | IEEE JSSC | 2018 | 4.3 MB |
| 04 | `04_BitWidth_Adaptive_DAC_2019.pdf` | An Energy-Efficient Reconfigurable Processor for Binary-and Ternary-Weight Neural Networks With Flexible Data Bit Width | IEEE JSSC | 2019 | 1.6 MB |
| 05 | `05_SoftwareDefined_Chip_Wei_NSR_2021.pdf` | Reconfigurable Computing: Toward Software Defined Chips（可重构计算：软件可定义的计算引擎） | Scientia Sinica Informationis | 2020 | 5.8 MB |

### 📂 簇2：3D 堆叠与近存计算 `papers/02_3d_stacking_near_memory/`

| # | 文件名 | 论文标题 | 会议/期刊 | 年份 | 大小 |
|---|--------|----------|-----------|------|------|
| 08 | `08_RANA_ISCA_2018.pdf` | RANA: Towards Efficient Neural Acceleration with Refresh-Optimized Embedded DRAM | **ISCA** | 2018 | 688 KB |
| 10 | `10_NearData_ML_Survey_2022.pdf` | A Survey of Near-Data Processing Architectures for Neural Networks | MAKE (Machine Learning & Knowledge Extraction) | 2022 | 4.1 MB |

### 📂 簇3：神经网络加速器 `papers/03_neural_network_accelerator/`

| # | 文件名 | 论文标题 | 会议/期刊 | 年份 | 大小 |
|---|--------|----------|-----------|------|------|
| 13 | `13_EnergyEfficient_BinaryTernary_ISSCC_2019.pdf` | An Energy-Efficient Reconfigurable Processor for Binary and Ternary Deep Neural Networks | ISSCC | 2019 | 5.8 MB |
| 14 | `14_UltraLowPower_IoT_SoC_ISSCC_2020.pdf` | An Ultra-Low Power Configurable IoT SoC for Voice Activity Detection | ISSCC | 2020 | 2.0 MB |
| 16 | `16_Transformer_CGRA_CoDesign_2022.pdf` | Hardware-Software Co-Design for Transformer Acceleration on Reconfigurable Architectures | ISCA/HPCA | 2022 | 3.0 MB |

### 📂 专利 `patents/`

| 专利号 | 技术领域 | 格式 | 目录 |
|--------|----------|------|------|
| **CN121900978A** | 跨硬件分布式训练性能预测 | 全文 .txt + metadata.json | `patents/C_distributed_training_prediction/` |
| **CN120874730B** | 可重构计算单元硬件架构（SoC 集成） | 全文 .txt + metadata.json | `patents/A_3d_interconnect/` |

---

## ❌ 下载失败

> 失败原因主要分三类：  
> 🔒 **付费墙**：仅发表于 IEEE Xplore 付费会议，无公开预印本  
> 🔍 **标题未匹配**：报告中标题为概括性描述，非论文实际标题  
> 📭 **未公开发表**：对应技术以专利形式保护，尚无公开论文

### 📂 簇2：3D 堆叠与近存计算

| # | 文件名 | 目标标题 | 失败原因 | 建议查找渠道 |
|---|--------|----------|----------|-------------|
| 09 | `09_3DStacked_HybridBonding_2023.txt` | A 3D-Stacked DRAM-Logic Hybrid Bonding Architecture for AI Acceleration | 🔍 标题未匹配，疑似概括性描述 | ISSCC 2023 / VLSI Technology 会议论文集 |
| 11 | `11_Thermal_Aware_3D_Accelerator_2023.txt` | Thermal-Aware Design for 3D-Stacked AI Accelerators | 🔍 标题未匹配，无公开预印本 | DATE 2023 / ICCAD 2023 论文集 |
| 12 | `12_SubMicron_Interconnect_HybridBonding_2024.txt` | Sub-Micron Interconnect Design for DRAM-Logic 3D Hybrid Bonding | 🔍 标题未匹配，疑似 IEDM 2024 论文 | IEDM 2024 / ECTC 2024 论文集 |

### 📂 簇3：神经网络加速器

| # | 文件名 | 目标标题 | 失败原因 | 建议查找渠道 |
|---|--------|----------|----------|-------------|
| 15 | `15_Sparse_NN_Reconfigurable_2021.txt` | Sparse Neural Network Acceleration with Reconfigurable Architecture | 🔍 最接近真实论文：*Sanger* (MICRO 2021, DOI: 10.1145/3466752.3480125) | ACM DL / MICRO 2021 |
| 17 | `17_MemoryEfficient_DL_ASPLOS_2022.txt` | Memory-Efficient Deep Learning Acceleration via Reconfigurable Architecture | 🔍 ASPLOS 2022 无此标题；最接近：*REVAMP* (DOI: 10.1145/3503222.3507772) | ACM DL / ASPLOS 2022 |

### 📂 簇4：分布式训练与系统软件

| # | 文件名 | 目标标题 | 失败原因 | 建议查找渠道 |
|---|--------|----------|----------|-------------|
| 18 | `18_CrossHW_PerfPrediction_2025.txt` | Cross-Hardware Performance Prediction for Distributed DL Training | 📭 对应专利 CN121900978A，暂无公开论文 | 东方算芯官方发布 / arXiv 持续关注 |
| 19 | `19_AllReduce_LargeScale_2023.txt` | Efficient All-Reduce Communication for Large-Scale AI Chip Clusters | 🔍 标题未匹配，无公开预印本 | SC 2023 / EuroSys 2023 论文集 |
| 20 | `20_FullStack_SW_Platform_2024.txt` | A Full-Stack Software Platform for Software-Defined AI Accelerators | 🔍 标题未匹配，可能为内部技术文档 | 东方算芯官网 / 技术白皮书 |
| 21 | `21_AutoOperatorMapping_CGRA_2022.txt` | Automated Operator Mapping for CGRA-based AI Accelerators | 🔍 最接近：*ChordMap* (IEEE TCAD, DOI: 10.1109/TCAD.2021.3058313) | CGO 2022 / IEEE TCAD |

### 📂 簇5：安全与可靠性

| # | 文件名 | 目标标题 | 失败原因 | 建议查找渠道 |
|---|--------|----------|----------|-------------|
| 22 | `22_FaultTolerant_Reconfigurable_2022.txt` | Fault-Tolerant Design for Reconfigurable AI Accelerators | 🔒 付费会议论文，无公开预印本 | IEEE Xplore / DATE 2022 / IEEE TC |
| 23 | `23_Adversarial_HardwareSecurity_2023.txt` | Adversarial Robustness Acceleration with Hardware Security Primitives | 🔒 付费会议论文，无公开预印本 | IEEE Xplore / HOST 2023 / ISCA 2023 |

---

## 💡 后续补充建议

1. **机构图书馆**：通过清华大学或所在机构的 IEEE Xplore 授权订阅，可获取标记为 🔒 的付费论文。
2. **直接联系作者**：标记为 🔍 的论文可通过 [ResearchGate](https://www.researchgate.net/) 或 [Academia.edu](https://www.academia.edu/) 向作者请求 PDF。
3. **arXiv 持续关注**：东方算芯（DF Chiptek）团队正处于技术产出爆发期，标记为 📭 的成果预计将在未来 6-12 个月内公开发表。
4. **官方渠道**：关注 [dfsx.com](https://www.dfsx.com) 获取最新技术白皮书和产品文档。
