# Riverty Wallet-Ready Card

**Product School · Product Management Certification · Final Project**
**Group 5 · Cohort 1**

- **Repository:** https://github.com/olgariverty/-pm-final-project
- **Prototype:** https://req-pilot.lovable.app/
- **Market:** Germany
- **Evidence note:** Persona facts come from the assigned case. Quantitative inputs are synthetic and directional unless labelled as proposed decisions. Figures are labelled Case, Synthetic or Proposed throughout.

## One-line pitch

Test whether phone-wallet access creates durable Riverty Card usage beyond partner checkout without weakening Riverty's merchant-first business.

## Problem hook and value proposition

**Problem hook:** Lena uses BNPL on most non-trivial purchases but takes whichever provider appears at checkout. She knows Riverty, but rarely seeks it out, so Riverty only reaches her where partner merchants show it. A card could give her a reason to choose Riverty beyond partner checkout.

**Value proposition:** For Lena, a Riverty card could give her a reason to use Riverty beyond partner checkout. **Why now:** Riverty remains dependent on merchant checkout while Klarna and PayPal remain available.

## Executive summary

Riverty reaches consumers mainly when a partner merchant offers it at checkout. Moment of misery: where a partner merchant does not offer Riverty, Lena falls back to Klarna, PayPal, or a bank card.

This project proposes a controlled friends-and-family beta of **phone-wallet provisioning**. Eligible, activated Riverty cardholders in the variant can add their issued card to one supported phone wallet; the control group keeps the same card experience without wallet provisioning during the experiment.

The primary decision metric is **M3 card retention**: randomised activated cardholders with at least one card purchase on days 61–90 after randomisation. The experiment protects **partner-checkout spend per randomised participant** (cumulative days 1–90, zeros included) with a proposed boundary of no more than 3% below control.

## Decision requested

Approve a controlled friends-and-family beta of phone-wallet provisioning, subject to a feasibility review (which returns to the decision forum) and to wallet-provider, Risk, and Compliance readiness.

Scale from an S-tier beta to a targeted M-tier rollout only if M3 card retention reaches the **approved lift threshold** (current proposal: the +10 percentage-point MDE, at p < 0.05) and partner-checkout spend stays within the **approved boundary** (current proposal: no more than 3% below control).

## Decision rules (summary)

- **Ship:** approved lift threshold reached at p < 0.05 and the guardrail passes.
- **Iterate:** direction is positive but below the MDE.
- **Inconclusive:** the confidence interval includes zero; extend or redesign.
- **Kill:** the primary metric is clearly negative.
- **Pause enrolment:** cumulative partner-checkout spend since randomisation is more than 3% below control in two weekly reads after the minimum-data rule is set, or a material incident defined by Risk/Compliance occurs.

## Feasibility gate

Proposed design: 50/50 split, 301 participants per arm (80% power, p < 0.05), approximately 602 activated participants in total. If that sample is unattainable, the beta is treated as directional.

## Repository structure

- `01-product-thinking/` — problem, strategy, and journey
- `02-discovery/` — persona, alternatives, and evidence boundaries
- `03-analytics/` — hypothesis and metrics
- `04-roadmap/` — roadmap, PRD, and prototype
- `05-experimentation/` — A/B experiment brief
- `06-launch/` — GTM plan, insights, and final presentation

Open `06-launch/final-presentation.html` for the executive deck.

