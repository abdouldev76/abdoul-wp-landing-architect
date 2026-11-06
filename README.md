# Abdoul WP Landing Architect

**A private AI Agent Skill for structured WordPress landing-page planning.**  
**Public documentation preview · v0.2.0**

> Turn a verified business brief into a mobile-first landing-page blueprint grounded in user experience, practical WordPress implementation, and honest launch decisions.

## What it helps you plan

| Capability | Output | Why it matters |
| --- | --- | --- |
| Page architecture | Prioritized sections and visitor questions | Keeps the page focused on the intended user journey. |
| UX-informed copy | Sample English headlines, supporting text and CTA labels | Connects each action to a clear purpose without inventing business claims. |
| Responsive strategy | Mobile, tablet and desktop layout recommendations | Supports legibility and predictable navigation across screen sizes. |
| WordPress handoff | Gutenberg block suggestions and integration limits | Distinguishes core blocks from functionality needing additional engineering. |
| Quality gates | Accessibility, SEO and pre-launch questions | Makes unverified claims and unresolved requirements visible early. |

## Example workflows

- **B2B industrial supply:** Organize a request-for-quote journey without inventing delivery promises or catalog breadth.
- **Local services:** Draft an appointment-inquiry page without pretending an email inquiry is a confirmed booking.
- **Conflicting requirements:** Flag requests for checkout or live scheduling when only core Gutenberg blocks are allowed.

[View the fictional example](DEMO_OUTPUT.md) · [Read limitations and FAQ](docs/FAQ.md) · [See validation status](docs/VALIDATION_STATUS.md)

## How the private Skill works — at a high level

1. Identify the confirmed offer, audience, objective, constraints and missing information.
2. Propose a section sequence with UX rationale and draft content.
3. Define layout tokens, responsive behavior and accessible interaction considerations.
4. Map the plan to WordPress/Gutenberg, calling out any required third-party or custom implementation.
5. Produce test recommendations and a truthful **GO / NO-GO** decision for the proposed specification.

**Example safety rule:** When the recipient email address is unknown, an email CTA stays **DRAFT ONLY**; there is no invented `mailto:` link or functional booking button.

## What is available here?

This repository is a **public documentation preview only**. It does **not** include the private runnable `SKILL.md`, proprietary references, scripts, or full Skill distribution package. GitHub's automatically generated source archives contain only this public documentation and cannot be installed as the full Agent Skill.

## Validation status

The private `v0.2.0` package passed local structural and written release-regression checks. A single limited Codex integration smoke test reported that the correct version loaded and produced a safe fictional blueprint. These are **limited, partially self-reported checks**, not an independent product audit.

**Not tested or certified:** live WordPress builds, browser compatibility, email delivery, payment or scheduling integrations, full WCAG 2.2 AA conformance, security review of deployed systems, marketplace approval, or customer outcomes. The fictional scenario was appropriately marked **NO-GO** for publication until required contact details and implementation constraints were resolved.

## Release and availability

- [Public preview release `v0.2.0-preview`](https://github.com/abdouldev76/abdoul-wp-landing-architect/releases/tag/v0.2.0-preview)
- Private Skill licensing, distribution and pricing are **not announced**.
- Marketplace submission depends on platform-specific account and region eligibility.

## Security and usage

Do not include passwords, API tokens, customer data, or production credentials in public issues or discussions. Please read [SECURITY.md](SECURITY.md). This documentation does not grant redistribution rights to the private Skill; no standalone public software license has been selected.

---

*Independent project preview. Not affiliated with, endorsed by, or certified by WordPress, Figma, Capafy, or a marketplace.*
