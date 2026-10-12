# A/B Experiment Brief, Riverty business-unit case

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | Phone-wallet provisioning |
| Persona | Eligible, activated, loyal frequent Riverty cardholder (eligibility TBD). Lena is a user context, but not  a confirmed pilot participant |
| Expected outcome | higher repeat card usage, including in-store usage |
| Primary success metric | M3 card retention, activated pilot cardholders with at least one Riverty card purchase in Month 3 |
| Baseline rate | 69% synthetic planning benchmark, cohort TBD |
| Guardrail metric | Partner-checkout Riverty spend per random participant |
| Guardrail boundary | TBD |
| Second guardrail | · |
| Minimum Detectable Effect | 10% |
| Sample size per arm | 301 |
| Traffic split | 50/50 |
| Test duration | 3 months |
| Significance threshold | p < 0.05 (95%) |

## Control vs. Variant
- **Control (A):** Eligible activated pilot cardholders use the Riverty card under the current experience, without iphone-wallet provisioning.
- **Variant (B):** The same cardholders and card experience, plus the ability to provision the card to one supported phone wallet for in-store payments. Include provisioning success feedback and a clear next step in case of failure.
- **Held constant (isolation check):** Card terms, credit limits and repayment, eligibility, card issuing, existing card functionality, merchant acceptance, support, and measurement remain the same. The only difference is access to iphone-wallet provisioning.

## Hypothesis
> I believe that Phone-wallet provisioning for Eligible, activated, loyal frequent Riverty cardholder (eligibility TBD). Lena is a user context, but not  a confirmed pilot participant will result in higher repeat card usage, including in-store usage, as measured by a 10% change in M3 card retention, activated pilot cardholders with at least one Riverty card purchase in Month 3 within 3 months. We will protect Partner-checkout Riverty spend per random participant throughout the test.

## Shipping criteria
> We will **ship** if M3 card retention, activated pilot cardholders with at least one Riverty card purchase in Month 3 improves by ≥ 10% at p < 0.05 (95%) and Partner-checkout Riverty spend per random participant does not reach TBD after 3 months.
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 3 months, no results reviewed before this date.
