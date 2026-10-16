# GTM and Success Dashboard

## Goal and audience

- **Feature:** Phone-wallet provisioning for eligible Riverty cardholders
- **Goal:** Engagement — deepen repeat card usage beyond partner checkout
- **Audience:** Eligible, activated, loyal frequent Riverty cardholders in Germany with a compatible device and supported wallet
- **Persona:** Lena informs the experience; she is not the targeting rule

## Launch tier

- **S — controlled beta:** friends-and-family experiment with no broad promotion
- **M — targeted rollout:** only after the experiment passes the primary metric and guardrail

## Channels for the M-tier rollout

1. **Owned — in-app card banner:** prompts eligible users to start provisioning.
2. **Owned — targeted email:** explains value, eligibility, and setup.
3. **Owned — push notification:** deep-links eligible users into the flow.

During the experiment, promotional communication is held constant to protect attribution.

## Enablement and assets

- Setup guide and in-app walkthrough
- Eligibility and known-error guidance
- FAQ, Customer Service macros, and escalation path
- Experiment and rollout dashboard
- Risk, Compliance, scheme, and wallet-provider readiness checklist

## Ownership and budget

- **Experiment and launch:** Riverty Card Product Manager
- **Technical readiness:** Engineering Lead
- **Customer communication:** Lifecycle Marketing Manager
- **Support readiness:** Customer Operations Lead
- **Measurement:** Product Data Analyst
- **Approval:** named Risk and Compliance approvers

No paid media. Potential incremental costs are wallet-provider or scheme fees and dedicated Customer Service training capacity. Existing marketing, analytics, and support tools are used.

## Timeline

1. **Beta:** confirm dependencies, instrument events, and run the controlled experiment.
2. **Decision:** apply ship / iterate / kill / pause rules after the fixed readout.
3. **Targeted rollout:** activate owned channels only if the primary metric and guardrail pass.
4. **Post-launch:** monitor provisioning, in-store usage, M3 retention, and partner-checkout spend.

## Success dashboard

| Metric | Role | Decision use |
|---|---|---|
| M3 card retention | Primary outcome | Scale only if lift is at least the proposed +10pp at p < 0.05 |
| Provisioning completion | Mechanism | Diagnose setup friction |
| At least one in-store wallet transaction | Mechanism | Confirm that provisioning creates relevant use |
| Partner-checkout spend per randomised participant | Guardrail | Pause/stop if the proposed 3% boundary is breached |

## Bad signals

- High flow starts but low provisioning completion: setup or provider friction.
- High provisioning but low in-store wallet usage: weak customer value.
- Higher card usage but partner-checkout spend more than 3% below control: merchant-channel cannibalisation.

## Likely decision

Iterate if setup or in-store use is weak. Scale only if M3 retention improves by at least 10 percentage points and the proposed partner-checkout guardrail holds.
