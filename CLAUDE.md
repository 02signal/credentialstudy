# CredentialStudy Site Rules

This repository is part of the Ettevõtluskeskus OÜ / 02Signal site group.
`credentialstudy.com` is the **online learning / provider brand** (a school) — the place
where our own recognised microcredentials are taught and sold.

## PUBLISHING GATE — CHECK BEFORE EVERY PUBLIC CHANGE

Read `CLAUDE.local.md` first if it exists — it holds owner-only constraints that
override everything here (including launch timing and what may be announced).

## Brand separation (important)

- **CredentialStudy = provider/academy** (this site): teaches and sells our own
  microcredentials, English-first, for working adults across Europe.
- **The neutral register** (`mikrokvalifikatsioon.ee`) is a SEPARATE brand and repo.
  It must stay neutral. CredentialStudy may appear there only as one listed provider,
  by the same rules as everyone else, disclosed — never with preferential treatment.
- Do not blur the two brands, share a domain, or imply the register endorses us.

## Audience & tone

English-first, working adults (25–55) across Europe considering upskilling or a career
change. Plain, concrete language: "skill", "recognised", "online", "months not years",
"worth it". Avoid jargon and empty EU-speak.

## Commercial rule

Every main page should answer: what skill the learner gets, how long it takes, what it
costs, who can help fund it (employer / public support / self), what it's worth, and the
next safe step.

## Tracking

Keep the family GA4 event taxonomy stable: `cta_click`, `email_click`, `phone_click`,
`lead_form_start`, `lead_form_submit_attempt`, `lead_form_submit`, `result_high_intent`.
Useful params: `form_name`, `role`, `source_site`, `delivery`.

## Privacy

No raw personal data, secrets or tokens in the repo or public files. Forms explain what
is collected and why. Analytics is consent-gated (Consent Mode v2, basic).

## Technical

Astro static site (Vercel + Cloudflare DNS, same family pattern). Before completing work:
1. Run `npm run build`.
2. Commit the scoped change.
3. Push and deploy only when requested (see the publishing gate).
4. Update `BACKLOG.md` when a follow-up is discovered.
