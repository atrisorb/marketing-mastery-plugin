---
name: saas-growth-metrics
description: Define, calculate, and act on subscription/SaaS and digital growth metrics — MRR/ARR, gross and net revenue retention, logo and revenue churn, CAC, LTV, LTV/CAC, CAC payback, the AARRR pirate funnel, activation, expansion, and unit economics — plus the marketing-funnel and attribution metrics. Use whenever the user runs a subscription/SaaS/HaaS/app/digital business and needs a metrics framework, KPI dashboard, unit-economics check, churn/retention analysis, "are our unit economics healthy", CAC/LTV, or growth-model math. Push to use this whenever recurring revenue is involved, since one-off-sale metrics mislead here.
argument-hint: "<business + the metric question or available numbers>"
---

# SaaS & Growth Metrics

In a subscription business, revenue is *rented, not earned once* — so the metrics that matter are about keeping and expanding customers over time, not just acquiring them. A business can look healthy on new logos while quietly bleeding out through churn (the leaky bucket). This skill installs the right metric framework, computes the unit economics, and turns the numbers into decisions.

## Trigger

User runs a subscription/SaaS/HaaS/app/digital business and needs a metrics or KPI framework, dashboard, unit-economics assessment, churn/retention analysis, CAC/LTV, growth-model math, or funnel/attribution metrics. Also trigger whenever recurring revenue makes one-off-sale metrics (units, gross margin only) insufficient.

## Inputs

1. **Business model** — subscription, usage, freemium, hybrid; contract length; ACV
2. **Numbers available** — revenue, customers, churn, spend, conversion (any subset)
3. **The question** — health check, target-setting, diagnosing a stall, board reporting
4. **Motion** — product-led vs. sales-led (changes benchmark expectations)

## Process

### 1. Frame with the AARRR "pirate" funnel

Organize growth into the five stages so metrics attach to a lever, not float free:

| Stage | Question | Core metrics |
|-------|----------|-------------|
| **Acquisition** | Do people find us? | Traffic, leads, signups, CAC, channel mix |
| **Activation** | Do they reach first value? | Activation rate, time-to-value, onboarding completion |
| **Retention** | Do they keep using/paying? | Churn, retention curves, DAU/MAU, NRR |
| **Referral** | Do they bring others? | Viral coefficient, referral/NPS |
| **Revenue** | Do they pay and expand? | MRR/ARR, ARPA, expansion, LTV |

The most common mistake is over-indexing on Acquisition while Activation and Retention leak — fix the leaks before pouring in more traffic.

### 2. Establish the recurring-revenue base

- **MRR / ARR** — monthly/annual recurring revenue; the heartbeat metric. Decompose MRR movement into **new + expansion + reactivation − contraction − churn** so you see *why* it moved, not just that it did.
- **ARPA/ARPU** — average revenue per account/user.
- **Bookings vs. revenue vs. cash** — don't confuse a signed contract, recognized revenue, and cash collected.

### 3. Measure retention properly (the decisive metrics)

- **Logo churn** vs. **revenue (gross $) churn** — losing small accounts ≠ losing revenue; track both.
- **Gross Revenue Retention (GRR)** — revenue kept before expansion; ceiling is 100%.
- **Net Revenue Retention (NRR)** — revenue kept *including* expansion; >100% means the existing base grows even with zero new customers (the hallmark of elite SaaS).
- **Cohort retention curves** — track each signup cohort over time; a curve that flattens above zero signals product-market fit; one that decays to zero signals a leaky bucket.
- Distinguish **adopters vs. active users vs. payers** — in subscription models these diverge, and monetization lags adoption; growth in adopters can mask churn in users.

### 4. Compute unit economics

The two-question health test: *can we acquire a customer profitably, and do we keep them long enough to profit?*

- **CAC** — fully-loaded sales+marketing cost to acquire one customer.
- **LTV** — gross-margin-adjusted lifetime value of a customer.
- **LTV / CAC** — value returned per acquisition dollar; **~3:1** is a common healthy benchmark (much higher may mean underinvesting in growth; below ~1 is unsustainable).
- **CAC payback (months)** — how long to recover CAC from margin; **<12 months** is a common healthy bar for SMB SaaS.
- **Magic number / burn multiple** — capital efficiency of growth.

See `references/metrics-formulas.md` for exact formulas, worked examples, and benchmark ranges.

### 5. Watch the freemium / PLG funnel (if applicable)

- **Free→paid conversion rate** — the freemium lever; typically low single-digit % for self-serve.
- **Free-tier economics** — free users cost money; the free tier must both deliver value and create a reason to upgrade, or it's a cost sink.
- **Product-qualified leads (PQLs)** — users whose in-product behavior signals readiness to buy; the PLG analogue of MQLs.

### 6. Add the marketing-funnel and attribution layer

Connect marketing to revenue so spend is judged on outcomes:
- **Funnel conversion:** MQL → SQL → opportunity → win, with rates at each stage.
- **Channel efficiency:** CPL, CPA, ROAS by channel.
- **Attribution:** first-touch (awareness), last-touch (conversion), or multi-touch (U-shaped/data-driven) — pick a model, know its bias, and use it directionally, not as truth.
(For the full marketing-metric catalog and attribution models, this pairs with performance-reporting practice.)

### 7. Turn metrics into decisions

Numbers are only useful if they change an action. For each key metric, state: the current value, the benchmark/target, the trend, the likely cause, and the lever. Prioritize the one or two metrics that gate growth right now (usually a retention or activation metric, not acquisition).

## Output

### Metric Framework
The AARRR map populated with this business's metrics and which stage is the current constraint.

### Recurring-Revenue & Retention
MRR/ARR movement decomposition, GRR/NRR, cohort read, and the leaky-bucket check.

### Unit Economics
CAC, LTV, LTV/CAC, CAC payback — computed (see reference file) with benchmark comparison and verdict.

### Funnel & Freemium
Conversion rates by stage/channel and (if PLG) free→paid and PQL health.

### Decisions
The 1-3 metrics gating growth, their likely causes, and the levers to pull.

## Follow-up

Ask: "Would you like me to:
- Compute your unit economics from your actual numbers (I'll use the formulas reference)?
- Build a KPI dashboard spec for ongoing tracking?
- Diagnose the churn/retention problem in depth?
- Model growth under different CAC/churn/expansion assumptions?"
