---
name: market-research-sizing
description: Plan market research and size a market — design qualitative and quantitative research, choose primary vs. secondary sources, size the opportunity with TAM/SAM/SOM (top-down and bottom-up), and translate demand into a defensible forecast. Use whenever the user needs market research design, market sizing, TAM/SAM/SOM, demand estimation, "how big is this market", survey/interview design, or the evidence base for a launch, plan, or investment case. Push to use this before committing budget, since sizing and evidence de-risk every downstream decision.
argument-hint: "<market/opportunity to research or size>"
---

# Market Research & Sizing

Decisions made without evidence are bets. This skill designs the research to reduce uncertainty and sizes the opportunity so investment is scaled to a real prize — not a guess. It covers what to research, how (methods and sources), and how to turn findings into a market size and a demand forecast with explicit assumptions.

## Trigger

User asks for market research design, market sizing, TAM/SAM/SOM, demand/sales forecasting, survey or interview design, competitive/market intelligence gathering, or the evidence base for a launch, business case, or plan.

## Inputs

1. **Decision the research must serve** — the research question drives everything; a study with no decision attached is waste
2. **Market / category and geography**
3. **Offering and business model** — unit economics differ for product vs. subscription
4. **What's already known** — prior data, current sales, hypotheses
5. **Constraints** — time, budget, access to respondents

## Process

### 1. Frame the research around a decision

State the decision and the specific unknowns blocking it. Convert each unknown into a research objective, then into questions. Distinguish:
- **Exploratory** — understand a fuzzy problem (what jobs/pains exist, how buyers decide)
- **Descriptive** — quantify what/who/how much (size, share, segment profiles)
- **Causal** — test cause and effect (will this message/price change behavior)

### 2. Choose methods (qual + quant)

Use qualitative to discover and frame, quantitative to measure and validate. They are complementary, not rivals.

| Method | Type | Best for | Watch-outs |
|--------|------|----------|-----------|
| In-depth interviews | Qual | Deep needs, buying process, B2B DMU | Small n, interviewer bias |
| Focus groups | Qual | Reactions, language, concept feedback | Groupthink, not projectable |
| Ethnography / observation | Qual | Actual behavior vs. stated behavior | Time-intensive |
| Surveys | Quant | Sizing attitudes, segments, satisfaction | Question design, sample bias |
| Conjoint / choice modeling | Quant | Trade-offs, feature/price value | Needs careful design |
| A/B tests / experiments | Quant | Causal proof of message/price/offer | Needs traffic/volume |
| Panel / longitudinal | Quant | Trends, churn, repeat behavior | Attrition |

For B2B, weight toward interviews and expert/channel input (few, high-value respondents); for B2C, weight toward surveys and behavioral data. Note the "say vs. do" gap: complement stated-preference (surveys) with revealed-preference (actual behavior) whenever possible.

### 3. Select sources

- **Secondary (desk) research first** — industry reports, trade associations, government/statistical data, analyst notes, financial filings, competitor sites, review platforms. Cheap and fast; use to frame and to avoid re-collecting what exists.
- **Primary research** — collect new data (interviews, surveys, experiments) for the questions secondary sources can't answer.
- **Syndicated/panel data** — purchased continuous data (retail scan, traffic, ad spend) where available.

If tools are connected, use web search and market-intelligence/SEO MCPs for secondary signals (traffic, keywords, funding, competitor scale). Always note source and recency so decision-makers can weigh confidence.

### 4. Size the market — TAM / SAM / SOM

Size the prize at three nested levels, and reconcile top-down with bottom-up:

- **TAM (Total Addressable Market)** — total demand if you had 100% of everyone who could ever buy the category.
- **SAM (Serviceable Available Market)** — the portion your business model, geography, and offering can actually serve.
- **SOM (Serviceable Obtainable Market)** — the realistic share you can capture in a defined period given competition and capacity.

Two independent methods, cross-checked:
- **Top-down** — start from a published market size, then narrow by segment/geography/qualification filters to SAM and SOM. Fast but inherits others' assumptions.
- **Bottom-up** — build from units: (number of target customers) × (penetration rate) × (units or contracts each) × (price). More defensible; forces explicit assumptions. Prefer bottom-up as the primary and use top-down as a sanity check. If they diverge wildly, find out why before trusting either.

Tie sizing to the demand funnel from qualification: potential → available/qualified → served → penetrated market. SOM is essentially the served-market share you can win.

### 5. Forecast demand

Translate size into a time-phased forecast with a method matched to the situation:
- **Analogy / proxy** — use a comparable product's adoption path when no history exists
- **Diffusion models (Bass)** — for new products, separate innovators (external influence, p) from imitators (word-of-mouth, q) to shape the adoption curve over time (hand off to `innovation-diffusion-strategy` for the full model)
- **Time-series / run-rate** — extend existing trends (moving average, YoY) for established products
- **Funnel math** — leads × conversion × price for pipeline-driven B2B/SaaS

Always present forecasts as a **range** (conservative / base / optimistic) with the assumptions that move between them. A point forecast hides its own uncertainty.

### 6. Validate and de-bias

- Check sample representativeness and size; flag low-confidence findings (small n, non-random samples).
- Watch for leading questions, self-selection, and confirmation bias.
- Triangulate: agreement across independent methods/sources raises confidence; divergence flags a question to resolve.

## Output

### Research Plan
Decision → objectives → questions → methods → sources → sample → timeline.

### Findings (if data provided/gathered)
Key insights tied back to the decision, with confidence levels and sources.

### Market Sizing
TAM / SAM / SOM with both top-down and bottom-up calculations, every assumption listed, and the reconciliation.

### Demand Forecast
Conservative / base / optimistic ranges over the relevant horizon, with the assumptions driving each.

### Confidence & Next Data
What's solid, what's shaky, and the highest-value data to collect next.

## Follow-up

Ask: "Would you like me to:
- Draft the actual survey or interview guide?
- Feed this sizing into a launch plan or business case?
- Model the adoption curve with a diffusion model?
- Turn segment findings into an STP strategy?"
