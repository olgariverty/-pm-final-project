# GTM and Success Dashboard

## Goal and audience

- **Feature:** Phone-wallet provisioning for eligible Riverty cardholders
- **Goal:** Engagement — deepen repeat card usage beyond partner checkout
- **Audience:** Eligible, activated, loyal frequent Riverty cardholders in Germany with compatible devices and a supported wallet
- **Persona:** Lena informs the experience; she is not the targeting rule

## Launch tier

- **S — controlled beta:** friends-and-family experiment with no broad promotion
- **M — targeted rollout:** only after the experiment passes the primary metric and guardrail

## Beta communication

In-product feature exposure only. Control users remain uncommunicated to protect attribution.

## Channels for the M-tier rollout (after the experiment passes)

1. **Owned — in-app card banner:** prompts eligible users to start provisioning.
2. **Owned — targeted email:** explains value, eligibility, and setup.
3. **Owned — push notification:** deep-links eligible users into the flow.

## Enablement and assets

- Setup guide and in-app walkthrough
- Eligibility and known-error guidance
- FAQ, Customer Service macros, and escalation path
- Experiment and rollout dashboard
- Risk, Compliance, scheme, and wallet-provider readiness checklist

## Ownership and budget

- **Launch:** Card PM
- **Technical readiness:** Engineering Lead
- **Customer communication:** Lifecycle Marketing
- **Support readiness:** Operations Lead (Customer Service)
- **Measurement:** Data Analyst
- **Approval:** named Risk/Compliance approvers

**Decision owners:** Card PM owns launch. Card PM and Risk/Compliance own pauses. Data and Finance approve thresholds. Data and Risk set the minimum-data rule.

**Proposed owners, to be confirmed before beta:** Card PM owns card-form confirmation. Finance owns gross/net and returns treatment. Engineering owns wallet and scheme support. Card Operations owns application, issuing, and activation. Credit Risk owns credit design. Risk/Compliance owns the gate. Customer Service owns training.

**Budget:** No paid media. Potential incremental costs are wallet-provider or scheme fees and dedicated Customer Service training capacity. Existing marketing, analytics, and support tools are used.

**Gaps:** Customer Service training, wallet certification, dashboard readiness.

## Timeline

1. **Beta:** confirm dependencies, instrument events, and run the controlled experiment. The pause rule applies throughout the test.
2. **Decision:** after every participant completes days 61–90, apply the ship / iterate / inconclusive / kill rules.
3. **Targeted rollout:** activate owned channels only if the primary metric and guardrail pass.
4. **Post-launch:** monitor provisioning, in-store usage, M3 retention, and partner-checkout spend.

## Success dashboard

| Metric | Role | Decision use |
|---|---|---|
| M3 card retention (days 61–90 after randomisation) | Primary outcome | Scale only if the approved lift threshold is reached at p < 0.05 (current proposal: +10pp MDE) |
| Provisioning completion | Mechanism | Diagnose setup friction |
| At least one in-store card transaction by any method, both arms | Diagnostic | Confirm in-store use differs between arms |
| At least one in-store wallet transaction (variant arm) | Mechanism | Confirm that provisioning creates relevant use |
| Partner-checkout spend per randomised participant (cumulative days 1–90) | Guardrail | Ship test, and pause rule if cumulative spend is more than 3% below control in two weekly reads after the minimum-data rule is set (proposed boundary) |

## Bad signals

- High flow starts but low provisioning completion: setup or provider friction.
- High provisioning but low in-store usage: weak customer value.
- Higher card usage but partner-checkout spend beyond the approved boundary: merchant-channel cannibalisation.

## Likely decision

Iterate if setup or in-store use is weak. Scale only if M3 card retention reaches the approved lift threshold and the partner-checkout guardrail holds.
