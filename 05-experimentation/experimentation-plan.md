# A/B Experiment Brief

## Experiment

**Phone-wallet provisioning for eligible, activated Riverty cardholders.**

| Parameter | Decision | Status |
|---|---|---|
| Persona | Lena, 32, Cologne; design context, not a targeting rule | Case input |
| Cohort | Eligible, activated, loyal frequent cardholders with a compatible device | Card PM and Risk freeze eligibility before enrolment |
| Primary metric | M3 card retention: randomised activated cardholders with at least one Riverty Card purchase on days 61–90 after randomisation (the third 30-day period) | Defined |
| In-store diagnostic | At least one in-store card transaction by any method, measured in both arms | Card form to confirm before launch |
| Baseline | 69% | Synthetic planning benchmark; comparability unconfirmed |
| MDE | +10 percentage points absolute | Proposed |
| Sample | 301 per arm; approximately 602 activated participants | Proposed calculator estimate at 80% power / 5% significance; directional if unattainable |
| Split | 50/50 | Proposed |
| Duration | 3 months per participant | Proposed |
| Guardrail | Cumulative partner-checkout spend per randomised participant, days 1–90, zeros included; days 61–90 are a secondary view | Defined; gross/net and returns treatment to be confirmed by Finance |
| Guardrail boundary | No more than 3% below control | Proposed from a synthetic signal |

## Control and variant

**Control A:** Eligible, activated pilot cardholders use the current Riverty Card experience without phone-wallet provisioning during the experiment.

**Variant B:** The same cardholders and card experience, plus access to one supported phone-wallet provisioning flow for in-store payments, with success feedback and an actionable recovery path.

**Held constant:** Card terms, credit limits, repayment, eligibility, card issuing, existing card functionality, merchant acceptance, support routing, app version, and metric definitions. Beta communication is in-product feature exposure only; control users remain uncommunicated. The only experiment difference is access to phone-wallet provisioning.

## Hypothesis

> We believe that phone-wallet provisioning for eligible, activated, loyal frequent Riverty cardholders will increase repeat card usage beyond partner checkout, measured by M3 card retention (the approved lift threshold; current proposal: +10 percentage points). We will protect partner-checkout Riverty spend per randomised participant.

## Decision rules

- **Ship:** M3 card retention reaches the approved lift threshold at p < 0.05 and the guardrail passes. A guardrail failure blocks shipping. The statistical rule for the guardrail (point estimate or confidence bound) is set by Data and Finance before enrolment.
- **Iterate:** Direction is positive but below the MDE.
- **Inconclusive:** The confidence interval includes zero; extend or redesign. This is not evidence of equivalence.
- **Kill:** The primary metric is clearly negative.
- **Pause enrolment:** Cumulative partner-checkout spend since randomisation is more than 3% below control in two weekly reads after the minimum-data rule is set by Data and Risk, or a material incident occurs, as defined by Risk/Compliance. Card PM and Risk/Compliance own pauses.

## Readout

The final efficacy read occurs after every participant completes days 61–90. No early efficacy stopping. Operational and guardrail monitoring continue throughout.

## Decision owners

Card PM owns launch. Card PM and Risk/Compliance own pauses. Data and Finance approve thresholds. Data and Risk set the minimum-data rule. Proposed owners are listed in `gtm-and-dashboard.md`.

## Pre-launch gates

Confirm wallet/provider support, card form, eligibility (frozen by Card PM and Risk), activation and days 61–90 definitions, baseline comparability, sample feasibility, Risk/Compliance approval, and Customer Service readiness.
