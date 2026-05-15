# Security Policy

## Reporting a vulnerability

**Please do not file public issues for security vulnerabilities.**

If you've found a security issue in OpenSettle — the platform, an
SDK, an example, or anything else under
[github.com/OpenSettle](https://github.com/OpenSettle) — report it via:

- **Email:** [OpenSettle@proton.me](mailto:OpenSettle@proton.me)
- **security.txt:** [opensettle.io/.well-known/security.txt](https://opensettle.io/.well-known/security.txt)

Both are monitored. Email is preferred for first contact.

We acknowledge new reports within 72 hours and provide a triage
decision (with assigned severity) within 7 days.

## Disclosure policy

The full disclosure policy — safe-harbor commitments, scope,
out-of-scope categories, severity tiering, and target patch SLAs — is at
[opensettle.io/legal/vulnerability-disclosure](https://opensettle.io/legal/vulnerability-disclosure).
A short overview lives at [opensettle.io/security](https://opensettle.io/security).

In summary:

- Researchers acting in good faith and following this policy will not
  face legal action from OpenSettle.
- We coordinate disclosure with the reporter. Public disclosure happens
  after a fix ships, with credit to the reporter unless they prefer
  anonymity.
- A formal bug bounty program will launch alongside the first external
  audit. Until then, we acknowledge researchers and may pay out at our
  discretion.

## Scope

In scope:
- The OpenSettle production API (`api.opensettle.io`) and its documented
  public endpoints
- The OpenSettle web app (`opensettle.io`, including the dashboard)
- Our published SDKs (`@opensettle/sdk` on npm, `opensettle` on PyPI,
  `opensettle-sdk-go`, `opensettle` on crates.io)
- Any code in any public OpenSettle/* repository (examples, OpenAPI spec, etc.)
- Documentation if it would mislead someone into a vulnerable integration

Auth bypass, payment-intent issuance, webhook signing, and tenant
isolation are the highest priority paths.

Out of scope:
- Issues in third-party services we use (Vercel, Fly.io, Supabase,
  Resend, etc.) — please report those to the vendor directly.
- Test mode integrations (no real funds at risk by definition)
- Reports requiring physical access to a merchant's machine
- Volumetric DoS without a downstream impact (we won't pay you to
  flood our edge)

## Audit reports

Self-audit summaries are published at
[github.com/OpenSettle/audits](https://github.com/OpenSettle/audits).
External audit reports will land there too as those engagements happen.
