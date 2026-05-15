# .github

OpenSettle's organization-level community files. GitHub recognizes
specific paths in this repo and applies them as defaults across every
public OpenSettle/* repository:

| File / path | What it does |
|---|---|
| `profile/README.md` | Renders on github.com/OpenSettle (org profile card) |
| `SECURITY.md` | Linked from the **Security** tab of every public org repo |
| `CODE_OF_CONDUCT.md` | Linked from each repo's community standards page |
| `CONTRIBUTING.md` | Shown when someone clicks **New Pull Request** without one |
| `ISSUE_TEMPLATE/*.md` | Picked from the dropdown when someone clicks **New Issue** |
| `PULL_REQUEST_TEMPLATE.md` | Pre-fills the PR body |

These don't replace files inside individual repos — repo-level versions
always take precedence. They're sensible defaults for any repo that
doesn't override them.

## Public repos this applies to

- [OpenSettle/opensettle-sdk-js](https://github.com/OpenSettle/opensettle-sdk-js) — Node / TypeScript SDK
- [OpenSettle/opensettle-sdk-python](https://github.com/OpenSettle/opensettle-sdk-python) — Python SDK
- [OpenSettle/opensettle-sdk-go](https://github.com/OpenSettle/opensettle-sdk-go) — Go SDK
- [OpenSettle/opensettle-sdk-rust](https://github.com/OpenSettle/opensettle-sdk-rust) — Rust SDK
- [OpenSettle/opensettle-openapi](https://github.com/OpenSettle/opensettle-openapi) — OpenAPI spec
- [OpenSettle/opensettle-postman](https://github.com/OpenSettle/opensettle-postman) — Postman collection
- [OpenSettle/opensettle-docs](https://github.com/OpenSettle/opensettle-docs) — Public docs source
- [OpenSettle/opensettle-webhook-examples](https://github.com/OpenSettle/opensettle-webhook-examples) — Webhook handlers
- [OpenSettle/opensettle-integration-examples](https://github.com/OpenSettle/opensettle-integration-examples) — End-to-end demos
- [OpenSettle/opensettle-status](https://github.com/OpenSettle/opensettle-status) — Status / postmortems
- [OpenSettle/audits](https://github.com/OpenSettle/audits) — Security audit summaries

## License

Templates and community files in this repo are [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) —
copy them into your own organization's `.github` repo without
attribution. We borrowed liberally from the same Contributor Covenant
template and Stripe-style PR template you'll find elsewhere; passing
that forward seems right.
