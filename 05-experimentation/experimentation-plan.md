# A/B Experiment Brief (Module 5)

## Experiment

**Riverty Wallet-Ready Instant Card — immediate phone-wallet provisioning at approval.**

## Parameters

| Parameter | Decision |
|---|---|
| Feature under test | Offer provisioning of an issued Riverty Card to one supported phone wallet immediately after approval, rather than after physical-card arrival |
| Design persona | Nadine, 38, a frequent shopper who uses several payment methods and wants fewer payment decisions |
| Experiment cohort | Newly approved frequent Riverty users in Germany with an issued card and a compatible device |
| Expected outcome | Higher repeat card usage through in-store availability before physical-card arrival |
| Primary success metric | Month 3 card retention: percentage of randomised approved cardholders with at least one Riverty Card purchase in their Month 3 observation window |
| Baseline | 69% synthetic planning benchmark; validate comparability before launch |
| Guardrail | Partner-checkout Riverty spend per randomised participant, variant versus control |
| Guardrail boundary | Proposed: no more than a 3% relative reduction versus control |
| MDE | +10 percentage points absolute, from 69% to 79% — proposed |
| Sample size | 301 users per arm; 602 total — recalculate if the baseline or MDE changes |
| Traffic split | 50/50 |
| Power / significance | 80% power; p < 0.05, two-sided |
| Participant duration | Three months per participant |
| Read date | After the final enrolled participant completes the Month 3 observation window |

All figures are synthetic planning inputs or proposed thresholds, not observed Riverty performance or approved business limits.

## Control vs variant

### Control (A)

The approved participant receives the same issued Riverty Card and can use its existing online functionality. Phone-wallet provisioning becomes available only after the physical card arrives.

### Variant (B)

The same cardholder receives the same card and terms, but phone-wallet provisioning is offered immediately after approval. The flow includes authentication, progress, success, clear failure reason, retry, and support access.

### Held constant

- Application, KYC, eligibility, approval criteria, and card issuing.
- Card terms, credit limit, pricing, repayment, and fraud controls.
- Existing online card functionality and physical-card fulfilment.
- Supported wallet platform and wallet-add flow; only availability timing differs.
- Support model, app version, event definitions, and measurement windows.
- No nudges, promotions, rewards, instalments, or second wallet during the experiment.

## Hypothesis

> We believe that offering newly approved frequent Riverty users immediate provisioning of their issued card to one supported phone wallet will increase Month 3 card retention by at least 10 percentage points, from a synthetic planning baseline of 69%, by enabling in-store use before the physical card arrives. We will protect partner-checkout Riverty spend per randomised participant, with a proposed tolerance of no more than a 3% relative reduction versus control.

## Mechanism metrics

- Wallet-provisioning completion rate.
- First Riverty Card purchase within 14 days.
- At least one in-store Riverty Card purchase.
- Time from approval to first card purchase.

These metrics diagnose the mechanism; they are not substitutes for the primary decision metric.

## Decision rules

### Ship

Ship the targeted rollout if Month 3 card retention improves by at least 10 percentage points at p < 0.05, the partner-checkout guardrail remains within the proposed 3% boundary, and no critical Risk or Compliance issue is identified.

### Iterate

Iterate if the primary direction is positive but below the MDE, provisioning or early in-store use is weak, or the guardrail result is inconclusive. Diagnose the funnel before expanding reach.

### Kill

Do not ship the feature if the primary metric shows no improvement or moves negatively at the full readout, or if evidence shows that immediate provisioning does not create sustained usage.

### Pause

Pause enrolment into the variant if partner-checkout spend falls more than 3% below control in two consecutive monitoring periods or if a material Risk, fraud, Compliance, or provisioning incident occurs. Investigate before resuming. Safety and data-quality monitoring may continue before the primary readout; efficacy results remain blinded.
