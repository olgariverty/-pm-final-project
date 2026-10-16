# Hypothesis and Success Metrics

## Evidence reconciliation

### Qualitative evidence

Lena uses whichever payment option appears at checkout and rarely seeks out Riverty. Riverty is unavailable where partner merchants do not offer it, so she falls back to Klarna, PayPal, or an existing bank card.

### Quantitative planning inputs

| Input | Value | Status |
|---|---:|---|
| M3 card retention | 69% | Synthetic planning benchmark for an activated loyal-heavy cohort; comparability must be validated |
| Eligible-to-activated conversion | 6.31% | Synthetic directional signal for loyal heavy users |
| Partner-checkout spend signal | -3% | Synthetic card-vs-non-card signal; used only to propose a guardrail |
| MDE | +10 percentage points | Proposed decision threshold |
| Sample per arm | 301 | Calculator estimate at 80% power and 5% significance, conditional on the 69% baseline and +10pp MDE |

## Hypothesis

> We believe that enabling eligible, activated, loyal frequent Riverty cardholders to add their issued card to one supported phone wallet will increase repeat card usage beyond partner checkout. We will measure this through M3 card retention and protect partner-checkout Riverty spend per randomised participant.

## Metric definitions

### Primary success metric

**M3 card retention:** percentage of all randomised activated pilot cardholders who make at least one Riverty Card purchase in Month 3. Month 3 is the third 30-day period after randomisation. Analysis is intention-to-treat.

### Mechanism metrics

- Wallet-provisioning completion rate among the variant cohort
- Share of randomised variant participants with at least one in-store wallet transaction
- Time from randomisation to first Riverty Card transaction

These explain why the primary metric moved; they do not replace the decision metric.

### Guardrail

**Partner-checkout Riverty spend per randomised participant:** net-of-returns partner-checkout spend in the same observation window, including participants with zero spend.

Proposed boundary: the variant must not reduce this metric by more than 3% relative to control. The boundary is a decision proposal informed by a synthetic signal, not an approved business threshold.

## Decision window

Three months per participant. The final read occurs when the last enrolled participant completes the Month 3 window, plus the agreed settlement lag. Data-quality checks are allowed; efficacy results are not reviewed early.
