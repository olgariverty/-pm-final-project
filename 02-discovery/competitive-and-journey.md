# Competitive Analysis and Journey

## Persona

**Lena, 32, Cologne** is a frequent BNPL user who shops mainly on her phone. She uses whichever payment option is available and rarely seeks out Riverty.

## Goal and friction

- **Goal:** Pay only after deciding to keep an item.
- **Moment of misery:** Where a partner merchant does not offer Riverty, Lena falls back to Klarna, PayPal, or a bank card.
- **Relevant friction for this project:** Riverty reaches her only where partner merchants offer it; it cannot be used outside partner checkout.
- **Workaround:** Klarna, PayPal, or an existing debit or credit card.
- **Scope boundary:** Wallet provisioning expands acceptance; it does not itself provide pay-after-deciding, which remains unvalidated.

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
4. **Repeat:** the user makes at least one Riverty Card purchase during days 61–90.

## Research questions

- Does wallet provisioning complete successfully?
- Does it create in-store card usage?
- Does card use persist through days 61–90?
- Does partner-checkout spend remain within the proposed guardrail?
