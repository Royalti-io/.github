# Security Policy

Royalti handles royalty statements, payout data and rights records for labels, distributors
and publishers. We take reports about any of it seriously.

## Reporting a vulnerability

**Do not open a public issue.** Two private routes:

1. **GitHub private vulnerability reporting** — the "Report a vulnerability" button under the
   Security tab of the affected repository. Preferred: it keeps the discussion attached to
   the code.
2. **Email** — `hello@royalti.io`. Encrypt if you can; ask for a key in your first message if
   you need one.

## What to include

- What the issue is, and which repo or endpoint it affects.
- How to reproduce it. A minimal proof-of-concept beats a description.
- What an attacker gets out of it — data access, privilege escalation, denial of service.
- Anything you already know about scope or affected versions.

## What to expect

- **Acknowledgement within 3 working days.** If you don't hear back, assume the mail went
  astray and chase it.
- An assessment and a rough timeline once we've reproduced it.
- Credit in the fix notes if you want it, and none if you don't.

## Scope

This policy covers the public repositories under
[`github.com/Royalti-io`](https://github.com/Royalti-io) and the hosted Royalti platform at
`royalti.io` and `api.royalti.io`.

Please don't test against production tenants that aren't yours, don't run automated scanners
against the hosted platform, and don't access, modify or exfiltrate anyone else's data. If
you need an account to test against, ask.

Ikenga has moved to its own organisation and its own policy — see
[`ikenga-hq/.github`](https://github.com/ikenga-hq/.github).
