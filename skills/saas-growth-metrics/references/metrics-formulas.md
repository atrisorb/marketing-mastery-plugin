# SaaS & Growth Metrics — Formulas, Examples, Benchmarks

Exact definitions and worked math for `saas-growth-metrics`. Read when you need to actually compute metrics or explain the formulas.

## Contents
1. Recurring revenue
2. Churn & retention
3. CAC
4. LTV
5. Ratios & payback
6. Funnel & conversion
7. Benchmarks (rules of thumb)
8. Worked example

---

## 1. Recurring revenue

- **MRR** = Σ (monthly recurring fee across all active subscriptions). Convert annual plans to monthly (ACV/12).
- **ARR** = MRR × 12 (only truly-recurring revenue; exclude one-off services).
- **MRR bridge (movement):**
  `End MRR = Start MRR + New + Expansion + Reactivation − Contraction − Churned`
  Always decompose growth this way — it shows the *engine*, not just the total.
- **ARPA** (avg revenue per account) = MRR / active accounts.

---

## 2. Churn & retention

Pick a consistent period (usually monthly for SMB, annual for enterprise).

- **Customer (logo) churn rate** = customers lost in period / customers at start of period.
- **Gross revenue churn** = MRR lost (churn + contraction) / MRR at start. Floor 0%; you can't gross-churn less than nothing.
- **Gross Revenue Retention (GRR)** = 1 − gross revenue churn = (Start MRR − churn − contraction) / Start MRR. **Ceiling = 100%.**
- **Net Revenue Retention (NRR)** = (Start MRR − churn − contraction + expansion) / Start MRR.
  - NRR > 100% → base grows without any new customers (elite).
  - NRR < 100% → you must run just to stand still.
- **Average customer lifetime (months)** = 1 / monthly customer churn rate.
  (e.g., 2% monthly churn → 1/0.02 = 50 months average lifetime.)
- **Cohort retention** = for each signup cohort, % still active (or % revenue retained) at month 1, 2, 3, … Plot the curve; flattening above zero = product-market fit.

---

## 3. CAC (Customer Acquisition Cost)

- **CAC** = total sales & marketing spend in a period / new customers acquired in that period.
  - Include *fully loaded* costs: ad spend, salaries, tools, commissions, content — not just media.
  - Segment CAC by channel and by segment; blended CAC hides which channels work.
- **Blended vs. paid CAC:** blended includes organic (flatters the number); paid CAC isolates acquisition efficiency. Report both.

---

## 4. LTV (Lifetime Value)

Use the gross-margin version (revenue alone overstates value):

- **Simple LTV** = ARPA × gross margin % × average customer lifetime
  = ARPA × gross margin % × (1 / customer churn rate).
- **Equivalent form** = (ARPA × gross margin %) / churn rate.
- **With expansion (better):** replace churn with *net* churn; if NRR > 100%, use an LTV model that accounts for growing revenue per account (LTV can be much higher, even theoretically unbounded as net churn → 0). Be conservative; don't book expansion you haven't proven.

Example: ARPA €100/mo, gross margin 80%, monthly churn 2%.
LTV = (100 × 0.80) / 0.02 = €4,000.

---

## 5. Ratios & payback

- **LTV / CAC** = LTV ÷ CAC.
  - ~3:1 is the classic "healthy" target.
  - <1:1 → you lose money on every customer (unsustainable).
  - ≫3:1 (e.g., 5:1+) → often *underinvesting* in growth; you could spend more to grow faster.
- **CAC payback period (months)** = CAC / (ARPA × gross margin %).
  - <12 months is a common SMB SaaS bar; enterprise tolerates longer.
- **Magic number** = (net new ARR in quarter × 4... commonly: ) net new ARR ÷ prior-period S&M spend. ≥0.75 suggests efficient, scalable growth.
- **Burn multiple** = net cash burned / net new ARR. Lower is better (≤1 is strong); measures capital efficiency of growth.
- **Rule of 40** (growth-stage health) = revenue growth rate % + profit margin % ≥ 40 signals a healthy balance of growth and profitability.

---

## 6. Funnel & conversion

- **Stage conversion** = entering next stage / entered this stage (e.g., MQL→SQL rate).
- **Overall funnel** = product of stage rates (visitors → signup → activated → paid → retained).
- **Free→paid conversion** (freemium) = paying users / total free users. Self-serve freemium is often low single-digit %.
- **Activation rate** = users reaching the defined "aha"/first-value action / new users.
- **CPL** = spend / leads; **CPA** = spend / conversions; **ROAS** = revenue / ad spend.
- **Funnel/pipeline math (B2B):** leads × MQL rate × SQL rate × win rate × ACV = revenue. Invert to back out how many leads a revenue target needs.

---

## 7. Benchmarks (rules of thumb — directional, vary by segment)

| Metric | Rough healthy range | Notes |
|--------|--------------------|-------|
| LTV/CAC | ~3:1 | <1 bad; ≫3 may mean underinvesting |
| CAC payback | <12 months (SMB) | Enterprise can be 18-24 |
| Monthly logo churn | 1-2% (SMB), <1% (enterprise) | Annualize for enterprise |
| NRR | >100% good, >120% elite | Expansion-driven |
| GRR | >90% strong | Pure stickiness |
| Free→paid | 1-5% self-serve | Higher for reverse-trial |
| Activation | varies; higher is better | Define "first value" explicitly |
| Rule of 40 | ≥40 | growth% + margin% |
| Gross margin | 70-85%+ (SaaS) | Lower for HaaS/usage-heavy |

Benchmarks are context-dependent (ACV, segment, motion). Use them to spot outliers and ask "why," not as pass/fail gates.

---

## 8. Worked example (mini unit-economics check)

Given: ARPA €100/mo, gross margin 80%, monthly churn 2%, blended CAC €1,200.
- Avg lifetime = 1/0.02 = 50 months.
- LTV = 100 × 0.80 × 50 = €4,000.
- LTV/CAC = 4,000 / 1,200 = **3.3:1** → healthy.
- CAC payback = 1,200 / (100 × 0.80) = 1,200 / 80 = **15 months** → a bit long for SMB; watch it.
- Verdict: acquisition is profitable and LTV/CAC is healthy, but payback >12 months means cash is tied up longer than ideal — either lower CAC, raise price/margin, or drive expansion (lift NRR) to shorten effective payback.

Always sanity-check that churn, margin, and CAC are measured over consistent periods and populations before trusting the ratios.
