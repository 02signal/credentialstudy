# CredentialStudy Backlog

## Status
- 2026-06-13: Skeleton created — Astro static site, indigo "academy" brand (placeholder),
  shared Seo/Nav/Footer/Faq/Analytics, pages: home, programmes (planned/placeholder),
  how-it-works, faq, privacy. Consent-gated GA4, notify form (role-segmented),
  robots/llms/sitemap, JSON-LD (EducationalOrganization/WebSite/FAQPage). Embargo-safe,
  pre-launch, NOT deployed.

## Next (pre-launch)
- Real brand identity: logo + final palette (replace the placeholder indigo + wordmark).
  Then swap the nav wordmark for the logo and generate a branded OG.
- Per-page OG images (astro-og-canvas, same pattern as mikrokvalifikatsioon).
- Replace og-default.png with a branded image once the logo exists.
- Lead webhook: set `PUBLIC_SITE_LEAD_WEBHOOK_URL` (family n8n pattern) so notify
  signups are captured automatically (until then: mailto fallback).
- GA4 property + `PUBLIC_GA_MEASUREMENT_ID`; Search Console; Bing Webmaster.

## Owner-gated (see CLAUDE.local.md)
- Add real programme(s): outcomes, assessment, price, ECTS, enrolment dates, funding.
  Add Course / EducationalOccupationalCredential JSON-LD per programme.
- Connect DNS (credentialstudy.com + .eu), add domain in Vercel, deploy.
- credential.study as a short redirect (if kept); credentialstudy.eu defensive.

## Family
- Stay strictly separate from the neutral register (mikrokvalifikatsioon.ee). Appear
  there only as one listed provider, disclosed, by the same rules as everyone.
