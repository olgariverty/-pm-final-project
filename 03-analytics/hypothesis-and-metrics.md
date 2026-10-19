# Hypothesis and Success Metrics

## Evidence reconciliation

### Qualitative evidence

Lena uses whichever payment option appears at checkout and rarely seeks out Riverty. Moment of misery: where a partner merchant does not offer Riverty, Lena falls back to Klarna, PayPal, or a bank card.

### Quantitative planning inputs

| Input | Value | Status |
|---|---:|---|
| M3 card retention, loyal-heavy users | 69% | Synthetic planning benchmark for an activated loyal-heavy cohort; comparability unconfirmed |
| Eligible-to-activated conversion, loyal-heavy users | 6.31% | Synthetic directional signal |
| M3 card retention, Lena-like users | 49% | Synthetic directional signal |
| Eligible-to-activated conversion, Lena-like users | 2.19% | Synthetic directional signal |
| Partner-checkout spend signal | -3% | Synthetic card-vs-matched-non-card signal; used only to propose a guardrail |
| MDE | +10 percentage points | Proposed decision threshold |
| Sample per arm | 301 | Calculator estimate at 80% power and 5% significance, conditional on the 69% baseline and the +10pp MDE; approximately 602 activated participants in total |

### Data lineage

The synthetic figures above come from an initial model-scale simulation whose eligible-user base was derived arithmetically from the case's Year 1 projection. That base is not a case fact and is not presented as observed Riverty data. A later, smaller friends-and-family-scale synthetic dataset was built separately for illustration and is not the source of these figures. None of the synthetic figures are observed Riverty performance.

## Hypothesis

> We believe that enabling eligible, activated, loyal frequent Riverty cardholders to add their issued card to one supported phone wallet will increase repeat card usage beyond partner checkout. We will measure this through M3 card retention and protect partner-checkout Riverty spend per randomised participant.

## Metric definitions

### Primary success metric

**M3 card retention:** percentage of randomised activated pilot cardholders who make at least one Riverty Card purchase on days 61–90 after randomisation (the third 30-day period). Analysis is intention-to-treat.

### Mechanism and diagnostic metrics

- Wallet-provisioning completion rate among the variant cohort
- Share of randomised variant participants with at least one in-store wallet transaction (variant arm only)
- At least one in-store card transaction by any method, measured in both arms (diagnostic; card form to confirm)
- Time from randomisation to first Riverty Card transaction

These explain why the primary metric moved; they do not replace the decision metric.

### Guardrail

**Partner-checkout Riverty spend per randomised participant:** cumulative over days 1–90 after randomisation, including participants with zero spend. Days 61–90 are a secondary view. Gross versus net-of-returns treatment is to be confirmed by Finance.

Proposed boundary: the variant must not be more than 3% below control. The boundary is a decision proposal informed by a synthetic signal, not an approved business threshold. Data and Finance approve thresholds and the statistical rule.

## Decision window

Three months per participant (proposed). The final read occurs after every participant completes days 61–90. Data-quality and operational checks are allowed; efficacy results are not reviewed early.
