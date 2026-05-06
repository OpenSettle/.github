# Security Policy

## Reporting a vulnerability

**Please do not file public issues for security vulnerabilities.**

If you've found a security issue in OpenSettle — the platform, an
SDK, an example, or anything else under
[github.com/OpenSettle](https://github.com/OpenSettle) — report it via:

- **Email:** [opensettle@proton.me](mailto:opensettle@proton.me)
- **security.txt:** [opensettle.io/.well-known/security.txt](https://opensettle.io/.well-known/security.txt)

Both are monitored. Email is preferred for first contact.

We aim to acknowledge reports within 24 hours and to provide an initial
remediation timeline within 72 hours.

## Disclosure policy

The full disclosure policy — including safe-harbor commitments, scope,
and out-of-scope categories — is at
[opensettle.io/security](https://opensettle.io/security).

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
- The OpenSettle production API (`api.opensettle.io`)
- The OpenSettle web app (`opensettle.io`, `app.opensettle.io`)
- Any code in any public OpenSettle/* repository (SDK, examples, etc.)
- Documentation if it would mislead someone into a vulnerable
  integration

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
