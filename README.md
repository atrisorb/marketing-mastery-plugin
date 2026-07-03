# 🤖 Marketing Mastery Plugin

An advanced marketing strategy suite for Claude Code. This plugin installs a comprehensive set of 18 professional AI skills spanning **B2B / industrial marketing**, **innovation marketing**, and **digital-era marketing** (SaaS, HaaS, on-premise, cloud, APIs, platforms), plus the cross-cutting strategy, mix, metrics, and sustainability toolkit. 

Built to make any agent that uses them a competent, applied marketing strategist for real brands — nascent or established.

## 🧠 How the suite is meant to be used

Start with **`brand-lifecycle-diagnostic`** — it reads where a brand is in its life (pre-launch → introduction → growth → maturity → decline → revitalization), separates the *stage* from the fixable *disease*, and routes you to the right skills for that stage. 

From there the skills chain naturally: analysis → strategy → mix → launch/growth → plan. The capstone **`marketing-plan-builder`** integrates everything into one board-ready document.

### Typical Workflow Flowchart

    brand-lifecycle-diagnostic
          │  (routes by stage)
          ▼
    market-environment-analysis ──► market-research-sizing
          │
          ▼
    segmentation-targeting-positioning ──► value-proposition-design
          │
          ▼
    marketing-mix-planner
       ├── pricing-strategy
       ├── distribution-channel-strategy
       └── marketing-communications-plan
          │
          ▼
    (context-specific) b2b-buying-behavior · account-based-marketing ·
       innovation-diffusion-strategy · new-product-launch-gtm ·
       digital-business-models · saas-growth-metrics ·
       customer-acquisition-retention · circular-economy-marketing
          │
          ▼
    marketing-plan-builder  (capstone — assembles the whole plan)

---

## 🧰 The 18 Skills

### Tier 0 — Diagnostic & orchestration
| Skill | What it does |
|-------|--------------|
| `brand-lifecycle-diagnostic` | Diagnoses the brand's life stage, separates stage from "disease," reads market orientation, and routes to the right playbook. **Run this first.** |

### Tier 1 — Strategic analysis
| Skill | What it does |
|-------|--------------|
| `market-environment-analysis` | PESTEL/STEEP, Porter's Five Forces, Value Chain + VRIO, weighted SWOT → TOWS action matrix |
| `segmentation-targeting-positioning` | Full STP: market qualification, segmentation bases (B2B & B2C), segment tests, targeting patterns, positioning statement + perceptual map, repositioning |
| `value-proposition-design` | Jobs-to-be-Done, Value Proposition Canvas, Kano model, value quantification (reference + differentiation value), proof |
| `market-research-sizing` | Research design (qual/quant), primary vs. secondary sources, TAM/SAM/SOM (top-down & bottom-up), demand forecasting |

### Tier 2 — Marketing mix (operational)
| Skill | What it does |
|-------|--------------|
| `marketing-mix-planner` | 4P→7P designed to deliver the positioning, coherence audit, lifecycle-stage tuning, execution |
| `pricing-strategy` | Cost/competition/value orientations, break-even, willingness-to-pay (Van Westendorp), skim vs. penetration, pocket-price waterfall, yield management |
| `distribution-channel-strategy` | Direct/indirect, length & intensity, intermediary types, function allocation, push/pull, omnichannel & e-commerce, trade marketing |
| `marketing-communications-plan` | AIDA/response ladder, message design, communication mix, budget (objective-and-task), integrated touchpoint plan, measurement |

### Tier 3 — B2B
| Skill | What it does |
|-------|--------------|
| `b2b-buying-behavior` | Buying center/DMU roles, buy-classes, buying process, uncertainty reduction, Kraljic matrix, transactional → relational marketing |
| `account-based-marketing` | ICP & account tiering (1:1/1:few/1:many), buying-group maps, orchestrated plays, content timed to journey stage, marketing–sales alignment |

### Tier 4 — Innovation
| Skill | What it does |
|-------|--------------|
| `innovation-diffusion-strategy` | Rogers adopter categories & S-curve, Bass model forecasting, Moore's chasm, disruptive innovation, technology S-curves, PLC/shark-fin *(+ math reference file)* |
| `new-product-launch-gtm` | Readiness gate, beachhead, launch narrative, 360° launch mix & Gantt, sales/channel enablement, launch metrics, failure-mode pre-mortem |

### Tier 5 — Digital era
| Skill | What it does |
|-------|--------------|
| `digital-business-models` | SaaS/PaaS/IaaS/HaaS, on-prem vs. cloud vs. hybrid, API/platform/two-sided models, packaging & value metric, PLG vs. sales-led, servitization |
| `saas-growth-metrics` | AARRR funnel, MRR/ARR, GRR/NRR, churn, CAC, LTV, LTV/CAC, CAC payback, unit economics, freemium/PLG, attribution *(+ formulas reference file)* |

### Tier 6 — Growth & sustainability
| Skill | What it does |
|-------|--------------|
| `customer-acquisition-retention` | Full lifecycle loop: acquisition → activation → retention/loyalty/CRM → expansion → referral, grounded in retention economics |
| `circular-economy-marketing` | Circular 4E mix (Experience/Everyplace/Exchange/Evangelism), product-service systems, consumer-barrier removal, credible (non-greenwashing) positioning |

### Tier 7 — Capstone
| Skill | What it does |
|-------|--------------|
| `marketing-plan-builder` | Assembles the full marketing/business plan: exec summary, situation analysis, SWOT/TOWS, strategy, mix program + Gantt, P&L/budget, control/KPIs |

---

## ⚙️ Installation

To use this plugin, you must have the Claude Code CLI installed. You can install it directly from GitHub or by cloning the repository locally.

### Option A: Direct from GitHub (Recommended)
From an interactive Claude Code session, run:

    /plugin marketplace add atrisorb/marketing-mastery-plugin
    /plugin install marketing-mastery@marketing-mastery

### Option B: Local Clone (Alternative)
If you prefer to have the repository files locally on your machine, run:

    git clone https://github.com/atrisorb/marketing-mastery-plugin.git
    cd marketing-mastery-plugin

Then, from an interactive Claude Code session executed inside the cloned directory, run:

    /plugin marketplace add .
    /plugin install marketing-mastery@marketing-mastery

### Uninstallation
To remove the plugin later (this process is fully reversible), run:

    /plugin uninstall marketing-mastery
    /plugin marketplace remove marketing-mastery

---

## 📚 Provenance & Frameworks

Grounded in university course lectures (Marketing B2B, Segmentation, Buying Process & Product, Distribution, Pricing, Communication, Business & Marketing Plan, Marketing of Innovation, Circular Economy) and cross-checked against academic and practitioner literature on industrial marketing, innovation diffusion (Rogers, Bass, Moore, Christensen), digital/SaaS business models and metrics, servitization, and distribution strategies. 

## 📄 License

This project is open-source and licensed under the **MIT License**. See the `LICENSE` file for details.