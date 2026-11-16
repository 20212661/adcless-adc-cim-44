# ADC-less 与减少 ADC 开销 · SRAM/NVM CIM 论文合集（44 篇）

SRAM 存内计算（CIM）方向「去掉 ADC / 降低 ADC 开销」主题对比批次，2026-11-16 齐套。

## 清单

### A 组 · 综述与综述转述（12）
| # | 论文 | 出处 | 版本 |
|---|---|---|---|
| A1 | A Review of SRAM-based Compute-in-Memory Circuits (Yoshioka) | arXiv 2411.06079 | arXiv v2 |
| A2 | Fully Bit-Flexible CIM Macro, Multi-Functional Bit Cell + Input Sparsity Sensing (Yao) | JSSC 2023, v58n5 | 正式版 |
| A3 | 4-Bit Mixed-Signal MAC Macro With One-Shot ADC Conversion (Yang & Sun) | JSSC 2023, v58n9 | 正式版 |
| A4 | Fully Row/Column-Parallel IMC SRAM Macro, Capacitor Mixed-Signal, 5-b Inputs (Lee/Verma) | VLSI 2021 | 作者终版 |
| A5 | Capacitor-Reconfiguring CIM Macro (Yoshioka) | ISSCC 2023 | arXiv 自存稿 |
| A6 | 28nm 1Mb Time-Domain CIM 6T-SRAM, 1241GOPS, 37.01TOPS/W (Wu) | ISSCC 2022 | Digest 正式版 |
| A7 | 16.4 89TOPS/W All-Digital Full-Precision CIM in 22nm (Chih) | ISSCC 2021 | Digest 正式版 |
| A8 | 34.4 3nm 32.5TOPS/W Fully-Digital CIM, INT12 (Fujiwara) | ISSCC 2024 | Digest 正式版 |
| A9 | DIMCA: Area-Efficient Digital IMC Macro, Approximate Arithmetic (Lin) | JSSC 2024, v59n3 | 正式版 |
| A10 | INT8 Charge-Digital Hybrid CIM, Shift-Feed Register (Chen/Xiong/Si) | TCAS-II 2023 | 期刊扩展版 |
| A11 | 22nm 64kB Lightning-Like Hybrid CIM, Compressed Adder Tree (Guo) | Sci China Inf Sci 2025 | 期刊扩展版 |
| A12 | OSA-HCIM: Saliency-Aware Hybrid SRAM CIM (Chen) | ASP-DAC 2024 | 正式版 |

