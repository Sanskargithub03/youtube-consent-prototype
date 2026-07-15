<div align="center">

# 🎬 Designing Consent for Young Viewers on YouTube

### A Product Management Case Study · Vedantu PM Internship

**How should YouTube (India) handle personal data and consent for minors,**
**in line with the Digital Personal Data Protection (DPDP) Act, 2023?**

[![Live Prototype](https://img.shields.io/badge/🔗_Live_Prototype-View_Demo-e30613?style=for-the-badge)](https://sanskargithub03.github.io/youtube-consent-prototype/)
[![Deck](https://img.shields.io/badge/📄_Product_Deck-Download-16213e?style=for-the-badge)](./YouTube_DPDP_Consent_Deck.pptx)

![Status](https://img.shields.io/badge/status-submitted-success?style=flat-square)
![Focus](https://img.shields.io/badge/focus-minors'%20consent%20flow-blueviolet?style=flat-square)
![Region](https://img.shields.io/badge/region-India-orange?style=flat-square)
![Law](https://img.shields.io/badge/law-DPDP%20Act%2C%202023-9c27b0?style=flat-square)

</div>

<br>

## 📌 The Problem

> YouTube's sign-up relies on a **self-declared birth date** — nothing verifies it.

A 14-year-old can enter an adult birth year and get an account whose watch history, search history, and location start feeding recommendations and ad-targeting — with **no parent in the loop**, and no consent that would hold up under DPDP's requirement for **verifiable parental consent (VPC)**.

| | |
|---|---|
| ⚖️ **Legal risk** | Penalties up to **₹250 crore** for mishandling children's data |
| 🤝 **Trust risk** | Parents, not children, are the real decision-makers on these accounts |
| 📢 **Reputational risk** | Risk of being named a large-scale non-compliant platform in India |

<br>

## 💡 The Solution

**Design principle:** default to the safest state — nudge for correction, not permission.

| # | Idea | What it does |
|---|------|---------------|
| 1 | **Minimal, on-device signal** | Flags likely-minor accounts without mandatory ID uploads for everyone |
| 2 | **Privacy-by-default toggles** | Every optional setting (recommendations, ads, 3rd-party sharing) starts **OFF** — parents opt in, not out |
| 3 | **In-app Parent Dashboard + 6-month nudge** | Lives inside YouTube itself, with a periodic review — not a one-time checkbox |
| 4 | **Soft self-correction** | A non-punitive, periodic prompt for accounts already mis-declared as adult — good faith over mass re-verification |

<details>
<summary><b>🤔 What this doesn't solve (click to expand)</b></summary>
<br>

A determined teen can still lie through the soft prompt, and signal-based detection isn't foolproof. This solution trades certainty for **proportionate, privacy-respecting friction** — not a perfect fix.

</details>

<br>

## 📁 What's in this repo

```
├── index.html                          → source for the live prototype (GitHub Pages)
├── YouTube_DPDP_Consent_Deck.pptx      → 11-slide product thinking deck
└── README.md
```

<br>

## 🗂️ The full case study covers

`Problem` → `User` → `Current Experience` → `Proposed Solution` → `Metrics & Success Criteria` → `Diagnostic Thinking` → `Dashboard` → `Rollout Plan` → `Risks & Trade-offs`

See the [full deck](./YouTube_DPDP_Consent_Deck.pptx) for all of it, including a "north star metric drops 15%" diagnostic scenario and a mock health dashboard.

<br>

## 🛠️ Built with

Structured and built with the help of **Claude (Anthropic)** — used transparently, per the assignment's own AI usage guidelines:

> *"You are welcome to use AI tools... We evaluate your thinking, not your prompts."*

All product decisions and trade-offs are mine to defend.

<br>

## 👤 Author

**Sanskar** — ECE, IIIT Nagpur
[LinkedIn](#) · [GitHub](https://github.com/sanskargithub03)

<br>

---
<sub>Case study submitted for the Vedantu Product Management Internship, 2026. Uses mock/illustrative data throughout. Not affiliated with or endorsed by YouTube or Google.</sub>
