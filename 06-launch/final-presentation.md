# Product School · Product Management Certification · Final Project

## Riverty Wallet-Ready Card

**Pitch:** Test whether phone-wallet access creates durable card usage beyond partner checkout.
**Controlled German pilot · merchant-first guardrail**

**Group 5 · Cohort 1**
**Repo:** https://github.com/olgariverty/-pm-final-project
**Prototype:** https://req-pilot.lovable.app/ (simulated usability flow; no real payments)

## Slide 5 · Strategy

**Headline:** Riverty disappears when partner checkout does.

- **Problem hook:** Lena uses BNPL on most non-trivial purchases but takes whichever provider appears at checkout. She knows Riverty, but rarely seeks it out, so Riverty only reaches her where partner merchants show it. A card could give her a reason to choose Riverty beyond partner checkout.
- **Moment of misery:** Where a partner merchant does not offer Riverty, Lena falls back to Klarna, PayPal, or a bank card.
- **Value proposition:** For Lena, a Riverty card could give her a reason to use Riverty beyond partner checkout. **Why now:** Riverty remains dependent on merchant checkout while Klarna and PayPal remain available.
- **Hypothesis informed by synthetic planning signals:** We believe wallet access can increase repeat card use while protecting partner checkout.
- **Synthetic signals:** Loyal-heavy users: 6.31% eligible-to-activated conversion and 69% M3 retention; Lena-like users: 2.19% eligible-to-activated conversion and 49% M3 retention; partner-checkout spend signal: -3%.
- **Market-entry choice:** Lena remains the case persona with no Riverty preference; the pilot targets loyal-heavy cardholders who share her acceptance friction.

## Slide 6 · Research

**Headline:** Lena's relevant friction is acceptance beyond partner checkout.

- **Persona (case):** Lena, 32, Cologne. Frequent BNPL user who shops mainly on her phone.
- **Goal (case):** Pay only after deciding to keep an item.
- **Moment of misery (case):** Where a partner merchant does not offer Riverty, Lena falls back to Klarna, PayPal, or a bank card.
- **Workaround (case):** Klarna, PayPal, or an existing debit or credit card.
- **Journey map:** activate (enter eligible cohort) → provision (add card to wallet) → use (pay in store; the moment of misery) → repeat (use card during days 61–90).
- **Legend:** Case = assigned-case input; Synthetic = directional planning signal; Proposed = decision to validate.
- **Scope boundary:** wallet provisioning addresses acceptance, not payment timing. Pay-after-deciding remains a separate, untested need.

## Slide 7 · Blueprint

**Headline:** Build only what the experiment needs.

**Now:** external prerequisites (application, credit design, issuing and activation); one supported-wallet flow; experiment instrumentation.
**Next:** second wallet if device mix warrants it; guided onboarding; card activity view.
**Later / separate bets:** pay-after-deciding; rewards; broad rollout.

- **PRD must-haves:** eligibility, secure provisioning, success state, actionable recovery, and event tracking.
- **Scope protection:** credit terms stay identical between arms. No platform promise, immediate-issuance claim, multiple wallets, or promotional nudges during the test.
- **Planning boundary:** Now covers prerequisites plus the test build, not a single-sprint commitment.
- **Prototype:** validates flow usability only, not real payments, retention, or business impact.

## Slide 8 · Validation

**Headline:** Will wallet access create durable usage without cannibalising partner checkout?

- **Control A:** no phone-wallet provisioning during the test.
- **Variant B:** same experience plus one supported-wallet flow.
- **Primary:** M3 card retention: randomised activated cardholders with at least one card purchase on days 61–90 after randomisation.
- **In-store diagnostic:** at least one in-store card transaction by any method, in both arms.
- **Guardrail:** cumulative partner-checkout spend per randomised participant, days 1–90; zeros included; proposed boundary no more than 3% below control. Days 61–90 are a secondary view.
- **Baseline:** 69% (synthetic); M3 baseline comparability unconfirmed.
- **Proposed design:** MDE +10 percentage points; 301 per arm; 3 months per participant; 50/50 split; 80% power; p < 0.05; approximately 602 activated participants; directional if unattainable.
- **Decision rules:** Ship: approved lift, p < .05, guardrail passes. Iterate: positive, below MDE. Inconclusive: CI includes zero; extend or redesign. Kill: clearly negative.
- **Pause:** cumulative spend since randomisation is more than 3% below control in two weekly reads after the minimum-data rule, or a Risk/Compliance-defined incident.
- **Read:** after every participant completes days 61–90.

## Slide 9 · Launch

**Headline:** S beta first. M rollout only after evidence.

- **Goal:** Engagement. Deepen repeat card use beyond partner checkout.
- **Tier:** S beta → M targeted rollout only after evidence.
- **Audience:** Eligible, activated, loyal frequent German cardholders with compatible devices.
- **Channels after pass:** in-app, email, push.
- **Metrics:** provisioning completion (diagnoses setup friction); M3 card retention (governs the scale decision). In-store card use: see Validation.
- **Beta communication:** in-product feature exposure only; control users remain uncommunicated to protect attribution.
- **Owners:** Card PM, Engineering Lead, Lifecycle Marketing, Operations Lead (Customer Service), Data Analyst.
- **Gaps:** CS training, wallet certification, dashboard readiness.
- **Bad signal:** card usage rises while partner-checkout spend falls beyond the approved boundary.

## Slide 10 · Decision requested

**Headline:** Approve the controlled beta.

**Decision requested today:** Approve the controlled beta subject to feasibility review, which returns to this forum. Scale only if M3 retention reaches the approved lift threshold and partner-checkout spend stays within the approved boundary.

- **Beta scope:** approximately 602 activated participants. Card PM and Risk freeze eligibility before enrolment; directional if unattainable.
- **Timing:** three months per participant. Card PM sets dates and the decision forum after feasibility review.
- **Decision owners:** Card PM owns launch. Card PM and Risk/Compliance own pauses. Data and Finance approve thresholds. Data and Risk set the minimum-data rule.
- **Proposed owners, to be confirmed before beta:** Card PM: card form. Finance: gross/net and returns. Engineering: wallet and scheme. Card Operations: application, issuing, activation. Credit Risk: credit design. Risk/Compliance: gate. Customer Service: training.
- **Protection:** merchants get a guardrail and stop rule. Risk/Compliance controls the gate and defines incidents. Support trains before exposure.

## Thank you · Submit

Ready for the decision.

**Group 5 · Cohort 1**
**Repo:** https://github.com/olgariverty/-pm-final-project
**Prototype:** https://req-pilot.lovable.app/
