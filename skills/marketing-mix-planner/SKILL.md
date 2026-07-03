---
name: marketing-mix-planner
description: Design a coherent marketing mix (4P for products, 7P for services and experience-led businesses) that delivers a chosen positioning, tuned to the brand's lifecycle stage and objectives. Use whenever the user needs a marketing mix, 4P/7P plan, "how do we go to market", operational marketing plan, or wants product, price, place, and promotion decisions aligned into one coherent program. Push to use this after STP and value proposition are set, since the mix exists to deliver a position to a target — never in a vacuum.
argument-hint: "<brand + target/positioning if known>"
---

# Marketing Mix Planner (4P / 7P)

The marketing mix is the set of controllable levers a firm pulls to occupy its chosen position and hit its objectives. The levers only work when they are *mutually coherent* and all point at the same positioning — a premium position undercut by discount pricing or bargain-bin distribution collapses. This skill designs the mix as an integrated system, not four independent choices, and tunes it to the lifecycle stage.

## Trigger

User asks for a marketing mix, 4P/7P, go-to-market at the operational level, or an operational marketing program that combines product, price, place, and promotion. Also trigger when a strategy is set but the executional levers are undefined.

## Inputs

1. **Target segment and positioning** — the mix must serve these (pull from `segmentation-targeting-positioning`)
2. **Value proposition** — what value, quantified (pull from `value-proposition-design`)
3. **Lifecycle stage** — introduction/growth/maturity/decline (pull from `brand-lifecycle-diagnostic`); the mix emphasis shifts by stage
4. **Objective** — awareness, trial, share, loyalty, margin
5. **Business type** — pure product, service, or experience/subscription (decides 4P vs. 7P)
6. **Constraints** — budget, channel access, brand permission

## Process

### 1. Decide 4P vs. 7P

Use the classic **4P** for tangible products; extend to **7P** whenever service is a material part of the offer (most B2B, all subscription/SaaS, all experience businesses), because the extra levers are where much of the value and differentiation actually live.

- 4P: Product, Price, Place, Promotion
- 7P: + People, Process, Physical Evidence

### 2. Design each lever to serve the position

Work each lever with the positioning as the constraint. For every choice, ask "does this reinforce or contradict the position we chose?"

**Product** — features, quality level, design, packaging, brand, range/line breadth, warranties, service bundle. Decide the core (job done), actual (features/quality/brand), and augmented (service, warranty, support) product layers. In B2B, augmentation (support, customization, reliability) often carries the differentiation.

**Price** — list price, discount structure, payment/financing terms, price positioning vs. rivals. Must be consistent with the perceived value and the position (premium position needs a premium price to be credible). Hand the deep pricing work to `pricing-strategy`; here just ensure the price *level* fits the mix.

**Place (distribution)** — channel type (direct/indirect), length, intensity (intensive/selective/exclusive), coverage, and increasingly omnichannel/digital presence. Channel choice signals positioning (exclusive distribution says premium). Hand deep channel design to `distribution-channel-strategy`.

**Promotion (communication)** — the communication mix (advertising, personal selling, PR, sales promotion, direct/digital) and the message. Must speak the target's language and carry the positioning. Hand deep work to `marketing-communications-plan`.

**People** (7P) — everyone who touches the customer: recruiting, training, motivation, and the customer-facing behaviors that deliver the brand. In service and B2B, people *are* the product experience.

**Process** (7P) — how the service is delivered: steps, standardization vs. customization, speed, customer effort, self-service vs. human. Process design determines both cost and experience.

**Physical Evidence** (7P) — the tangible cues that make an intangible service credible: environments, equipment, signage, documents, digital UI, staff appearance. Reduces perceived risk.

### 3. Enforce internal coherence

Audit the mix as a whole. Every lever must be consistent with the positioning and with the other levers. Run this coherence check:

| Lever | Says what about positioning? | Consistent with the others? |
|-------|------------------------------|-----------------------------|
| Product | ... | ... |
| Price | ... | ... |
| Place | ... | ... |
| Promotion | ... | ... |
| People/Process/Physical (7P) | ... | ... |

Flag any contradiction (e.g., premium product + discount promo + mass distribution) and resolve it.

### 4. Tune the mix to the lifecycle stage

The right emphasis shifts as the brand ages:

| Stage | Product | Price | Place | Promotion |
|-------|---------|-------|-------|-----------|
| Introduction | Core, get it working; limited range | Skim (recover investment) or penetrate (deter entry) | Selective, seed key channels | Heavy: build awareness + drive trial |
| Growth | Extend features, quality, variants | Hold or start easing as rivals enter | Broaden channels aggressively | Shift to differentiation & preference |
| Maturity | Differentiate, refresh, bundle services | Defend; promotional/tactical; watch pocket price | Maximize coverage & efficiency | Loyalty, reminder, share defense |
| Decline | Prune range; add services or find new uses | Harvest or defensive cuts | Rationalize to profitable channels | Minimal; targeted retention or exit |

### 5. Sequence and resource

Turn the mix into an executable program: what happens first (dependencies — e.g., landing page live before ads), who owns each lever, timing (a Gantt-style view), budget split across levers, and the KPIs per lever.

## Output

### Mix Overview
Target, positioning, stage, objective — the constraints the mix serves.

### The Levers (4P or 7P)
Each lever's decisions, justified against the positioning and value proposition.

### Coherence Audit
The consistency table + any contradictions resolved.

### Stage Tuning
How the mix is set for the current lifecycle stage and what shifts as it moves.

### Execution
Sequence + dependencies, ownership, timing, budget split, and per-lever KPIs.

## Follow-up

Ask: "Would you like me to:
- Go deep on any single lever (pricing, distribution, or communication)?
- Build the full campaign and content calendar from the promotion lever?
- Set the metrics/KPI framework to track the mix?
- Assemble this into a complete marketing plan?"
