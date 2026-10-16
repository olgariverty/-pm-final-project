# Competitive Analysis and Journey

## Persona

**Lena, 32, Cologne** is a frequent BNPL user who shops mainly on her phone. She uses whichever payment option is available and rarely seeks out Riverty.

## Goal and friction

- **Goal:** Use a flexible payment method while staying in control of payment timing.
- **Relevant friction for this project:** Riverty cannot be used outside partner checkout.
- **Workaround:** Klarna, PayPal, or an existing debit or credit card.
- **Scope boundary:** Wallet provisioning expands acceptance; it does not itself provide pay-after-deciding.

## Competitive alternatives

| Alternative | Why it wins the moment | Riverty implication |
|---|---|---|
| Klarna | Familiar BNPL option when offered | Riverty needs a route beyond its own partner checkout |
| PayPal | Broad online availability and remembered account | Convenience and reach matter alongside financing |
| Debit or credit card | Works across many online and in-store merchants | The Riverty Card must earn repeat use, not merely exist |
| Do nothing | User accepts whichever option appears | Riverty remains dependent on merchant placement |

## Future-state journey

1. **Activate:** an eligible user activates the issued Riverty Card.
2. **Provision:** the variant can add the card to one supported phone wallet.
3. **Use:** the user makes an in-store wallet transaction at a compatible terminal.
4. **Repeat:** the user makes at least one Riverty Card purchase in Month 3.

## Research questions

- Does wallet provisioning complete successfully?
- Does it create in-store card usage?
- Does card use persist into Month 3?
- Does partner-checkout spend remain within the proposed guardrail?
