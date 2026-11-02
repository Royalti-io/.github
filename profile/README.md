# Royalti

**Royalty accounting and rights management for labels, distributors and publishers.**

Royalti is a platform for the unglamorous half of the music business: ingesting royalty
statements from every source that sends them, splitting the money correctly, registering
works, delivering releases, and paying people what they're actually owed.

→ **[royalti.io](https://royalti.io)** · [Developers](https://royalti.io/developers) · [Help centre](https://royalti.io/help)

### 🧾 Free CWR tools: [CWR checker](https://royalti.io/tools/cwr-checker) · [CWR creator](https://royalti.io/tools/cwr-creator)

Check a CWR file, or build one from a spreadsheet. Both run in your browser. Your file is never uploaded.

### 🎛 [Royalti Skills](https://github.com/Royalti-io/royalti-skills) — free, cited music-industry reference

```bash
/plugin marketplace add Royalti-io/royalti-skills
```

Working reference on DDEX delivery and CWR registration for your AI assistant. Every normative
claim cites a primary source; where we couldn't cite something, we removed it rather than
hedging it.

## What we publish here

Most of the platform is closed. What we open source is the material that's useful whether or
not you ever become a customer — the API surface, and the industry knowledge that's
genuinely hard to find written down accurately.

Everything in the skills catalog passes two gates before it ships: a scrub checklist, and an
accuracy gate where an uncitable claim is deleted rather than softened. That pass has already
caught us being wrong — the record of what it caught is published alongside the skills.

| Repo | What it is |
|---|---|
| [`royalti-skills`](https://github.com/Royalti-io/royalti-skills) | A catalog of [Agent Skills](https://agentskills.io) covering the parts of the music business that are documented badly or not at all — a link-checked index of DDEX's primary sources, and how publishers register works with ASCAP, BMI and SOCAN via CWR. Written for label ops, distributors, publishers and rights admins. |
| [`royalti-cwr`](https://github.com/Royalti-io/royalti-cwr) | The open-source (MIT) engine behind the Royalti [CWR checker](https://royalti.io/tools/cwr-checker) and [CWR creator](https://royalti.io/tools/cwr-creator): parse, check, edit and write CWR 2.1 and 2.2 files. On npm as [`@royalti/cwr`](https://www.npmjs.com/package/@royalti/cwr). |
| [`royalti-api-skill`](https://github.com/Royalti-io/royalti-api-skill) | An [Agent Skill](https://agentskills.io) giving your AI assistant working knowledge of the Royalti REST API — auth, pagination, webhooks, DDEX distribution, publishing. Works with Claude Code, Cursor, Copilot, Codex, and anything supporting the open Agent Skills standard. |
| [`post-build-cliff`](https://github.com/Royalti-io/post-build-cliff) | A free course for non-technical founders shipping AI-built software. Three modules, thirteen lessons, opinionated tooling. |
| [`payloadcms-social-media-plugin`](https://github.com/Royalti-io/payloadcms-social-media-plugin) | Social sharing plugin for Payload CMS applications. |

## Looking for Ikenga?

Ikenga — the open-source desktop shell and package manager for Claude Code setups — moved to
its own organisation: **[github.com/ikenga-hq](https://github.com/ikenga-hq)**.

Old links still work; GitHub redirects `Royalti-io/ikenga*` paths to the new home. Existing
clones and remotes need no changes.

## Working with us

Bug reports and questions on any repo above are welcome — open an issue on that repo.
Security reports go through [SECURITY.md](https://github.com/Royalti-io/.github/blob/main/SECURITY.md),
not public issues.
