# PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** Phone-wallet provisioning. Enable pilot cardholders to add their issued Riverty card to a supported phone wallet for in store payments.
- **My finalized Must-Haves (after overriding the AI):** - An approved pilot cardholder can add their issued card to one supported phone wallet.
- The provisioned card can make an in-store payment at a compatible terminal.
- The user sees whether provisioning succeeded; if it fails, they get a clear next step.
Dependencies: active issued card, wallet/scheme support and Compliance approval.
- **What I demoted from Must → Should/Won’t, and why:** Moved card limits and authorisation to dependencies: these belong to the credit and issuing features. Moved transaction tagging to pilot measurement, not wallet functionality. Deferred a second wallet, extra guidance and online/in-app payments because they aren’t needed for the core in-store flow. Card removal and lost-device handling need confirmation from Compliance and the wallet provider before being classified as optional.

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** The PRD makes clear that the prototype simulates wallet provisioning, it tests usability, not real payments or M3 impact.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** The prototype retained "Step 1 of 2" and "Step 2 of 2" labels, although the final PRD removes the step indicator. The core flow worked as specified.
- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** https://req-pilot.lovable.app/
