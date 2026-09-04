**SwiftPay Capstone — Written Deliverables**
__________________________________________
**1. The Engine Room: Master Prompt (RTCROS)**

Used to generate SwiftPay's user personas and the initial UX audit that identified the 60% drop-off.

**Role**: Act as a senior UX researcher and fintech trust specialist who has led onboarding redesigns for international payment apps.

**Task**: Analyze SwiftPay's transfer flow (login, home, transaction) and generate: (1) three distinct user personas representing SwiftPay's international user base, and (2) a friction audit that pinpoints the most likely drop-off point in the send-money journey, explaining the psychological or usability reason behind it.

**Context**: SwiftPay is a fintech app serving international users sending cross-border payments. The app currently has a 60% drop-off rate somewhere between opening a transfer and completing it. Users are wary of losing money to fraud or sending funds to the wrong recipient. The audience is not necessarily tech-savvy and may be sending money to family or contacts in another country for the first time.

**Constraints**: Do not recommend generic "make it prettier" fixes. Every recommendation must tie directly to a trust or fraud-prevention mechanism (verification, transparency, security messaging). Personas must be realistic, not stereotypes. Keep each persona under 100 words. Keep the audit to the single highest-impact friction point, not a general list.

**Reference**: Base the audit style on known fintech trust patterns: Confirmation of Payee checks, fee transparency before confirmation, biometric confirmation steps, and visible regulatory/security badges.

**Output**: Return three personas (name, age range, goal, biggest fear) as short profiles, followed by one friction-point diagnosis of 3-4 sentences and one concrete fix.

**Style** Write in a direct, consultative tone, as if presenting findings to a product team — clear, evidence-based, no fluff.
__________________________________________
**2. The Business Suit**
A-I-P Proposal (Audit → Insight → Proposal)

A consultative 3-part pitch structure for presenting this work to SwiftPay's stakeholders.

**Audit**: SwiftPay's transaction flow was reviewed end-to-end. The transfer journey (login → enter amount → confirm & send) currently asks users to commit funds to a recipient without any visible confirmation that the recipient's name matches the account on file. For an international user sending money across borders — often to someone they've never paid before — this is the single point where anxiety peaks and trust breaks down.

**Insight**: The 60% drop-off is not a UI problem in isolation; it's a trust gap at the exact moment of financial risk. Users don't abandon the app because the screen looks unpolished — they abandon it because nothing on screen answers the question running through their mind: "Am I sure this money is going to the right person, safely?" Fintech research consistently shows that visible verification and fee transparency at the point of commitment reduce abandonment more than any cosmetic redesign.

**Proposal**: We recommend inserting a Recipient Verification step directly before confirmation — showing a matched name check, upfront fee breakdown, and biometric confirmation — paired with visible regulatory and encryption badges earlier in the flow (login screen) so trust is established before the user is ever asked to commit funds. This is reflected in the attached 3-screen prototype. Expected outcome: a measurable reduction in transaction-stage abandonment, validated through A/B testing against the current flow.
__________________________________________
**3. The Workflow (Summary)**

User Research (AI-assisted) → Personas & UX Audit (AI, via RTCROS prompt) → Wireframes (AI wireframe tool) → Figma Prototype (human-led refinement) → Quality Audit (human-led review) → loop insights back into research.

See the accompanying workflow diagram for the visual version of this cycle.
<img width="427" height="527" alt="Screenshot 2026-09-04 at 13 11 33" src="https://github.com/user-attachments/assets/1e89ccc8-9adf-43ed-adf8-58d25b5e64d6" />
<img width="340" height="475" alt="Screenshot 2026-09-04 at 13 12 08" src="https://github.com/user-attachments/assets/c302f83f-60f3-4b39-931e-0ef1b7157f25" />
