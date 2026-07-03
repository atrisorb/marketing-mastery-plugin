# Diffusion Models — Reference

Math and interpretation for the quantitative and conceptual parts of `innovation-diffusion-strategy`. Read this when you need to actually apply, compute, or explain a diffusion/adoption model.

## Contents
1. The four diffusion-curve models (overview)
2. S-curve and bell curve (Rogers)
3. Linear trajectories — disruptive innovation (Christensen)
4. Shark fin — big-bang / "devastating" disruption (Downes & Nunes)
5. The Bass diffusion model (equations)
6. Bass parameters and typical values
7. Estimating Bass parameters
8. Worked interpretation
9. Extensions and cautions

---

## 1. The four diffusion-curve models (overview)

Innovation adoption is described by four canonical curve models. They are not rivals — they describe different *kinds* of innovation and market. Pick the one whose shape matches the innovation in front of you; using the wrong shape produces the wrong forecast and the wrong strategy.

| Model | Source | Shape | What it describes | Use it to… |
|-------|--------|-------|-------------------|-----------|
| **S-curve** | Rogers | Cumulative "S" (slow → steep → plateau) | Total penetration over time | Talk penetration, saturation, timing |
| **Bell curve** | Rogers | Normal bell | Adoption *rate* split into adopter segments | Know which segment you're selling to now |
| **Linear trajectories** | Christensen | Crossing performance trajectories | How a disruptive technology overtakes market demand from below | Spot disruption; decide attack-from-below vs. defend |
| **Shark fin** | Downes & Nunes | Near-vertical spike then collapse | Near-instant mass adoption and equally fast decline ("big-bang") | Plan for compressed, winner-take-all cycles |

The S-curve and bell curve are two views of the *same* smooth diffusion process (cumulative vs. marginal). The linear-trajectories and shark-fin models describe innovations that break the smooth-curve assumption — the first over the long run (disruption from below), the second in the extreme short run (explosive then devastating).

---

## 2. S-curve and bell curve (Rogers)

**S-curve (cumulative adopters, N(t)):** adoption starts slowly (few innovators), accelerates as word-of-mouth kicks in, then flattens as the market saturates toward its ceiling (market potential m). Use it to reason about *how far and how fast* penetration goes.

**Bell curve (new adopters per period, S(t)):** the derivative of the S-curve. Its area sums to m, and it partitions adopters into Rogers' segments by *when* they adopt and *why*:

| Segment | ~Share | Cumulative | Buys because |
|---------|--------|-----------|--------------|
| Innovators | 2.5% | 2.5% | Love the new; external influence |
| Early adopters | 13.5% | 16% | Vision, first-mover advantage |
| Early majority | 34% | 50% | Pragmatism, proven value |
| Late majority | 34% | 84% | Pressure, don't be left behind |
| Laggards | 16% | 100% | Only when forced |

The gap between early adopters and early majority is where Moore's **chasm** sits. Speed along the curve is governed by Rogers' five determinants: relative advantage, compatibility, complexity, trialability, observability.

---

## 3. Linear trajectories — disruptive innovation (Christensen)

This model plots **performance against time** as a set of near-linear trajectories, and explains *why* a seemingly inferior innovation can overtake established ones. It distinguishes two kinds of line:

- **Technology-performance trajectories** — how fast a product's capability improves over time (in the lecture's notation, technologies **A** and **C**).
- **Market-demand trajectories** — how much performance each market tier can actually *absorb/use* (markets **B** and **D**): a demanding high-end tier and a less-demanding low-end / new-market tier.

The key structural fact: **technology usually improves faster than customers' ability to use it.** So a sustaining technology (A), by serving its best customers, keeps climbing and eventually *overshoots* what even the high-end market (B) needs — "performance oversupply." That overshoot opens the door underneath.

A **disruptive** technology (C) enters *below* the performance the mainstream demands — it is "not good enough" for mainstream customers at first, so incumbents ignore it. It takes root in the low end or in a **new market** (D) that values other attributes (cheaper, simpler, more convenient). Then it improves along its own trajectory until it **rises to meet the mainstream demand line** — at which point it satisfies mainstream customers too, and displaces the incumbents, who have fled up-market chasing margin.

**Strategic implications:**
- *Challenger:* don't attack incumbents head-on where they're strong; enter where they're happy to cede (low end, non-consumers, a new use), then climb. Compete on a *different* performance dimension initially.
- *Incumbent:* watch trajectories, not just today's performance ranking. A product that is worse on paper today can win if its improvement trajectory is steeper while you over-serve. Don't dismiss "not good enough" entrants.
- Distinguish **sustaining** innovation (better products for your best existing customers, along the established trajectory) — which favors incumbents — from **disruptive** innovation, which favors attackers from below.

This is a *long-run* dynamic: the crossover can take years. It answers "why won't this die / why did the cheap thing win," which the smooth S-curve cannot.

---

## 4. Shark fin — big-bang / "devastating" disruption (Downes & Nunes)

For some (especially digital, networked, platform) innovations the smooth bell curve is replaced by a **shark fin**: a near-vertical rise followed by an almost-as-vertical fall. Almost everyone adopts almost at once, and then abandons almost as fast when the next thing arrives. It is sometimes called **devastating innovation** because incumbents get no gradual ramp to react to — the disruption is near-instant and near-total.

**Why the curve collapses into a fin:** near-perfect and instant information flow, products that are *better AND cheaper from day one* (not the usual "cheaper but worse" of classic disruption), zero-friction global distribution, and platform/network effects. Rogers' five adopter segments collapse into essentially **two**: a brief pool of **trial users**, then **everybody else** adopting simultaneously — there is no slow majority ramp to ride.

