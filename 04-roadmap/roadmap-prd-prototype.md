# Roadmap, PRD and Prototype

## Strategic anchors

- **Design persona:** Lena, a frequent mobile BNPL user who cannot use Riverty beyond partner checkout.
- **Experiment cohort:** Eligible, activated, loyal frequent Riverty cardholders with compatible devices.
- **Primary metric:** M3 card retention (days 61–90 after randomisation).
- **Guardrail:** Partner-checkout Riverty spend per randomised participant.

## Now — make the experiment possible

Now covers prerequisites plus the test build, not a single-sprint commitment.

1. **Card readiness (external prerequisites):** application, credit design, issuing, and activation.
2. **Phone-wallet provisioning:** build one supported-wallet flow with success and recoverable failure states.
3. **Experiment instrumentation:** randomisation, wallet events, card transactions, M3 retention, and the partner-checkout guardrail.

## Next — improve after evidence

- Second wallet, only if device mix warrants it
- Guided onboarding and setup content after the experiment
- Card activity view

## Later — separate hypotheses

- Pay-after-deciding, validated against repayment mechanics
- Rewards (a separate bet, excluded from the beta)
- Broader market rollout

## Cut from the beta

- Partner promotions
- Multiple wallets during the beta
- Promotional nudges that would contaminate attribution
- Unvalidated loyalty or pay-after-deciding promises

## PRD highlights

The feature is one attributable change: access to phone-wallet provisioning. The prototype covers setup, success, failure, retry, and support. It is platform-agnostic until device mix and provider readiness are confirmed.

## Prototype

https://req-pilot.lovable.app/

The prototype is a simulated usability flow; no real card is issued and no payment is processed. It validates flow usability only, not real payments, retention, or business impact.
