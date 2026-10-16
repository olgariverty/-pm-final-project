# Product School · Product Management Certification · Final Project

## Riverty Wallet-Ready Card

**Pitch:** Test whether phone-wallet access creates durable Riverty Card usage beyond partner checkout.

**Group 5 · Cohort 1**
**Repo:** https://github.com/olgariverty/-pm-final-project
**Prototype:** https://req-pilot.lovable.app/

## Slide 5 · Strategy

**Headline:** Riverty disappears when partner checkout does.

- **Persona:** Lena, 32, Cologne; frequent BNPL user who shops mainly on her phone.
- **Friction:** Where merchants do not offer Riverty, Lena uses Klarna, PayPal, or a bank card.
- **Opportunity:** One supported phone wallet could create an in-store route for the issued Riverty Card.
- **Hypothesis:** We believe wallet access can increase repeat card use while protecting partner checkout.
- **Hypothesis informed by synthetic planning signals:** Loyal-heavy users: 6.31% eligible-to-activated conversion and 69% M3 retention; Lena-like users: 2.19% eligible-to-activated conversion and 49% M3 retention; partner-checkout spend signal: -3%.
- **Market-entry choice:** Lena remains the case persona with no Riverty preference; the pilot targets loyal-heavy cardholders who share her acceptance friction.
- **Cost of waiting:** Riverty remains dependent on merchant checkout while Klarna and PayPal remain available.

## Slide 6 · Research

Lena, 32, Cologne, is a frequent mobile BNPL user. Her goal is to pay only after deciding to keep an item. Riverty reaches her only where partner merchants offer it, so she falls back to Klarna, PayPal, or a bank card. Phone-wallet provisioning addresses the acceptance gap; pay-after-deciding remains a separate, untested need.

Journey: activate → provision → use in store → repeat during days 61–90.

## Slide 7 · Blueprint

**Now:** external prerequisites (application, credit design, issuing and activation); one supported-wallet flow; experiment instrumentation. Now covers prerequisites plus the test build, not a single-sprint commitment.
**Next:** second wallet if device mix warrants it, guided onboarding, activity view.
**Later:** separately validate pay-after-deciding and rewards.

Must-haves: eligibility, secure provisioning, success state, recoverable failure, event tracking. Credit terms stay identical between arms. The prototype validates flow usability only—not real payments, retention, or business impact.

## Slide 8 · Validation

- **Control:** current activated card experience without phone-wallet provisioning during the test.
- **Variant:** same card experience plus phone-wallet provisioning.
- **Primary:** M3 card retention: randomised activated cardholders with at least one card purchase during days 61–90 after randomisation.
- **In-store diagnostic:** at least one in-store card transaction by any method, measured in both arms.
- **Guardrail:** cumulative partner-checkout spend per randomised participant during days 1–90; zeros included; proposed boundary no more than -3% vs control. Days 61–90 are a secondary view.
- **Baseline caveat:** the 69% M3 baseline is synthetic and cohort comparability remains unconfirmed.
- **Design:** Proposed 50/50 split, 301/arm, 80% power, p < 0.05, three months per participant. Final read after every participant completes days 61–90.

Ship if the lift threshold is reached at p < 0.05 and the guardrail passes. Iterate below MDE with positive direction. If the confidence interval includes zero, classify the result as inconclusive and extend or redesign. Kill only if clearly negative. Pause enrolment when cumulative partner-checkout spend since randomisation is more than 3% below control in two weekly reads after the minimum-data rule is set, or after a material incident defined by Risk/Compliance.

Proposed design: 50/50, 80% power, approximately 602 activated participants; if unattainable, treat the beta as directional.

## Slide 9 · Launch

**Goal:** Engagement.
**Tier:** S beta → M targeted rollout after evidence.
**Audience:** Eligible, activated, loyal frequent German cardholders with compatible devices.
**Channels after pass:** in-app card banner, targeted email, push notification.
**Dashboard:** provisioning completion, M3 retention, partner-checkout spend.
**In-store card use:** see Validation.
**Beta communication:** in-product feature exposure only; control users remain uncommunicated.
**Owners:** Card PM, Engineering Lead, Lifecycle Marketing, Operations Lead, Data Analyst.
**Gaps:** Customer Service training, wallet certification, dashboard readiness.

## Slide 10 · Decision requested

**Decision requested today:** Approve the controlled beta subject to feasibility review, which returns to this forum. Scale only if M3 retention reaches the approved lift threshold and partner-checkout spend stays within the approved boundary.

**Beta scope:** approximately 602 activated participants. Card PM and Risk freeze eligibility before enrolment; treat the beta as directional if the sample is unattainable.
**Timing:** three months per participant. Card PM sets dates and the decision forum after feasibility review.
**Decision owners:** Card PM owns launch. Card PM and Risk/Compliance own pauses. Data and Finance approve thresholds. Data and Risk set the minimum-data rule.
**Proposed owners, to be confirmed before beta:** Card PM owns card-form confirmation. Finance owns gross/net and returns treatment. Engineering owns wallet and scheme support. Card Operations owns application, issuing, and activation. Credit Risk owns credit design. Risk/Compliance owns the gate. Customer Service owns training.

**Stakeholder protection:** Merchants get a guardrail and stop rule. Risk/Compliance controls the gate and defines incidents. Support trains before exposure.

## Thank you · Submit

**Group 5 · Cohort 1**

**Repo:** https://github.com/olgariverty/-pm-final-project

**Prototype:** https://req-pilot.lovable.app/
