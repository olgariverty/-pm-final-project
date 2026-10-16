# Product School · Product Management Certification · Final Project

## Riverty Wallet-Ready Card

**Pitch:** Test whether phone-wallet access creates durable Riverty Card usage beyond partner checkout.

**Group 5 · Cohort 1**
**Repo:** https://github.com/olgariverty/-pm-final-project
**Prototype:** https://req-pilot.lovable.app/

## Slide 5 · Strategy

**Headline:** Riverty disappears when partner checkout does.

- **Persona:** Lena, 32, Cologne; frequent BNPL user who shops mainly on her phone.
- **Friction:** When Riverty is not offered, she falls back to Klarna, PayPal, or a bank card.
- **Opportunity:** Add one supported phone-wallet route for using an issued Riverty Card in store.
- **Hypothesis:** Wallet access will increase repeat card use without materially reducing partner-checkout spend.

## Slide 6 · Research

Lena's relevant moment of misery is lack of Riverty acceptance beyond partner checkout. Phone-wallet provisioning addresses that acceptance gap. Her pay-after-deciding preference remains a separate, untested need.

Journey: activate → provision → use in store → repeat in Month 3.

## Slide 7 · Blueprint

**Now:** card readiness, one supported-wallet flow, experiment instrumentation.
**Next:** second wallet if device mix warrants it, guided onboarding, activity view.
**Later:** separately validate pay-after-deciding and rewards.

Must-haves: eligibility, secure provisioning, success state, recoverable failure, event tracking. Prototype is simulated and processes no real payments.

## Slide 8 · Validation

- **Control:** current activated card experience without phone-wallet provisioning during the test.
- **Variant:** same card experience plus phone-wallet provisioning.
- **Primary:** M3 card retention among all randomised activated cardholders.
- **Guardrail:** partner-checkout spend per randomised participant; proposed boundary no more than -3% vs control.
- **Design:** 50/50, proposed 301/arm, 80% power, p < 0.05, three months per participant.

Ship at ≥ +10pp and guardrail pass. Iterate below MDE with positive direction. Kill if clearly negative. Pause if the guardrail breaches for two consecutive safety reads or a material Risk/Compliance incident occurs.

## Slide 9 · Launch

**Goal:** Engagement.
**Tier:** S beta → M targeted rollout after evidence.
**Audience:** Eligible, activated, loyal frequent German cardholders with compatible devices.
**Channels after pass:** in-app card banner, targeted email, push notification.
**Dashboard:** provisioning completion, in-store wallet usage, M3 retention, partner-checkout spend.

## Slide 10 · Decision requested

**Decision requested:** Approve a controlled beta subject to wallet-provider, Risk, and Compliance readiness. Scale only if M3 retention improves by the agreed threshold and partner-checkout spend stays within the agreed boundary.

**Before launch:** Confirm provider and scheme support; validate cohort, baseline, and sample feasibility; secure Risk, Compliance, and Support readiness.
