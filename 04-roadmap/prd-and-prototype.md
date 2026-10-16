# PRD and Prototype

## Feature

**Phone-wallet provisioning:** enable an eligible, activated pilot cardholder to add the issued Riverty Card to one supported phone wallet for in-store payments.

## User problem

Riverty is unavailable where partner merchants do not offer it. Lena therefore falls back to Klarna, PayPal, or an existing debit or credit card.

## Must-haves

1. An eligible user with an active issued card can start provisioning to one supported phone wallet.
2. Required authentication and wallet-provider handoff complete securely.
3. The user sees a clear success state.
4. A failure state explains the next action: retry, eligibility guidance, or support escalation.
5. Wallet and in-store card events are instrumented for the experiment.
6. Card terms, credit policy, repayment, and existing card functionality are unchanged between experiment arms.

## Dependencies

- Active issued Riverty Card
- Compatible device and supported wallet
- Scheme and wallet-provider tokenisation support
- Risk and Compliance approval
- Defined eligibility and activation rules
- Customer Service escalation path

## Out of scope

- A second wallet during the beta
- New credit or repayment terms
- Pay-after-deciding
- Rewards or partner promotions
- Promotional nudges during the experiment
- Universal device or merchant compatibility

## Prototype

https://req-pilot.lovable.app/

The prototype simulates the provisioning flow and tests usability. It does not process real payments, prove provider readiness, or validate M3 impact.

## Experiment isolation

Control has the same activated cardholder and current card experience without phone-wallet provisioning during the three-month experiment. Variant adds only access to the provisioning flow. All other terms, support, app version, and measurement definitions remain constant.
