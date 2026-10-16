# Roadmap, PRD & Prototype (Module 4)

## Strategic anchors

- **Design persona:** Nadine, the fragmentation-weary shopper.
- **Experiment cohort:** Newly approved frequent Riverty users with a compatible device.
- **Primary metric:** Month 3 card retention.
- **Moment of misery:** Riverty is unavailable at a non-partner checkout or in store, so the user switches payment method.
- **Guardrail:** Partner-checkout spend per randomised participant must not decline by more than the proposed 3% relative boundary versus control.

## Roadmap

### Now — prove the core hypothesis

1. **Approval and issuing readiness:** Confirm an approved card is active and eligible for wallet tokenisation.
2. **Wallet-Ready Instant Card:** Offer provisioning to one supported phone wallet immediately after approval.
3. **Experiment instrumentation:** Measure provisioning, first use, in-store use, Month 3 retention, and partner-checkout spend.

### Next — improve adoption after the readout

- First-use guidance and a reminder for users selecting "Not now."
- A second phone wallet if cohort device mix and technical readiness justify it.
- Card activity and payment overview improvements.

### Later

- Split-it-later or pay-after-deciding propositions, subject to separate customer, Risk, and Compliance validation.
- Multi-device token management.
- Rewards or partner-funded benefits only if evidence supports incremental value.

### Cut from the pilot

- Cashback, partner promotions, creator cards, default-card nudges during the experiment, additional credit propositions, and markets outside Germany.

## PRD highlights — Wallet-Ready Instant Card

### Core experience

An approved cardholder can add the issued Riverty Card to one supported phone wallet immediately after approval, before the physical card arrives.

### Must-haves

1. A valid issued card and an eligible, compatible device.
2. Secure wallet provisioning with required authentication and tokenisation.
3. A clear provisioning success state.
4. A clear failure reason, retry option, and support path.
5. Ability to make an in-store payment at a compatible terminal after successful provisioning.
6. Card or wallet-token suspension for safety.
7. Event logging for provisioning, first use, channel, Month 3 retention, and guardrail reporting.

### Isolation and scope protection

The only experiment difference is when wallet provisioning becomes available: immediately after approval versus after physical-card arrival. Card terms, credit policy, issuing, repayment, fraud controls, support, and measurement remain unchanged.

Out of scope: a second wallet, nudges or promotions during the test, instalments, rewards, pricing changes, and expanded wallet functionality.

## Prototype

The prototype demonstrates approval, wallet provisioning, success, failure, retry, and support states. It tests flow comprehension and usability only; it does not validate real tokenisation, payment execution, Month 3 retention, or business impact.

The current prototype illustrates a wallet implementation. The first production platform must be selected using cohort device mix, technical readiness, provider approval, Compliance requirements, and integration cost.

**Prototype:** https://req-pilot.lovable.app/

The current platform-agnostic prototype is the retained base. A later iteration will add the approval entry point and explicitly show the timing difference tested by the experiment.

## What the prototype revealed

- Retry behaviour and progress preservation needed an explicit rule.
- The happy path is two user actions because success appears automatically.
- Authentication failure, offline handling, and lockout scope require separate definitions.
- Several technical and Risk requirements cannot be validated in a visual prototype.
