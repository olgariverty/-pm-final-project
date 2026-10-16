# A/B Experiment Brief

## Experiment

**Phone-wallet provisioning for eligible, activated Riverty cardholders.**

| Parameter | Decision | Status |
|---|---|---|
| Persona | Lena, 32, Cologne; design context, not a targeting rule | Case input |
| Cohort | Eligible, activated, loyal frequent cardholders with a compatible device | Eligibility to define before launch |
| Primary metric | M3 card retention: at least one Riverty Card purchase in the third 30-day period after randomisation | Defined |
| In-store diagnostic | At least one in-store card transaction by any method, measured in both arms | Card form to confirm before launch |
| Baseline | 69% | Synthetic planning benchmark; validate comparability |
| MDE | +10 percentage points absolute | Proposed |
| Sample | 301 per arm | Proposed calculator estimate at 80% power / 5% significance |
| Split | 50/50 | Proposed |
| Duration | 3 months per participant | Proposed |
| Guardrail | Partner-checkout spend per randomised participant | Defined |
| Guardrail boundary | No more than 3% relative reduction vs control | Proposed from synthetic signal |

## Control and variant

**Control A:** Eligible, activated pilot cardholders use the current Riverty Card experience without phone-wallet provisioning during the experiment.

**Variant B:** The same cardholders and card experience, plus access to one supported phone-wallet provisioning flow for in-store payments, with success feedback and an actionable recovery path.

**Held constant:** Card terms, credit limits, repayment, eligibility, card issuing, existing card functionality, merchant acceptance, support routing, app version, and metric definitions. The only experiment difference is access to phone-wallet provisioning.

## Hypothesis

> We believe that phone-wallet provisioning for eligible, activated, loyal frequent Riverty cardholders will increase repeat card usage beyond partner checkout, measured by a proposed 10 percentage point absolute lift in M3 card retention within three months per participant. We will protect partner-checkout Riverty spend per randomised participant.

## Decision rules

- **Ship:** M3 card retention improves by at least 10 percentage points at p < 0.05 and partner-checkout spend declines by no more than 3% relative to control.
- **Iterate:** Direction is positive but below the MDE, or provisioning take-up shows correctable setup friction.
- **Kill:** The primary metric is clearly negative at the final read, or the guardrail is materially breached.
- **Pause:** Partner-checkout spend is more than 3% below control in two consecutive weekly safety reads **[minimum data or confidence rule TBD]**, or a material Risk/Compliance incident occurs. A material incident is a confirmed regulatory, customer-harm, fraud, or operational event that Risk/Compliance classifies as requiring a pause. The Experiment Owner pauses enrolment with Risk and Compliance.
- **Inconclusive:** The confidence interval includes no effect at the planned sample. This is not evidence of equivalence.

## Readout

The final efficacy read occurs after the last enrolled participant completes days 61–90 plus the agreed settlement lag. No early efficacy stopping. Operational and guardrail monitoring may continue throughout.

## Pre-launch gates

Confirm wallet/provider support, card form, eligibility, activation and days 61–90 definitions, baseline comparability, sample feasibility, Risk/Compliance approval, and Customer Service readiness.
