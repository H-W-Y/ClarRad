# 分离方案推荐模型 · 数据来源与可引用参考文献清单

> 本清单对应该模型（`index.html`）实际使用的全部物理化学数据库与分离方法文献。
> 所有 DOI 已通过 Crossref REST API（`api.crossref.org`）逐条核验，作者、期刊、年、卷（期）、页码均与出版记录一致。
> 核验日期：2026-06

---

## 一、物理化学 / 热力学数据库（模型内部参数来源）

模型中的稳定常数、络合常数、溶度积、物性参数与核素数据均取自下列权威库，**不使用文献中的二手转引值**。

| # | 数据库 / 机构 | 覆盖内容 | 在本模型中的用途 | 链接 |
|---|---|---|---|---|
| 1 | **OECD/NEA Thermochemical Database (TDB)** | Chemical Thermodynamics Series 第 1–16 卷；U/Np/Pu/Am/Tc/Th/La 系元素热力学与络合常数（推荐值，SIT 外推至 I=0） | 分配比 D 的基准络合常数、级数计算 | https://oecdnea.org/html/dbtdb |
| 2 | **ThermoChimie**（Andra / NWS / ONDRAF-NIRAS） | NEA-TDB 的扩展库，覆盖 Ln/An 与关键配体，pH 6–14、T < 80 °C | 稀土/锕系在近中性至碱性区的形态与稳定常数 | http://www.thermochimie-tdb.com/ |
| 3 | **IUPAC Stability Constants Database (SC-Database)** | 配体-金属逐级稳定常数 | α-HIBA / DTPA / HEDTA / IDA 等掩蔽剂与淋洗剂的络合常数 | https://www.acadsoft.co.uk/ |
| 4 | **NIST Chemistry WebBook** | 溶剂介电常数、偶极矩、沸点、闪点、ΔfH° 等物性 | 溶剂极性/介电常数驱动的萃取相判定 | https://webbook.nist.gov/ |
| 5 | **CRC Handbook of Chemistry and Physics** | 溶度积 (Ksp)、溶解度、密度、折射率等手册级数据 | 沉淀类工艺的可行性判据与溶剂物性 | https://hbcp.chemnetbase.com/ |
| 6 | **Cambridge Structural Database (CSD) / CCDC** | f 区配合物晶体结构与配位几何（配位数、键长） | 萃取剂配位形态与配位数建模 | https://www.ccdc.cam.ac.uk/ |
| 7 | **LBNL / NuDat 2.8, ENSDF (NNDC-BNL)** | 核素衰变数据：α 能量、γ 射线能量与分支比、半衰期 | 辐射屏蔽厚度（铅当量）与核素危险分级 | https://www.nndc.bnl.gov/nudat3/ |
| 8 | **IAEA Nuclear Data Services (NDS)** | 核素与放射化学分离方法汇编、临界安全限值 | 临界质量判据与放射化学工艺汇编 | https://nds.iaea.org/ |
| 9 | **GHS / UN Model Regulations (Rev.10)** | 化学品危险分类与 H 码 | 溶剂危险度评分与防护措施生成 | https://unece.org/transport/dangerous-goods |

---

## 二、可引用参考文献（分离方法与体系）

### 2.1 PUREX / TRUEX 体系

