## H3 — Source Effects vs. ChatGPT (Model 2, No Interaction)

Expected direction: Other sources show **more bias** (+ for PB), **less credibility** (−), **less agreement** (−), **less action** (−) than ChatGPT.

| DV | Source | β | p | Trend as expected? | With 3× N, likely sig? |
|---|---|---|---|---|---|
| **PB Signed** | NS | +0.10 | .340 | ✓ Yes (more biased) | Borderline (t×√3 = 1.66) |
| | FOX | +0.37 | **.001** | ✓ **Yes — significant** | Already significant |
| | CNN | −0.12 | .256 | ✓ Right direction  | N/A (wrong direction) |
| | AP | −0.02 | .823 | — Near zero | No (t×√3 = 0.38) |
| **PB Absolute** | NS | +0.19 | **.019** | ✓ **Yes — significant** | Already significant |
| | FOX | +0.23 | **.006** | ✓ **Yes — significant** | Already significant |
| | CNN | +0.04 | .632 | ✓ Right direction | No (t×√3 = 0.83) |
| | AP | +0.03 | .738 | ✓ Right direction | No (t×√3 = 0.59) |
| **Credibility** | NS | −0.02 | .877 | ✓ Right direction | No (t×√3 = 0.28) |
| | FOX | −0.02 | .834 | ✓ Right direction | No (t×√3 = 0.36) |
| | CNN | +0.11 | .286 | ✗ Wrong direction (CNN > ChatGPT) | N/A (wrong direction) |
| | AP | +0.24 | **.025** | ✗ **Wrong direction — AP sig. more credible** | N/A (wrong direction) |
| **Agreement** | NS | +0.01 | .972 | ✗ Wrong direction | No (t×√3 = 0.07) |
| | FOX | +0.07 | .588 | ✗ Wrong direction | No (t×√3 = 0.93) |
| | CNN | +0.00 | 1.00 | — Zero | No |
| | AP | +0.12 | .364 | ✗ Wrong direction | No (t×√3 = 1.57) |
| **Action** | NS | −0.03 | .726 | ✓ Right direction | No (t×√3 = 0.61) |
| | FOX | −0.01 | .853 | ✓ Right direction | No (t×√3 = 0.33) |
| | CNN | +0.02 | .821 | ✗ Wrong direction | No (t×√3 = 0.40) |
| | AP | +0.11 | .137 | ✗ Wrong direction | Possibly (t×√3 = 2.58), but wrong direction |

### H3 Diagnosis

**Perceived bias is the only DV where the pattern works.** FOX and NS both show the expected effect (more biased than ChatGPT), especially for absolute magnitude. CNN and AP show essentially zero or wrong-direction effects — these are true nulls, not power issues.

**Credibility, agreement, and action are true nulls.** The coefficients are so close to zero (most |β| < 0.10 with SEs of ~0.10–0.13) that tripling the sample would not change the conclusion. The one exception is AP on credibility, which is significant in the *wrong* direction (AP is seen as more credible than ChatGPT).

---

## H4 — Source × AI Neutrality Interaction (Model 2, Simplified)

These are the interaction coefficients: how much the source-vs.-ChatGPT gap changes per 1-unit increase in AI Neutrality belief.

Expected direction: As AI Neutrality increases, ChatGPT's advantage **widens** → PB interactions should be **+** (others seen as even more biased), Credibility/Agreement/Action interactions should be **−** (others lose ground).

| DV | Source × AI_Neutrality | β | p | Trend as expected? | With 3× N, likely sig? |
|---|---|---|---|---|---|
| **PB Signed** | NS × AIN | +0.065 | .314 | ✓ Right direction | Borderline (t×√3 = 1.75) |
| | FOX × AIN | −0.099 | .125 | ✗ Wrong direction (gap narrows) | N/A (wrong direction) |
| | CNN × AIN | +0.000 | .996 | — Zero | No |
| | AP × AIN | +0.012 | .850 | ✓ Right direction | No (t×√3 = 0.33) |
| **PB Absolute** | NS × AIN | +0.033 | .498 | ✓ Right direction | No (t×√3 = 1.18) |
| | FOX × AIN | −0.012 | .808 | ✗ Wrong direction | No |
| | CNN × AIN | +0.005 | .915 | ✓ Right direction | No (t×√3 = 0.19) |
| | AP × AIN | −0.037 | .452 | ✗ Wrong direction | No |
| **Credibility** | NS × AIN | −0.134 | **.031** | ✓ **Yes — significant** | Already significant |
| | FOX × AIN | −0.059 | .347 | ✓ Right direction | Unlikely (t×√3 = 1.63) |
| | CNN × AIN | −0.075 | .231 | ✓ Right direction | Possibly (t×√3 = 2.08) |
| | AP × AIN | −0.137 | **.029** | ✓ **Yes — significant** | Already significant |
| **Agreement** | NS × AIN | −0.006 | .943 | ✓ Right direction | No (t×√3 = 0.12) |
| | FOX × AIN | +0.075 | .335 | ✗ Wrong direction | N/A (wrong direction) |
| | CNN × AIN | −0.103 | .183 | ✓ Right direction | Possibly (t×√3 = 2.30) |
| | AP × AIN | +0.036 | .644 | ✗ Wrong direction | N/A (wrong direction) |
| **Action** | NS × AIN | −0.083 | .068 | ✓ Right direction (marginal) | Yes (t×√3 = 3.17) |
| | FOX × AIN | −0.060 | .188 | ✓ Right direction | Possibly (t×√3 = 2.28) |
| | CNN × AIN | −0.113 | **.014** | ✓ **Yes — significant** | Already significant |
| | AP × AIN | −0.092 | **.044** | ✓ **Yes — significant** | Already significant |

### H4 Diagnosis

**Perceived bias: H4 doesn't work here.** The interactions are near zero or wrong-direction for FOX. More sample won't help.

**Credibility: Direction is right for all four sources**, but the significant effects are NS and AP (the non-partisan sources), not FOX and CNN. This means AI Neutrality belief shrinks the credibility *advantage* that NS/AP had over ChatGPT — it's a general halo effect, not a partisan-specific moderation. CNN might reach significance with 3× N.

**Agreement: Inconsistent.** FOX and AP go the wrong direction; CNN trends right but n.s.

**Action: Most promising DV for H4.** All four sources trend in the expected direction, CNN and AP are already significant, and NS and FOX would likely reach significance with more power. This suggests that people who believe AI is neutral show less behavioral engagement with non-ChatGPT sources relative to ChatGPT — and this pattern would likely hold up at larger N.

---

## Overall Power Assessment

| | True null (3× N won't help) | Underpowered (3× N might help) | Already significant |
|---|---|---|---|
| **H3** | Credibility, Agreement, Action (all sources) | PB Signed (NS only) | PB Signed (FOX), PB Absolute (FOX, NS) |
| **H4** | PB Signed/Absolute (all), Agreement (mixed) | Action (NS, FOX), Credibility (CNN) | Credibility (NS, AP), Action (CNN, AP) |

The story isn't really about power — it's that **ChatGPT is functionally equivalent to traditional sources on credibility, agreement, and action**, and only differs on perceived bias (and only from certain sources). For H4, **action intent is the one DV where the moderation pattern works broadly**.
