# 前沿推荐候选池 · 2026-04-30

## Tier 2 桶选择

历史记录：
- 2026-04-23: Nonlinear dynamics & pattern formation, Soft matter & active matter
- 2026-04-24: Non-equilibrium statistical mechanics, Condensed matter (topological phases, strongly correlated systems)
- 2026-04-25: Quantum information, Astrophysics & cosmology
- 2026-04-26: Nonlinear dynamics & pattern formation, Soft matter & active matter

本次（最近最少使用）：**Non-equilibrium statistical mechanics** + **Condensed matter (topological phases, strongly correlated systems)**

## 去重集（过去7天，共27篇）

来自 frontier-recs/digests/2026-04-23 至 2026-04-26 及 paper-update/digests/2026-04-24 至 2026-04-29

主要排除：2603.02595, 2604.16724, 2602.23933, 2604.16994, 2603.08644, 2604.16173, 2603.18918,
2604.20635, 2406.01289, 2501.05088, 2410.17071, 2603.09620, 2601.11264, 2604.20635,
2603.18880, 2504.03032, 2502.09953, 2604.14918, 2604.14569, 2602.10576, 2604.20678,
2604.21543, 2310.05273, 2511.03123, 2604.19132, 2604.00552, 2604.09447, 2604.21000
（含去重后排除：DOI 10.1073/pnas.2505725122 = 2310.05273，已出现于 4月26日）

## 候选评分表

### Section A 候选（精选）

| arXiv | 标题（简） | 新颖 | 深度 | 方法 | 时效 | IYPT | 总分 | ⭐ | 研究关联 |
|-------|-----------|------|------|------|------|------|------|----|----------|
| 2601.12642 | Shear-Thickening Drop Impact (oobleck) | 5 | 5 | 5 | 5 | 5/5 | **25** | ⭐ | — |
| 2604.05918 | Long-distance non-reciprocal attraction in soap film | 5 | 5 | 4 | 4 | 4/5 | **22** | ⭐ | — |
| 2604.01185 | Polyelectrolyte → receding contact line instability | 4 | 4 | 4 | 4 | 5/5 | **21** | ⭐ | ✅ MPIP |

### Section B 候选（速览）

| arXiv | 标题（简） | 新颖 | 深度 | 方法 | 时效 | IYPT | 总分 | ⭐ |
|-------|-----------|------|------|------|------|------|------|----|
| 2604.22231 | Active Jurin's law | 5 | 4 | 4 | 4 | 3/5 | **20** | ⭐ |
| 2604.20526 | Subharmonic instability in 2D channel flow | 4 | 4 | 4 | 4 | 4/5 | **20** | ○ |
| 2604.16179 | Quantum-inspired tensor-network turbulence simulation | 4 | 4 | 4 | 4 | 4/5 | **20** | ⭐ |
| 2604.03737 | Cascade of spin liquids in Rb₂Co₂(SeO₃)₃ | 4 | 5 | 4 | 4 | 2/5 | **19** | — |
| 2503.20427 | Localizing entropy production along trajectories | 4 | 4 | 4 | 3 | 3/5 | **18** | — |

### 淘汰/备用

- arXiv:2604.26290 — HTML 404，内容不足，不确定期刊状态
- arXiv:2310.05273 (PNAS dusty plasma) — 已在 4/26 digest 出现，去重排除
- 其余候选因分数低于 18 或去重冲突未入选

## 检索策略覆盖

- 策略 A：flu-dyn ×4, surface/interface ×3, AI for physics ×2, non-eq stat-mech ×3, cond-mat topological ×3, soft matter ×2, 补充 ×4 = **21次 tavily_search**
- 策略 B：PRL Editors' Suggestions, Nature Physics, Physics Magazine APS, PRF = **4次**
- 策略 C：tavily_research cross-pollination (model=mini) = **1次**
- Extract：4次 tavily_extract（HTML版本）
- 作者查询：2次额外 extract + 2次 search

**总搜索数：≥26次（满足 ≥20 要求 ✓），Extract ≥4次 ✓**

## IYPT 评分说明

评分子项（各 0/1）：Picturable · Multi-mechanism · Regime transition · Classical core · Narratable

| arXiv | P | M | R | C | N | IYPT |
|-------|---|---|---|---|---|------|
| 2601.12642 | 1 | 1 | 1 | 1 | 1 | 5/5 |
| 2604.05918 | 1 | 1 | 1 | 0 | 1 | 4/5 |
| 2604.01185 | 1 | 1 | 1 | 1 | 1 | 5/5 |
| 2604.22231 | 1 | 1 | 1 | 1 | 0 | 4/5 — wait, corrected to 3/5 |
| 2604.20526 | 1 | 1 | 1 | 1 | 0 | 4/5 |
| 2604.16179 | 1 | 1 | 1 | 0 | 1 | 4/5 |
| 2604.03737 | 0 | 1 | 1 | 0 | 0 | 2/5 |
| 2503.20427 | 0 | 1 | 1 | 0 | 1 | 3/5 |

注：2604.22231 最终 IYPT = 3/5 (P=1, M=1, R=1, C=0, N=0)，总分 20/25。

## 最终决策

- mode: **standard**（最高分 25 >> 12，无特殊主题聚焦）
- Section A: 3篇（2601.12642, 2604.05918, 2604.01185）
- Section B: 5篇（2604.22231, 2604.20526, 2604.16179, 2604.03737, 2503.20427）
- paper_count: **8**
- top_score: **25**
