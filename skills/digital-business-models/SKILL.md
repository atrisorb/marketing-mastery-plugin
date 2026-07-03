---
name: digital-business-models
description: Choose and design digital and as-a-service business models — SaaS, PaaS, IaaS, HaaS/hardware-as-a-service, on-premise vs. cloud vs. hybrid, API/platform/marketplace and two-sided models, and the servitization shift from selling products to selling outcomes. Covers packaging, pricing metaphors, value capture, and go-to-market implications for each. Use whenever the user works with software/tech/industrial firms and needs to pick or design a business model, decide on-prem vs. cloud, move to subscription/servitization, monetize an API/platform, or "should we sell the product or the outcome". Push to use this when the revenue model itself is the strategic question.
argument-hint: "<offering + current or target model>"
---

# Digital Business Models & Servitization

In the digital and industrial economy, *how* you sell often matters more than *what* you sell: the same capability can be a licensed product, a subscription, a usage-metered API, or an outcome-as-a-service — and each choice reshapes value creation, capture, marketing, and defensibility. This skill selects and designs the business model and the packaging/pricing metaphor that fits the offering and buyer, and plans the shift from products to services where warranted.

## Trigger

User works with software, technology, or industrial firms and must choose or design a business model; decide on-premise vs. cloud vs. hybrid; move to subscription or servitization; monetize an API, platform, or marketplace; or design packaging and value capture for a digital offering.

## Inputs

1. **The core capability/offering** and who buys it
2. **Current model** (if any) — license, subscription, usage, one-off hardware, service
3. **Buyer context** — B2B/B2C, enterprise vs. SMB, technical maturity, procurement/security constraints
4. **Cost structure** — marginal cost of serving one more customer/unit
5. **Strategic goal** — recurring revenue, scale, lock-in, margin, ecosystem

## Process

### 1. Map the "as-a-service" stack and deployment options

Place the offering on the service-model stack and the deployment spectrum, because they set the customer's control/responsibility trade-off:

**Service models (who manages what):**
- **On-premise** — customer buys a license and runs it on their own infrastructure. Maximum control/customization; customer bears ops, security, upgrades. Favored where data residency, latency, or regulation demand it.
- **IaaS** (Infrastructure-as-a-Service) — vendor provides compute/storage/network; customer manages OS and up.
- **PaaS** (Platform-as-a-Service) — vendor manages the platform/runtime; customer builds and runs apps.
- **SaaS** (Software-as-a-Service) — vendor manages everything; customer just uses it. Lowest customer burden, fastest time-to-value, recurring revenue for the vendor.
- **HaaS / hardware-** or **equipment-as-a-service** — physical asset delivered as a paid outcome/subscription (e.g., pay-per-use machinery, "pay-per-wash"). The product becomes a service; ownership stays with the provider.

**Deployment:** on-prem ↔ private cloud ↔ public cloud ↔ **hybrid/multi-cloud**. Choose by security/compliance, latency, cost model (capex vs. opex), and control needs.

### 2. Read the strategic implications of each model

| Model | Revenue shape | Vendor keeps | Customer gets | Watch-outs |
|-------|--------------|--------------|---------------|-----------|
| On-prem license | Large upfront + maintenance | Control ceded post-sale | Control, customization | Lumpy revenue; slow upgrades |
| SaaS subscription | Recurring (MRR/ARR) | Ongoing relationship, data, upgrades | Low burden, always current | Churn risk; must keep earning it |
| Usage / API metered | Scales with consumption | Alignment to customer value | Pay-for-what-you-use | Revenue volatility; metering design |
| HaaS / outcome | Recurring, outcome-linked | Asset + ongoing service | Capex → opex, risk transfer | Financing, asset lifecycle, service ops |
| Platform / marketplace | Take-rate / fees | Network effects, ecosystem | Access to both sides | Two-sided cold-start, governance |

The strategic prize of subscription/service models is a *durable relationship* and recurring revenue — but it inverts the burden: you must deliver value continuously or the customer leaves. Monetization becomes gradual (adoption ≠ immediate revenue; value accrues as usage deepens), so retention and expansion, not just acquisition, drive the economics.

### 3. Handle platform / two-sided / API models

If the offering connects two or more groups (buyers/sellers, developers/users):
- **Two-sided market logic** — each side's value depends on the other's participation; solve the cold-start (subsidize the harder-to-get side, seed one side first).
- **APIs as product** — treat the API as a first-class product with its own DX, docs, pricing (per-call, tiered, freemium), and developer marketing; the developer is the buyer.
- **Ecosystem/complementors** — value comes from complements and integrations; design partner/reseller programs (reseller ecosystems can be the primary scale engine for SaaS expansion).

### 4. Design packaging and the pricing metaphor

Decide *what unit the customer pays for* — this "value metric" is the most consequential packaging choice:
- Pick a **value metric** that scales with the value the customer receives (seats, usage/volume, transactions, outcomes, capacity). A good metric grows revenue as the customer succeeds and feels fair.
- **Tiering** — Good/Better/Best packages to serve segments and create upgrade paths; align features to willingness-to-pay by segment.
- **Freemium vs. free trial vs. demo** — free tier for viral/product-led motions (works when marginal cost ≈ 0 and the free tier both delivers value and creates a reason to upgrade); trials for time-boxed evaluation; demos for high-touch enterprise.
- **Add-ons and bundling** — expand revenue, but beware over-bundling at onboarding (too many add-ons early can *increase* complexity and *hurt* early retention). Sequence expansion after the customer reaches value.
Hand the number-setting to `pricing-strategy`; here decide the *structure* and *metric*.

### 5. Plan the go-to-market motion that fits the model

The model dictates the motion:
- **Product-led growth (PLG)** — the product acquires, converts, and expands users (freemium/self-serve); marketing feeds the top and removes friction. Fits low-touch SaaS/API.
- **Sales-led** — reps close and expand; marketing generates and nurtures pipeline (ABM). Fits high-ACV enterprise, on-prem, complex HaaS.
- **Channel/ecosystem-led** — resellers, integrators, marketplaces scale reach. Fits geographic expansion and platform models.
- **Hybrid** — PLG bottom-up + sales-assist for expansion (common in modern SaaS).

### 6. Plan the servitization shift (if moving product → service)

For a firm moving from selling products to selling outcomes/services:
- Shift the value proposition from features to *outcomes and availability* (uptime, results, cost-per-use).
- Rebuild economics around lifetime value and retention, not unit sales.
- Reconfigure operations: service delivery, customer success, asset/financing, data feedback loops.
- Manage the transition: culture, sales incentives (recurring vs. one-off), and cash-flow change from lumpy to recurring. Servitization commonly fails from over-focusing on technology and under-investing in the organizational shift.

## Output

### Model Recommendation
The selected service model and deployment, with the reasoning against buyer constraints and strategic goal.

### Value Capture Design
The value metric, tiering/packaging, and free-motion (freemium/trial/demo) — with the expansion path.

### Platform/API Considerations
(If relevant) two-sided/cold-start plan and developer/partner ecosystem design.

### Go-To-Market Motion
PLG / sales-led / channel / hybrid, and what marketing must do to feed it.

### Servitization Transition
(If shifting) the value-prop, economics, operations, and change-management plan.

## Follow-up

Ask: "Would you like me to:
- Set the actual prices and tiers (value-based pricing)?
- Define the SaaS/subscription metrics and unit economics to track?
- Design the product-led or ABM go-to-market motion?
- Build the servitization transition roadmap?"
