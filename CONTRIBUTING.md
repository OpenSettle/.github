# Contributing

Thanks for considering a contribution to OpenSettle.

We're a small team — the response time on issues and pull requests will
be measured in days, not hours. Setting expectations up front so neither
of us is disappointed.

## Where things land

Different repos take different kinds of work. Pick the right one before
opening anything:

| If you want to… | Open an issue or PR in… |
|---|---|
| Fix a typo or bug in the docs | [opensettle-docs](https://github.com/OpenSettle/opensettle-docs) |
| Report a bug in the Node SDK | [opensettle-sdk-js](https://github.com/OpenSettle/opensettle-sdk-js) |
| Suggest a missing endpoint or wrong type in the spec | [opensettle-openapi](https://github.com/OpenSettle/opensettle-openapi) |
| Add a webhook example in a new language | [opensettle-webhook-examples](https://github.com/OpenSettle/opensettle-webhook-examples) |
| Improve the Postman collection | [opensettle-postman](https://github.com/OpenSettle/opensettle-postman) |
| Report a security vulnerability | **DO NOT open an issue.** See [SECURITY.md](./SECURITY.md). |

For anything that affects the platform itself (API behavior, billing,
auth, etc.), we'll triage in the relevant public repo and route the work
internally.

## Pull requests

Before you spend time:

1. **Open an issue first** for substantive changes. We may already be
   working on the same thing, or we may have context that changes the
   shape of the fix. Small typo / one-line fixes — go ahead and PR
   directly.
2. **Match the existing style.** Each repo's existing code is the
   reference. We don't have a published style guide; we'd rather match
   what's there than have you fight against it.
3. **Keep PRs focused.** One logical change per PR. Easier to review,
   easier to revert.
4. **Tests welcome.** Especially for SDK and examples — the bar is
   "could a stranger maintain this in 6 months without our help."

## Code of Conduct

By participating you agree to follow our [Code of Conduct](./CODE_OF_CONDUCT.md).
Short version: be kind, assume good faith, focus on the work.

## Questions

For things that aren't clearly a bug or PR, open a Discussion in the
relevant repo (where Discussions are enabled), or email
[opensettle@proton.me](mailto:opensettle@proton.me).