**The four stages (Downes & Nunes):**
1. **The Singularity** — pre-bang experimentation; many cheap trials, most fail quietly.
2. **The Big Bang** — one experiment ignites and adoption explodes almost vertically.
3. **The Big Crunch** — saturation hits fast; the market collapses just as sharply as the next disruption arrives or the fad passes.
4. **Entropy** — aftermath; exit and residual/decline.

**Strategic implications:**
- Expect **compressed life cycles**; plan to launch fast, scale instantly, and *exit or reinvent* before the crunch — don't over-invest in defending a single S-curve.
- Run **continuous cheap experiments** (you can't predict which ignites); be ready to pour resources behind the one that catches.
- Incumbency and gradual response are liabilities here; the winners are ready to cannibalize themselves. Forecast with scenarios, not a smooth curve — Bass and Rogers *underfit* shark-fin markets.

---

## 5. The Bass diffusion model (equations)

The Bass model (1969) quantifies the smooth S-curve/bell-curve process by combining two adopter types:
- **Innovators** — adopt due to *external* influence (media, advertising), independent of how many others have adopted. Coefficient of innovation, **p**.
- **Imitators** — adopt due to *internal* influence (word of mouth), proportional to how many have already adopted. Coefficient of imitation, **q**.

**Core equation (continuous form):**
```
f(t) / (1 − F(t)) = p + q · F(t)
```
- `f(t)` = fraction of the market adopting at time t (adoption rate)
- `F(t)` = cumulative fraction adopted by time t
- `p` = coefficient of innovation (external influence)
- `q` = coefficient of imitation (internal influence / word of mouth)

**Adopters per period**, with market potential `m` (ultimate adopters):
```
S(t) = m · f(t) = [ p + (q/m) · N(t) ] · [ m − N(t) ]
        new adopters = (external pull + word-of-mouth) × (market remaining)
```
where `N(t)` = cumulative adopters so far.

**Closed-form cumulative solution:**
```
F(t) = [ 1 − e^(−(p+q)t) ] / [ 1 + (q/p) · e^(−(p+q)t) ]
```

**Time of peak adoption:**
```
t* = ln(q/p) / (p + q)
```
**Peak new-adopters per period** ≈ `m·(p+q)² / (4q)`.

---

## 6. Bass parameters and typical values

- **p (innovation)** — usually small; empirically ~0.01–0.03. Higher p → earlier, faster initial uptake (marketing/media-driven).
- **q (imitation)** — usually much larger; empirically ~0.3–0.5. Higher q → stronger word-of-mouth, steeper take-off, sharper peak.
- **m (market potential)** — ultimate adopters (size from `market-research-sizing` SAM/SOM).

Rules of thumb:
- **q > p** in almost all cases → the characteristic S-shape.
- Large q/p → later but sharper peak (word-of-mouth dominates).
- p close to q → earlier, flatter diffusion (media-driven).

---

## 7. Estimating Bass parameters

1. **Analogy** — borrow p, q from a comparable, already-diffused product (best pre-launch).
2. **Early sales fit** — once a few periods of real data exist, fit p, q, m by (non)linear least squares; early estimates are unstable, so widen the range and refit as data arrive.
3. **Judgment + tests** — set m from sizing, choose p, q from published category benchmarks (durables, tech, pharma differ), then sensitivity-test.

Always present the forecast as **conservative / base / optimistic**, driven mainly by the m and q assumptions.

---

## 8. Worked interpretation (illustrative)

m = 100,000; p = 0.02; q = 0.40.
- **Peak timing:** t* = ln(0.40/0.02)/(0.42) = ln(20)/0.42 ≈ 3.0/0.42 ≈ **7.1 periods**.
- **Shape:** q ≫ p → slow first periods, steep climb, pronounced peak ~period 7, then saturating decline in *new* adopters.
- **So-what:** don't judge the launch by period-1 sales; build capacity for the ~period-7 surge; front-load awareness spend (raises effective p, pulls the curve left); seed word-of-mouth/references (raises q, steepens take-off — the chasm-crossing "peer reference" mechanism).

Compute exact per-period adopters by iterating `S(t) = [p + (q/m)·N(t)]·[m − N(t)]`, updating N each period.

---

## 9. Extensions and cautions

- **Match the model to the innovation:** smooth Bass/Rogers for continuous/incremental innovations; **linear trajectories** when a cheaper/simpler entrant may overtake from below over years; **shark fin** for digital/platform goods with explosive-then-collapsing adoption. Forcing a smooth curve onto a disruptive or shark-fin case gives a confidently wrong forecast.
- **Repeat purchase / subscriptions:** basic Bass is for one-time adoption. For subscriptions, combine adoption with retention/churn — a product can peak in *adopters* while still growing in *active users and revenue*, or the reverse (leaky bucket). Pair with `saas-growth-metrics`.
- **Successive generations:** technology generations replace each other; use successive-generation Bass variants or treat each as a new S-curve (link to technology S-curve discontinuities).
- **Marketing-mix effects:** generalized Bass models let price and advertising shift p, q, and timing — useful to test "what if we spend more on launch awareness."
- **Discontinuous innovations & the chasm:** across a chasm the early-adopter and majority markets behave almost as separate diffusion processes — don't fit one smooth curve across the gap.
- **Culture:** q (word-of-mouth strength) varies by culture and social structure; don't transplant parameters across very different markets.

Bottom line: the curve models are planning lenses. Their value is forcing explicit assumptions about market size, external pull, word-of-mouth, performance trajectories, and cycle speed — and showing how launch spend, references, and disruption bend the shape.
