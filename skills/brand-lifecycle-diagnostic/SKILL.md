---
name: brand-lifecycle-diagnostic
description: Diagnose which life stage a brand or product is in (pre-launch, introduction, growth, maturity, decline, revitalization) and route to the right marketing playbook for that stage. Use this FIRST whenever the user wants a marketing strategy, plan, or diagnosis for a specific brand — new or established — or asks "what should we do next", "where are we", "is our brand declining", "how do we relaunch", or wants stage-appropriate priorities. Also use when the user names a company/product and asks for any marketing help without specifying where they are in the lifecycle.
argument-hint: "<brand or product name + a few facts about it>"
---

# Brand Lifecycle Diagnostic

The single most common mistake in applied marketing is running a playbook built for the wrong life stage: pouring money into awareness for a mature brand that actually has a retention problem, or optimizing churn for a product that has not yet found product-market fit. This skill diagnoses where a brand truly is and hands off to the stage-appropriate skills in the suite. Run it before any strategic work on a named brand.

## Trigger

Use when the user asks for a marketing strategy, plan, audit, or "what to do next" for a specific brand or product, or when they describe a business situation (sales slowing, new launch, crowded market, relaunch) without stating the lifecycle stage. When in doubt about stage, run this first — every other skill in the suite behaves differently by stage.

## Inputs

Gather what you can; infer the rest and state your assumptions. Do not block on missing data — a directional diagnosis from partial signals is the point.

1. **Brand / product** — name, category, and what it sells
2. **Market type** — B2B, B2C, or B2B2C; industrial/technical vs. consumer
3. **Business model** — one-off product sale, subscription/SaaS, HaaS/as-a-service, service, platform (routes to different metrics)
4. **Age & traction signals** — how long on market; revenue/units trend (growing fast, plateauing, declining); customer count trend
5. **Competitive signals** — number of competitors entering or exiting; price pressure; substitutes appearing
6. **Margin & pricing signals** — are prices/margins holding, rising, or eroding?
7. **What prompted the question** — launch, stalled growth, new competitor, falling sales, board pressure, etc.

## Diagnostic Process

### Step 1 — Place the brand on the lifecycle curve

Score the signals against the stage table. The dominant pattern wins; brands often straddle two stages (e.g., "late growth tipping into maturity") — say so.

| Signal | Introduction | Growth | Maturity / Saturation | Decline |
|--------|-------------|--------|----------------------|---------|
| Sales trend | Low, slow, uncertain | Accelerating | Peaked, flat | Falling |
| Sales growth rate | Near zero → positive | High, rising | Slowing to ~0 | Negative |
| Competitors | Few / none | Increasing rapidly | Many, consolidating | Exiting |
| Prices / margins | High (skim) or low (penetrate) | Starting to fall | Under pressure, promotional | Depressed |
| Customer focus | Get them to *try* | Win *preference* vs. rivals | Build *loyalty*, defend share | Harvest or exit |
| Cash | Negative (investment) | Tightening then improving | Strong (cash cow) | Declining |
| Marketing job | Create awareness + trial | Differentiate + scale | Retain + efficiency | Milk, reposition, or retire |

Two pre-curve and off-curve states matter too:

- **Pre-launch / concept** — not yet on the market; the job is validation (problem-solution fit, value proposition, market sizing, launch plan). This is the true state for "nascent brands" the user hasn't launched.
- **Revitalization / repositioning** — a mature or declining brand deliberately re-entering growth via new uses, new segments, added services/functionality, or redesign. Not a natural stage — a chosen intervention.

### Step 2 — Distinguish "stage" from "disease"

A falling metric does not always mean the lifecycle stage you'd guess. Separate the *stage* (structural position in the curve) from the *disease* (the fixable problem):

- Declining sales + product still fits market + weak nurture → **retention disease in a mature brand**, not decline. Route to retention, not relaunch.
- Flat sales + you have never crossed from early adopters to mainstream → **the chasm** (innovation stall), not maturity. Route to diffusion strategy.
- Great trial + poor repeat → **activation/value-delivery disease**, not an awareness problem. Do not buy more traffic.
- High churn + healthy acquisition in a subscription model → **leaky-bucket**; growth is an illusion. Route to retention + unit economics.

State the stage AND the most probable disease, because they drive different playbooks.

### Step 3 — Read the market orientation

