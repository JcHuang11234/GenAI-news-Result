## Quick Verdict

| Hypothesis | Result |
|---|---|
| Manipulation checks | ✅ Both passed |
| H2 — Source selection (Congruent > AI > Incongruent) | ✅ Supported (Congruent > AI confirmed; AI > Incongruent not significant) |
| H3 — Source effects on DVs | ⚠️ Partially supported for perceived bias only (FOX > ChatGPT); not supported for credibility, agreement, or action intent |
| H4 — AI Neutrality as source-specific moderator | ❌ Not supported as specified; AI Neutrality is a general positivity predictor, not source-specific |

---

## Manipulation Checks (Both Passed)

**Stance manipulation (§3.1):** One-way ANOVA, F(2, 1492) = 211, p < .001. Tukey post-hoc: all three congruence groups significantly different (Congruent M = 5.20, Neutral M = 4.43, Incongruent M = 3.31; all pairwise p < .001).

**Source manipulation (§3.2):** Correct identification rates 91–94% across all five sources (NS = 91.3%, FOX = 94.3%, CNN = 92.3%, AP = 93.7%, ChatGPT = 93.7%).

---

## Selective Exposure (Descriptive)

**Liberals:** AP (64%) → CNN (28%) → ChatGPT (7%) → FOX (<1%)
**Conservatives:** FOX (44%) → CNN (21%) → ChatGPT (21%) → AP (15%)

Ideology × source choice: χ²(3) = 120, p < .001; Fisher's p < .001.

*Note: The 21% conservative selection of ChatGPT is an interesting finding worth discussing.*

---

## H2 — Source Selection ✅ Supported

After dropping AP: Congruent = 59.7%, AI = 22.7%, Incongruent = 17.7%.

- Overall: χ²(2) = 57, p < .001; exact multinomial p = 3.2 × 10⁻⁶; Cramér's V = 0.397
- Congruent vs. AI: **significant** (p = 6 × 10⁻⁸)
- AI vs. Incongruent: **not significant** (p = .30)
- Congruent vs. Incongruent: **significant** (p = 2 × 10⁻¹⁰)

**Takeaway:** Participants preferred the congruent outlet, placed AI second, and avoided the incongruent outlet — but the AI vs. Incongruent gap was not reliable.

---

## H3 — Source Effects on DVs

All models use mixed-effects (random intercept for participant), fixed effects for news_source × article_stance, controlling for ideology + demographics. Reference levels: ChatGPT (source), Neutral (stance).

### Perceived Bias — Signed (−3 lib / +3 con): ⚠️ Partially Supported

| Model | Key result |
|---|---|
| (a) No interaction | news_source F(4, 1415) = 6.07, p < .001. Only **FOX** differed from ChatGPT (+0.37, t = 3.42, p = .001). CNN, AP, NS: n.s. Ideology: β = −0.09, p < .001. |
| (b) Interaction | Interaction F(8, 1415) = 0.55, p = .82 — **not significant** |

*Note: Singular fit warnings (61% of scores exactly 0). Absolute magnitude model is primary.*

*Random-Category robustness: Focal coefficients nearly identical; LRT n.s. Fixed-Category spec is appropriate.*

### Perceived Bias — Absolute Magnitude (0–3): ⚠️ Partially Supported

| Model | Key result |
|---|---|
| (a) No interaction | news_source F(4, 1138) = 3.18, p = .013. **FOX** (+0.23, p = .006) and **NS** (+0.19, p = .019) > ChatGPT. CNN, AP: n.s. |
| (b) Interaction | Interaction F(8, 1318) = 1.28, p = .25 — n.s. One marginal: CNN × Liberal article (β = +0.44, p = .041). |
| (c) AI vs. Partisan | F(1, 574) = 3.61, p = .058 (marginal); interaction with stance F(2, 824) = 0.49, p = .61. |

**Takeaway:** FOX (but not CNN or AP) produces significantly higher perceived bias magnitude than ChatGPT. Direction is consistent with H3 but not universal; source × stance interaction absent.

### Credibility (1–7): ❌ Not Supported

| Model | Key result |
|---|---|
| (a) No interaction | news_source F(4, 1161) = 2.25, p = .061 (marginal). Only **AP** > ChatGPT (+0.24, p = .025). Congruent/incongruent articles rated less credible. |
| (b) Interaction | Interaction F(8, 1364) = 0.95, p = .48 — n.s. |
| (c) AI vs. Partisan | F(1, 606) = 0.21, p = .65 — n.s. |

**Takeaway:** ChatGPT did not produce higher credibility than partisan outlets; AP trended slightly higher.

### Agreement (1–7): ❌ Not Supported

| Model | Key result |
|---|---|
| (a) No interaction | news_source F(4, 1175) = 0.34, p = .85 — n.s. Stance: F(2, 1286) = 4.63, p = .010. |
| (b) Interaction | Interaction F(8, 1396) = 0.67, p = .72 — n.s. |
| (c) AI vs. Partisan | F(1, 620) = 0.11, p = .74 — n.s. |

### Action Intent (1–7): ❌ Not Supported

| Model | Key result |
|---|---|
| (a) No interaction | news_source F(4, 1136) = 1.07, p = .37 — n.s. Stance: F(2, 1158) = 5.30, p = .005. |
| (b) Interaction | Interaction F(8, 1195) = 0.65, p = .73 — n.s. |
| (c) AI vs. Partisan | F(1, 570) = 0.01, p = .93 — n.s. |

---

## H4 — AI Neutrality Moderation ❌ Not Supported as Specified

H4 predicts AI Neutrality belief specifically moderates the source effect (i.e., the ChatGPT vs. partisan gap is larger for high-AI-Neutrality participants). All H4 models add AI_Neutrality (1–7) as a continuous moderator.

### Key pattern across all DVs:

| DV | AI Neutrality main effect | Source × AI Neutrality interaction | Stance × AI Neutrality |
|---|---|---|---|
| Perceived Bias (signed) | F(1, 1415) = 5.35, **p = .021** | F(4, 1415) = 1.69, p = .15 — n.s. | F(2, 1415) = 5.33, **p = .005** |
| Perceived Bias (absolute) | F(1, 281) = 0.06, p = .81 — n.s. | n.s. | F(2, 1217) = 5.26, **p = .005** |
| Credibility | F(1, 303) = 18.76, **p < .001** | F(4, 1160) = 1.67, p = .155 — n.s. | F(2, 1263) = 5.18, **p = .006** |
| Agreement | F(1, 320) = 30.07, **p < .001** | F(4, 1177) = 1.45, p = .21 — n.s. | All n.s. |
| Action Intent | F(1, 280) = 46.92, **p < .001** | F(4, 1136) = 1.81, p = .13 — n.s. | n.s. |

**Notable coefficient-level findings:**
- NS × AI_Neutrality (p = .031) and AP × AI_Neutrality (p = .029) for credibility — as AI Neutrality increases, the credibility advantage of NS and AP over ChatGPT shrinks.
- Three-way interactions not significant in any model.
- CNN × Liberal article significant for credibility in the full model (p = .009).

**Takeaway:** AI Neutrality predicts outcomes as a *general positivity belief* (people who trust AI rate news more credibly and agree more overall), but the predicted *source-specific moderation* is absent. A significant stance × AI Neutrality interaction for signed perceived bias suggests AI Neutrality affects how stance content is processed, not source-specific evaluations.