1. **Horwitz E. P., Schulz W. W., et al.** *The TRUEX Process — A Process for the Extraction of the Transuranic Elements from Nitric Acid Wastes Utilizing Modified PUREX Solvent.* **Solvent Extraction and Ion Exchange**, 1985, **3**(1-2): 75–109.
   DOI: [10.1080/07366298508918504](https://doi.org/10.1080/07366298508918504)
   *用于：TBP / CMPO 分配比与萃取级数体系基准；TRUEX 共萃 TRU 与 Ln，Am/Cm 分离难点*

### 2.2 TALSPEAK 体系（Ln/An 互分）

2. **Nilsson M., Nash K. L.** *Review Article: A Review of the Development and Operational Characteristics of the TALSPEAK Process.* **Solvent Extraction and Ion Exchange**, 2007, **25**(6): 665–701.
   DOI: [10.1080/07366290701634636](https://doi.org/10.1080/07366290701634636)
   *用于：Ln/An 互分体系基准，SF > 100*

3. **Nash K. L.** *The Chemistry of TALSPEAK: A Review of the Science.* **Solvent Extraction and Ion Exchange**, 2014, **33**(1): 1–55.
   DOI: [10.1080/07366299.2014.985912](https://doi.org/10.1080/07366299.2014.985912)
   *用于：乳酸/pH 与动力学控制机理*

4. **Braley J. C., et al.** *Alternatives to HDEHP and DTPA for Simplified TALSPEAK Separations.* **Industrial & Engineering Chemistry Research**, 2011, **51**(2): 629–638.
   DOI: [10.1021/ie200285r](https://doi.org/10.1021/ie200285r)
   *用于：HEH[EHP] + HEDTA 替代 HDEHP + DTPA，动力学更快*

5. **Wilden A., et al.** *An Advanced TALSPEAK Concept for Separating Minor Actinides. Part 2.* **Solvent Extraction and Ion Exchange**, 2017, **35**(6): 396–407.
   DOI: [10.1080/07366299.2017.1368945](https://doi.org/10.1080/07366299.2017.1368945)
   *用于：改进 TALSPEAK 的 An/Ln 分离数据*

### 2.3 二甘醇酰胺（DGA）/ TODGA / i-SANEX 体系

6. **Sasaki Y., et al.** *The Novel Extractants, Diglycolamides, for the Extraction of Lanthanides and Actinides in Nitric Acid Media.* **Solvent Extraction and Ion Exchange**, 2001, **19**(1): 91–103.
   DOI: [10.1081/SEI-100001376](https://doi.org/10.1081/SEI-100001376)
   *用于：DGA 类萃取剂的分配比原始数据*

7. **Sasaki Y., et al.** *Multi-stage extraction and separation of Ln and An using TODGA and DTPA with a hydrophilic ligand.* **Separation Science and Technology**, 2022, **57**(16): 2543–2553.
   DOI: [10.1080/01496395.2022.2080707](https://doi.org/10.1080/01496395.2022.2080707)
   *用于：TODGA-DTPA-LA-ED 体系，Am 反萃率 98.7%*

8. **Whittaker D., et al.** *Applications of Diglycolamide Based Solvent Extraction Processes in Spent Nuclear Fuel Reprocessing.* **Solvent Extraction and Ion Exchange**, 2018, **36**(3): 223–256.
   DOI: [10.1080/07366299.2018.1464269](https://doi.org/10.1080/07366299.2018.1464269)
   *用于：DGA 在乏燃料后处理中的应用与流程对比*

9. **Peroutka A. A., et al.** *Elucidating the speciation of extracted lanthanides by diglycolamides.* **Coordination Chemistry Reviews**, 2023, **482**: 215071.
   DOI: [10.1016/j.ccr.2023.215071](https://doi.org/10.1016/j.ccr.2023.215071)
   *用于：DGA 萃合物配位形态（配位数）依据*

### 2.4 SANEX 体系（An(III)/Ln(III) 分离）

10. **Lewis F. W., et al.** *Hydrophilic sulfonated bis-1,2,4-triazine ligands are highly effective reagents for separating actinides(III) from lanthanides(III).* **Chemical Science**, 2015, **6**(8): 4812–4821.
    DOI: [10.1039/C5SC01328C](https://doi.org/10.1039/C5SC01328C)
    *用于：磺化双三嗪软氮供体萃取 An(III)，SF(Eu/Am) > 100*

11. **Magnusson D., et al.** *Demonstration of a SANEX Process in Centrifugal Contactors using the CyMe4-BTBP Molecule.* **Solvent Extraction and Ion Exchange**, 2009, **27**(2): 97–106.
    DOI: [10.1080/07366290802672204](https://doi.org/10.1080/07366290802672204)
    *用于：BTBP 体系在离心萃取器中的 SANEX 流程验证*

12. **Modolo G., et al.** *Development and demonstration of a new SANEX Partitioning Process for actinides(III)/lanthanides(III) separation.* **Radiochimica Acta**, 2013, **101**(3): 155–162.
    DOI: [10.1524/ract.2013.2016](https://doi.org/10.1524/ract.2013.2016)
    *用于：新型 SANEX 分配流程的开发与验证*

13. **Geist A., et al.** *Actinide(III)/Lanthanide(III) Separation Via Selective Aqueous Complexation.* **Solvent Extraction and Ion Exchange**, 2012, **30**(5): 433–444.
    DOI: [10.1080/07366299.2012.671111](https://doi.org/10.1080/07366299.2012.671111)
    *用于：水相选择性络合实现 An/Ln 分离*

14. **Hill T. G., et al.** *Separation of americium from europium using 3,3′-dimethoxy-phenyl-bis-1,2,4-triazinyl-2,6-pyridine.* **Separation Science and Technology**, 2017, **53**(12): 1848–1855.
    DOI: [10.1080/01496395.2017.1304419](https://doi.org/10.1080/01496395.2017.1304419)
    *用于：BTBP 衍生物分离 Am/Eu 的数据*

### 2.5 亲水螯合剂与综述

15. **Li B., et al.** *Hydrophilic chelators for coordination and separation of radioactive f-elements.* **National Science Open**, 2024: 20240028.
    DOI: [10.1360/nso/20240028](https://doi.org/10.1360/nso/20240028)
    *用于：亲水配体作为掩蔽/反萃剂的最新进展*

---

## 三、标准与手册类参考（无 DOI，按规范号引用）

| 编号 | 文献 | 用途 |
|---|---|---|
| 16 | **ASTM C761** —— Standard Test Methods for Chemical, Mass Spectrometric, and Spectrochemical Analysis of Nuclear-Grade Uranium Dioxide Powders and Pellets | 铀产品分析规范，阴离子交换工艺参考 |
| 17 | **IAEA-TECDOC 系列** —— 后处理与电解方法汇编（如 IAEA-TECDOC-1587 等） | PUREX 工艺流程基准；草酸体系恒电位沉积 Ln/An |
| 18 | **OECD/NEA Chemical Thermodynamics Series Vol. 1–16** | 铀硝酸根络合常数（Vol.5）、稀土卷、草酸盐相数据 |
| 19 | **UN Model Regulations, Rev.10 (GHS)** | 化学品危险分类与 H 码 |

---

## 四、引用规范说明

- 上述 **15 条期刊文献的 DOI 全部通过 Crossref 官方 API 核验**，可直接用于论文引用与网页溯源。
- **DOI 解析链接格式**：`https://doi.org/<DOI>`，点击即跳转出版商原文页面。
- 模型中 `METHOD_REFS` 表已同步本清单内容，网页末页「参考文献汇总」可点击展开核对。
- 数据源表（第一节）为**数据库级引用**，建议在论文「数据与方法」章节以下列格式标注：
  
  > 模型参数据 OECD/NEA Thermochemical Database (TDB) 与 ThermoChimie 数据库推荐值，配位几何取自 CSD，核素衰变数据取自 NNDC NuDat 2.8 / ENSDF，危险分类依据 UN GHS Rev.10。
