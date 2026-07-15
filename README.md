Designing Consent & Data Trust for Young Viewers on YouTube
A Product Management case study prepared for the Vedantu PM Internship hiring assignment — designing how YouTube (India) should handle personal data and consent for minors, in line with India's Digital Personal Data Protection (DPDP) Act, 2023.
🔗 Live clickable prototype: [add your hosted link here]
📄 Product thinking deck: `YouTube_DPDP_Consent_Deck.pptx`
---
The problem
YouTube's sign-up flow relies on a self-declared birth date with no verification. This means a minor can easily claim to be an adult, after which their data — watch history, search history, approximate location — is used for recommendations and ad-targeting with no real parental consent behind it.
The DPDP Act, 2023 requires verifiable parental consent (VPC) and purpose-limited processing for anyone under 18. This project reimagines YouTube's sign-up and Supervised Experience flow to close that gap, without breaking the product for the vast majority of honest users.
The solution, in short
#	Idea	Why
1	Minimal, on-device age signal	Flags likely-minor accounts without mandatory ID uploads for everyone
2	Privacy-by-default consent	Every optional toggle (recommendations, ads, 3rd-party sharing) starts off — parents opt in, not out
3	In-app Parent Dashboard + 6-month nudge	Lives inside YouTube itself; consent is reviewed periodically, not just once
4	Soft self-correction for existing accounts	A non-punitive, periodic prompt for accounts already mis-declared as adult — assumes good faith over mass re-verification
The deck is also explicit about what this doesn't solve — a determined user can still lie, and signal-based detection isn't foolproof. The goal is proportionate, privacy-respecting friction, not certainty.
What's in this repo
```
├── YouTube_DPDP_Consent_Deck.pptx     # 11-slide product thinking deck
├── YouTube_Consent_Prototype.html     # Clickable prototype (happy path, mobile UI)
└── README.md
```
Product thinking deck
Covers the full case study brief: problem statement → user → current experience → proposed solution → metrics & success criteria → diagnostic thinking (a "north star drops 15%" scenario) → dashboard → rollout plan → risks & trade-offs.
Clickable prototype
A single-file HTML mobile mockup covering the happy path end-to-end:
`Sign-up → age flagged as minor → parent consent screen → confirmation → parent dashboard → data access / consent withdrawal → periodic re-consent review`
To view it, either:
Open `YouTube_Consent_Prototype.html` directly in a browser, or
Visit the hosted link at the top of this README
Tools used
Built with the help of Claude (Anthropic) for structuring the product thinking, generating the deck, and building the prototype — used transparently, per the assignment's own AI usage guidelines. All product decisions and trade-offs are mine and I can walk through the reasoning behind each one.
Author
Sanskar — ECE, IIIT Nagpur
LinkedIn · GitHub
---
Case study submitted for the Vedantu Product Management Internship, July 2026. Uses mock/illustrative data throughout; not affiliated with or endorsed by YouTube or Google.
