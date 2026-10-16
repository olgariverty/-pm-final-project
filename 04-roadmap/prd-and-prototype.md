# PRD & Prototype Sprint (Module 4)

## Feature

**Wallet-Ready Instant Card:** allow an approved Riverty cardholder to add the issued card to one supported phone wallet immediately after approval, before the physical card arrives.

## Must-haves

- The user is approved and has an active issued card.
- The user's device is compatible with the selected pilot wallet.
- The user can start provisioning directly from the approval confirmation.
- Required authentication and wallet tokenisation complete securely.
- The user sees a clear success state when the card is ready.
- A failure shows an understandable reason, retry action, and support path.
- The provisioned card can make an in-store payment at a compatible terminal.
- The user can suspend the card or wallet token if the device is lost.
- Events capture provisioning, first transaction, in-store use, Month 3 retention, and partner-checkout spend.

## Dependencies

- Card approval and issuing.
- Scheme, processor, and wallet-provider support.
- Risk, Compliance, and security approval.
- Card art and wallet entitlement.
- Support readiness and operational escalation.

## Should / Could / Won't

### Should

- Lightweight first-use guidance.
- A second wallet if device mix and readiness justify it.
- Transaction notification after first payment.

### Could

- Multi-device token management.
- Provisioning through a secure deep link.
- Merchant logos in transaction history.

### Won't in the pilot

- Default-card nudges or promotions during the experiment.
- Cashback, rewards, or partner perks.
- New instalment, pricing, credit-limit, or repayment propositions.
- Markets outside Germany.

## Measurement principle

Success is not provisioning alone. The primary decision metric is Month 3 card retention; provisioning completion, first use within 14 days, and in-store usage explain whether the feature mechanism worked. Partner-checkout spend protects the existing merchant business.

## Prototype learning

The prototype clarified retry behaviour, authentication and offline states, and the difference between a visual flow and live wallet integration. It validates usability only, not real payments or retention.

**Prototype:** https://req-pilot.lovable.app/

The current platform-agnostic prototype is the retained base. A later iteration will add the approval entry point and explicitly show that wallet access is available before the physical card arrives.