How the company *thinks* constrains what it can execute. Classify its dominant orientation and flag the gap to a market/customer orientation, since most stage transitions require moving toward the latter:

- **Product/technology orientation** — "we have excellent products, customers will notice." Common in engineering-led B2B; dangerous at maturity.
- **Sales orientation** — "we push volume." Short-termist; erodes brand at maturity.
- **Market orientation** — segments served with tailored offers; the default healthy state.
- **Customer orientation** — one-to-one, relationship-led; strong in B2B and subscription.

### Step 4 — Assemble the diagnosis and route

Produce the diagnosis, then hand off to the specific suite skills that fit the stage (see routing table).

## Stage → Playbook Routing

| Stage / State | Primary jobs | Route to these suite skills |
|---------------|-------------|-----------------------------|
| Pre-launch / concept | Validate problem, size market, design value prop, plan launch | `market-research-sizing`, `value-proposition-design`, `segmentation-targeting-positioning`, `new-product-launch-gtm`, `marketing-plan-builder` |
| Introduction | Awareness, trial, early positioning, channel seeding | `marketing-communications-plan`, `innovation-diffusion-strategy`, `pricing-strategy` (skim vs. penetrate), `distribution-channel-strategy` |
| Growth | Differentiate, scale acquisition, cross the chasm, expand channels | `segmentation-targeting-positioning`, `innovation-diffusion-strategy`, `customer-acquisition-retention`, `marketing-mix-planner` |
| Maturity | Defend share, deepen loyalty, pricing discipline, efficiency | `customer-acquisition-retention`, `pricing-strategy`, `market-environment-analysis` (defensive), `account-based-marketing` (B2B) |
| Decline | Harvest, reposition, or exit; find new uses/segments | `innovation-diffusion-strategy` (new uses), `circular-economy-marketing` (new value models), `pricing-strategy` (defense/harvest) |
| Revitalization | Reposition, add services, enter adjacencies, redesign | `value-proposition-design`, `segmentation-targeting-positioning` (repositioning), `digital-business-models` (servitization), `marketing-mix-planner` |
| Any (context) | Understand structure, buyers, competitive forces | `market-environment-analysis`, `b2b-buying-behavior` (if B2B), `saas-growth-metrics` (if subscription) |

## Reference: lifecycle nuances that change the call

- **The curve is not destiny.** Maturity can last decades (Coca-Cola) or a product can skip stages. Use the curve to choose emphasis, not to predict doom.
- **Category vs. brand vs. product.** A brand can be mature while a specific product line is in introduction, or vice versa. Diagnose the level the user actually cares about, and name it.
- **B2B derived demand.** In industrial markets, the brand's stage is often pulled by the customer's industry cycle. A supplier can be "declining" only because its customers' end-market is. Check the demand chain before concluding.
- **Innovation ≠ growth stage automatically.** A genuinely new-to-world innovation lives on the *adoption* curve (innovators → early adopters → chasm → majority), which is not the same as the sales lifecycle. If the offering is discontinuous, prefer `innovation-diffusion-strategy` framing.
- **Subscription reshapes the curve.** For SaaS/HaaS, "sales" is less informative than cohort retention and net revenue retention; a brand can look mature in logos but be growing in revenue (or vice versa). Pull `saas-growth-metrics`.

## Output

Present the diagnosis in this structure:

### Lifecycle Diagnosis: [Brand]
- **Stage:** [stage, or "straddling X→Y"] — one-sentence justification tied to the strongest signals
- **Most likely underlying issue ("disease"):** [the fixable problem, distinct from the stage]
- **Market orientation:** [current] → [recommended shift, if any]
- **Confidence:** high / medium / low, with the 1-2 data points that would raise it

### Stage-Appropriate Priorities (next 1-3)
Numbered, specific to this brand and stage — not generic. Each with the *why* (linked to a signal).

### Recommended Playbook (routing)
The 2-4 suite skills to run next, in order, and what each will produce for this brand.

### Watch-outs
1-3 stage-transition risks (e.g., "trial is fine but repeat is unproven — validate activation before scaling spend").

## Follow-up

Ask: "Would you like me to:
- Run the top recommended skill now (e.g., build the STP, the launch plan, or the retention analysis)?
- Do a full market and competitive analysis to firm up the diagnosis?
- Build an integrated marketing plan that sequences all the stage-appropriate moves?"
