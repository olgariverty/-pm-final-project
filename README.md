# Riverty Wallet-Ready Instant Card

> Product School · Product Management Certification · Final Project

- **Team:** Group 5 · Cohort 1
- **Market:** Germany
- **Repository:** https://github.com/olgariverty/-pm-final-project
- **Status:** Canonical combined project

## One-line pitch

Make the Riverty Card available in a supported phone wallet immediately after approval, creating earlier in-store access and sustained card usage without weakening partner checkout.

## Product bet

Frequent shoppers switch between payment methods because Riverty is available mainly through partner checkout. We are testing whether immediate wallet provisioning after card approval creates sustained repeat usage. Month 3 card retention is the primary metric; partner-checkout spend protects the merchant-first business.

## Decision framework

- **Ship:** Month 3 retention improves by at least the proposed 10 percentage points at p < 0.05 and the partner-checkout guardrail holds.
- **Iterate:** Direction is positive but below the MDE, the mechanism is weak, or the guardrail is inconclusive.
- **Kill:** No improvement or a negative primary result at full readout.
- **Pause:** Partner-checkout spend breaches the proposed 3% boundary in two consecutive monitoring periods, or a material operational risk occurs.

## Evidence boundaries

All user-research references and quantitative figures are synthetic and directional. The 69% baseline, +10 percentage-point MDE, 301 users per arm, 3% guardrail boundary, and supported wallet are planning inputs requiring validation before launch.

## Deliverables

| Module | Deliverable | File |
|---|---|---|
| M1 | Strategic discovery map | `01-product-thinking/strategic-map.md` |
| M1 | Problem hook and value proposition | `01-product-thinking/problem-hook.md` |
| M2 | Product-health synthesis | `02-discovery/ai-synthesis.md` |
| M2 | Competitive analysis and journey | `02-discovery/competitive-and-journey.md` |
| M2 | Journey map | `01-product-thinking/riverty-card-journey-map.md` |
| M3 | Hypothesis and success metrics | `03-analytics/hypothesis-and-metrics.md` |
| M4 | Roadmap, PRD and prototype | `04-roadmap/roadmap-prd-prototype.md` |
| M4 | PRD and prototype sprint | `04-roadmap/prd-and-prototype.md` |
| M4 | Interactive roadmap | `04-roadmap/riverty-card-roadmap.html` |
| M5 | Experimentation plan | `05-experimentation/experimentation-plan.md` |
| M6 | GTM strategy and dashboard | `06-launch/gtm-and-dashboard.md` |
| M6 | Individual insights | `06-launch/individual-insights.md` |
| M6 | Final presentation source | `06-launch/final-presentation.md` |
| M6 | Final HTML deck | `06-launch/final-presentation.html` |

## Prototype

[Open the current prototype](https://req-pilot.lovable.app/)

The current prototype is retained as the platform-agnostic base. It validates flow comprehension and recovery states only. It does not execute real wallet provisioning or payments and does not validate retention or business impact. A later iteration will add the approval entry point and make the timing difference—immediate availability versus after physical-card arrival—explicit.
