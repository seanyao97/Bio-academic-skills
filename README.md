# Bio-Academic-Skills

<div align="center">

**微生物学与生命科学学术研究技能集**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skills](https://img.shields.io/badge/Skills-5-blue.svg)](./skills)
[![Status](https://img.shields.io/badge/Status-Beta-green.svg)](./)

*专为微生物学、病原生物学、分子生物学研究者设计的AI辅助工具*
*目标期刊：PNAS | eLife | Nature Communications | Cell Reports | mBio | ISME Journal*

</div>

---

## 📖 项目简介

本技能集专为**微生物学与生命科学领域**的学术研究者设计，帮助你完成从文献检索、数据分析、论文写作到投稿准备的完整科研流程。

**与 nature-skills 的区别：**

| 维度 | nature-skills | bio-academic-skills |
|------|--------------|---------------------|
| 目标期刊 | Nature, Nature Medicine, Cell | **PNAS, eLife, NC, ISME, mBio** |
| 核心领域 | 生物医学、临床研究 | **微生物学、分子生物学、生态学** |
| 语言风格 | Nature house style (英式) | **PNAS/eLife/NC 通用学术风格** |
| 图表规范 | Nature 特定配色/排版 | **微生物学期刊通用标准** |
| 数据格式 | GEO, SRA 等生物医学数据库 | **微生物组、基因组、蛋白质组** |

---

## 🎯 目标期刊

本技能集针对以下期刊的格式要求和学术规范进行优化：

| 期刊 | 缩写 | 领域 | 影响因子 |
|------|------|------|---------|
| **PNAS** | PNAS | 综合性 | ~9.4 |
| **eLife** | eLife | 生命科学 | ~6.4 |
| **Nature Communications** | NC | 综合性 | ~14.7 |
| **Cell Reports** | Cell Rep | 生命科学 | ~7.5 |
| **ISME Journal** | ISME J | 微生物生态 | ~10.3 |
| **mBio** | mBio | 微生物学 | ~6.4 |
| **Molecular Systems Biology** | MSB | 系统生物学 | ~8.5 |

---

## 📦 技能列表

| 技能 | 状态 | 功能描述 | 触发关键词 |
|------|------|---------|-----------|
| `bio-search` | Beta | 微生物学文献多源搜索（PubMed, bioRxiv, CrossRef） | "找文献", "搜索PubMed", "微生物文献" |
| `bio-figure` | Draft | PNAS/eLife风格科研绘图（显微镜、电泳、序列图） | "画图", "发表级图", "PNAS风格" |
| `bio-writing` | Draft | 微生物学论文写作（Introduction, Results, Discussion） | "写引言", "论文写作", "润色" |
| `bio-stats` | Draft | 微生物学统计报告（t检验、ANOVA、多样性分析） | "统计", "差异分析", "alpha多样性" |
| `bio-response` | Beta | 审稿意见回复（针对NC/eLife/PNAS） | "回复审稿人", "修改说明" |
| `bio-paper2ppt` | Beta | 微生物学论文转中文PPT | "论文转PPT", "组会汇报" |

---

## 🚀 快速安装

### 对于 Codex

```bash
# 克隆仓库
git clone https://github.com/seanyao97/bio-academic-skills.git
cd bio-academic-skills

# 安装所有技能
mkdir -p ~/.codex/skills
cp -R skills/* ~/.codex/skills/

# 重启 Codex