### B 组 · 去掉 ADC（19）
| # | 论文 | 出处 | 版本 |
|---|---|---|---|
| B1 | HCiM: ADC-Less Hybrid Analog-Digital CiM Accelerator (Negi, Purdue) | ASP-DAC 2025 | 官方档案 |
| B2 | Partial-Sum Quantization for Near ADC-Less CiM (Saxena) | ISLPED 2023 | 正式版 |
| B3 | BitSplitNet/MOSAIC: Minimal Peripheral Overhead (Kim) | DAC 2020 | 正式版 |
| B4 | Quarry: Quantization-based ADC Reduction (Azamat) | ICCAD 2021 | 正式版 |
| B5 | RIMAC: Array-Level ADC/DAC-Free ReRAM DNN Processor (Chen) | ASP-DAC 2023 | ACM OA |
| B6 | Towards ADC-Less CiM Accelerators (Saxena) | DATE 2022 | 官方档案 |
| B7 | MIRAGE: MRAM-Based Near ADC-Less CiM Macro (Mukherjee) | DATE 2026 | 正式版 |
| B8 | 27.38-TOPS/W Signed-INT8 Dynamic-Logic ADC-less SRAM CIM, 28nm (Yan) | ISSCC 2022 | Digest 正式版 |
| B9 | 65nm 8-bit All-Digital Stochastic CIM DL Processor, SCIMA (Yang, UCLA) | A-SSCC 2022 | 博士论文版 |
| B10 | rTD-CiM: Resonant Time-Domain ADC-Less Architecture (Challagundla) | GLSVLSI 2024 | CC-BY OA |
| B11 | TDC-CiM: TDC-Based Resonant CiM for INT8 CNNs (Challagundla) | JETCAS 2026, v16n2 | 正式版 |
| B12 | TIMELY: Pushing Data Movements and Interfaces in PIM (Li) | ISCA 2020 | arXiv 自存稿 |
| B13/14 | Neuro-CIM: ADC-Less Neuromorphic CiM Processor (Kim) | JSSC 2023, v58n10 | 正式版（覆盖 VLSI 2022 会议版） |
| B15 | HW/SW Co-Design ADC-Less IMC for SNNs (Apolinario) | arXiv 2211.02167 | arXiv |
| B16 | 40nm Analog-Input ADC-Free CIM RRAM Macro, PWM (Jiang) | VLSI 2022 | 正式版 |
| B17 | ENNA: NN Accelerator with ADC-Free CIM Subarrays (Jiang) | TCAS-I 2023, v70n1 | 正式版 |
| B18 | LINKAGE: Blockwise Dataflow, Straightforward Analog Transfer (Liu) | Front. Electron. 2023 | OA 正式版 |
| B19 | ReRAM Analog Computing without ADCs (Dang) | arXiv 2412.19869 | arXiv |
| B20 | ADC-Less 3D-NAND CIM Using Margin Propagation (Undavalli) | MWSCAS 2023 | 正式版 |

### C 组 · 减少 ADC 开销（12）
| # | 论文 | 出处 | 版本 |
|---|---|---|---|
| C1 | 35.5-127.2 TOPS/W Dynamic Sparsity-Aware Reconfigurable-Precision CIM SRAM (Ali) | SSC-L 2021 | 正式版 |
| C2 | SAMBA: Single-ADC Multi-Bit Accumulation CIM (Che) | TCAS-I 2023, v70n7 | 正式版 |
| C3 | MF-Net: CIM SRAM, Memory-Immersed Data Conversion (Nasrin) | arXiv 2102.00035 | arXiv |
| C4 | Memory-Immersed Collaborative Digitization (Nasrin) | arXiv 2307.03863 | arXiv |
| C5/C6 | 28nm 50.1-TOPS/W P-8T SRAM CIM, BL Charge-Sharing In-SRAM DAC/ADC (Lee) | JSSC 2024, v59n6 | 正式版（覆盖 ICCAD 2022 会议版） |
| C7 | 137.5 TOPS/W SRAM CIM with 9-b Cell-Embedded ADCs (Wang) | arXiv 2307.05944 | arXiv |
| C8 | Reconfigurable CIM Macro with Charge-Sharing Weighted Accumulator (Yang) | arXiv 2605.30814 | arXiv |
| C9 | NeuDW-CIM: 65nm Reconfigurable Neuromorphic CIM (Yang) | arXiv 2606.08947 | arXiv |
| C10 | Pruning for Improved ADC Efficiency in Crossbar Analog IMC (Ibrayev) | arXiv 2403.13082 | arXiv |
| C11 | Hierarchical Non-Structured Pruning, Reduced ADC Resolution (Xue) | DATE 2023 | 官方档案 |
| C12 | Sorted Weight Sectioning for Sparse DNNs on CIM Crossbars (Farias) | ISCAS 2025 | arXiv |

## 目录
- `papers/` — 42 个 PDF（44 条清单：B13 并入 B14、C5 并入 C6）
- `docs/` — 00-索引（逐条账目：DOI/arnumber/版本口径/勘误/待办）、获取说明存档

## 版权说明
本合集仅作个人学习/研究备份。papers/ 下的出版社排版版（IEEE/ACM/Springer 等）版权归 respective publishers 所有，**请勿公开分发**；公开分享请只使用本 README 的元数据表。
