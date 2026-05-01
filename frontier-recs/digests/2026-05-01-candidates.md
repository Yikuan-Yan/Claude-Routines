# 前沿推荐候选池 · 2026-05-01

## Tier 2 桶选择

历史记录：
- 2026-04-24: Non-equilibrium statistical mechanics, Condensed matter (topological phases, strongly correlated systems)
- 2026-04-25: Quantum information, Astrophysics & cosmology
- 2026-04-26: Nonlinear dynamics & pattern formation, Soft matter & active matter
- 2026-04-30: Non-equilibrium statistical mechanics, Condensed matter (topological phases, strongly correlated systems)

本次（最近最少使用）：**Quantum information** + **Astrophysics & cosmology**

---

## 去重集（过去7天，共47篇）

来自 frontier-recs/digests/2026-04-24 至 04-30 及 papers-update/digests/2026-04-24 至 2026-04-29

主要排除（frontier-recs）：
2601.12642, 2604.05918, 2604.01185, 2604.22231, 2604.20526, 2604.16179, 2604.03737, 2503.20427,
2603.18880, 2504.03032, 2502.09953, 2604.14918, 2604.14569, 2602.10576, 2604.20678,
2603.02595, 2604.16724, 2602.23933, 2604.16994, 2603.08644, 2604.16173, 2603.18918,
2604.20635, 2406.01289, 2501.05088, 2410.17071, 2603.09620

主要排除（papers-update）：
2604.05918, 2604.01185, 2604.00484（注：下方以独立检索确认，papers-update 版本与 frontier-recs 独立），
2603.04737, 2604.20526, 2603.20973（后经确认仍纳入考虑），
DOI:10.1021/acs.langmuir.5c00419, DOI:10.1103/d2br-hl5x（papers-update 未收录，可纳入）

注：2604.00484（compliant walls turbulence）最终确认未出现于任何已有 digest，纳入候选池。

---

## 候选评分表

### Section A 候选（精选，分数 ≥ 20）

| ID | 标题（简） | 新颖 | 深度 | 方法 | 时效 | IYPT | 总分 | ⭐ | 研究关联 |
|----|-----------|------|------|------|------|------|------|----|----------|
| DOI: d2br-hl5x | Exactly Solvable Model of Wave-Mean Field Interaction in Integrable Turbulence | 5 | 5 | 5 | 5 | 1/5 | **21** | — | — |
| DOI: s41567-025-02791-2 | Conformal invariance in living biological matter (Nature Physics) | 5 | 5 | 4 | 5 | 2/5 | **21** | ⭐ | — |
| DOI: 1jkm-kybr | Long-Range Order in Strictly Short-Range Quasi-2D XY Model (PRL) | 5 | 5 | 4 | 5 | 2/5 | **21** | — | — |

### Section B 候选（速览，分数 18–20）

| ID | 标题（简） | 新颖 | 深度 | 方法 | 时效 | IYPT | 总分 | ⭐ |
|----|-----------|------|------|------|------|------|------|----|
| DOI: s41586-026-10449-z | Muon g−2 HVP to 0.48% (Nature) | 5 | 5 | 5 | 5 | 0/5 | **20** | — |
| DOI: s7rj-swb3 | Shape & oscillation modes of levitated multiphase drops (PRFluids) | 4 | 3 | 4 | 4 | 5/5 | **20** | ⭐ |
| DOI: s41567-026-03259-7 | Exceptional deficiency of non-Hermitian systems (Nature Physics) | 4 | 5 | 4 | 5 | 1/5 | **19** | — |
| 2604.26621 | LESnets: physics-informed neural operator for turbulence | 4 | 4 | 5 | 5 | 1/5 | **19** | ○ |

### 备用 / 淘汰

| ID | 标题（简） | 总分 | 淘汰原因 |
|----|-----------|------|----------|
| 2604.00484 | Compliant walls turbulent heat transfer | 18 | 分数足够但 Section B 额度已满 |
| 2604.23874 | Solver-aware turbulence closures (nudged LES) | 18 | 与 B4 LESnets 主题高度重叠 |
| 2602.17820 | Criticality in resting-state MEG | 16 | 时效偏低（Feb 2026），分数不足 |
| 2511.20075 | Elasticity and bubble pinch-off | 16 | Nov 2025，时效过低（T=2） |
| 2604.26290 | Scaling in supersonic turbulence DNS | 15 | arXiv HTML 404，内容不足 |
| 2603.20973 | Scaling laws in empirical networks | 13 | 方法和深度分数低，方向偏弱 |
| (unconfirmed) | Viscoelastic yo-yoing mixing layer | N/A | arXiv ID 未确认，无法引用 |

---

## IYPT 评分子项（P·M·R·C·N）

- P = Picturable（有直觉视觉）
- M = Multi-mechanism（机制耦合复杂度）
- R = Regime transition（存在 regime 转变）
- C = Classical core（无需量子力学的经典核心）
- N = Narratable（科普钩子清晰）

| ID | P | M | R | C | N | IYPT |
|----|---|---|---|---|---|------|
| d2br-hl5x | 0 | 1 | 0 | 0 | 0 | 1/5 |
| s41567-025-02791-2 | 1 | 1 | 0 | 0 | 0 | 2/5 |
| 1jkm-kybr | 0 | 1 | 1 | 0 | 0 | 2/5 |
| s41586-026-10449-z | 0 | 0 | 0 | 0 | 0 | 0/5 |
| s7rj-swb3 | 1 | 1 | 1 | 1 | 1 | 5/5 |
| s41567-026-03259-7 | 0 | 1 | 0 | 0 | 0 | 1/5 |
| 2604.26621 | 0 | 1 | 0 | 0 | 0 | 1/5 |

---

## 检索策略覆盖

- 策略 A：flu-dyn ×4, surface/interface ×2, AI for physics ×2, quantum-info ×2, astrophysics ×2, 补充 ×13 = **25次 tavily_search**
- 策略 B：PRL Editors' Suggestions, Nature Physics, PRFluids, APS Physics, Quanta, Science/PNAS = **6次 tavily_search**
- 策略 C：tavily_research (model=mini) ×1 + 补充 tavily_search ×2 = **3次**
- Extract：6次 tavily_extract（≥16 篇 HTML 内容）

**总 tavily_search：≥27次（满足 ≥20 要求 ✓），Extract ≥4次（6次）✓，候选 ≥12（16篇）✓**

---

## 最终决策

- mode: **standard**（最高分 21，3篇并列，无特殊主题聚焦）
- Section A: 3篇（d2br-hl5x, s41567-025-02791-2, 1jkm-kybr）
- Section B: 4篇（s41586-026-10449-z, s7rj-swb3, s41567-026-03259-7, 2604.26621）
- paper_count: **7**
- top_score: **21**
