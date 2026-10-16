# Roadmap, PRD and Prototype

## Strategic anchors

- **Design persona:** Lena, a frequent mobile BNPL user who cannot use Riverty beyond partner checkout.
- **Experiment cohort:** Eligible, activated, loyal frequent Riverty cardholders with compatible devices.
- **Primary metric:** M3 card retention.
- **Guardrail:** Partner-checkout Riverty spend per randomised participant.

## Now — make the experiment possible

1. **Card readiness:** validate application, approval, issuing, credit-limit, repayment, and activation dependencies.
2. **Phone-wallet provisioning:** build one supported-wallet flow with success and recoverable failure states.
3. **Experiment instrumentation:** randomisation, wallet events, card transactions, Month 3 retention, and partner-checkout guardrail.

## Next — improve after evidence

- Second wallet, only if device mix warrants it
- Guided onboarding and setup content after the experiment
- In-app card activity view

## Later — separate hypotheses

- Pay-after-deciding, validated against repayment mechanics
- Rewards or partner propositions
- Broader market rollout

## Cut from the beta

- Partner promotions
- Multiple wallets
- Promotional nudges that would contaminate attribution
- Unvalidated loyalty or pay-after-deciding promises

## PRD highlights

The feature is one attributable change: access to phone-wallet provisioning. The prototype covers setup, progress, success, failure, retry, and support. It is platform-agnostic until device mix and provider readiness are confirmed.

## Prototype

https://req-pilot.lovable.app/

The prototype is a simulated usability flow; no real card is issued and no payment is processed.
