<h1 align="center">Lucas · @tobenwarrior</h1>

## Contributing to Hermes Agent

I contribute upstream to **[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)** — the open-source agent framework:

| | Count | Where to verify |
|---|---|---|
| Pull requests opened | **20** | [`pulls?q=author:tobenwarrior`](https://github.com/NousResearch/hermes-agent/pulls?q=is%3Apr+author%3Atobenwarrior) |
| Merged upstream | **3** | [`…+is:merged`](https://github.com/NousResearch/hermes-agent/pulls?q=is%3Apr+author%3Atobenwarrior+is%3Amerged) |
| Issues filed (bugs + design) | **17** | [`issues?q=author:tobenwarrior`](https://github.com/NousResearch/hermes-agent/issues?q=is%3Aissue+author%3Atobenwarrior) |

### Two of my plugins ship in the official Hermes plugin catalog

Published upstream and installable by any Hermes user (`hermes plugins install <name>`):

| Plugin | What it does | Catalog | Source |
|---|---|---|---|
| **`kiro-acp`** | AWS Kiro CLI exposed as a Hermes **model provider** over ACP stdio — a new model backend behind an existing agent platform | `v0.1.2` | [hermes-kiro-provider](https://github.com/tobenwarrior/hermes-kiro-provider) |
| **`provider-copy`** | Desktop plugin: copy provider credentials + base-URL overrides from one profile to other agents — explicit, one-time, secret-safe | `v1.0.1` | [hermes-provider-copy](https://github.com/tobenwarrior/hermes-provider-copy) |

Merged via [#113833](https://github.com/NousResearch/hermes-agent/pull/113833) and [#116349](https://github.com/NousResearch/hermes-agent/pull/116349).

### Plugin SDK & desktop platform work — 14 PRs open for review

Two coherent workstreams, both in review upstream right now:

- **Plugin SDK** — making third-party plugins first-class citizens of the desktop app: a sandboxed
  embed primitive for external content, a public plugin-backend → desktop event bridge, appearance
  and settings slots, typed bridges for skills/toolsets/profiles, model-pill label providers,
  session-list APIs and row-decoration slots.
- **Bot Mode / multi-agent UX** — running several agents side by side: each bot's chat as its own
  tab, one thread per bot pair, drag-reorder for bots and roster sections, naming a duplicate agent
  before creation, pinned sessions rendered correctly.

I also filed the accompanying design series upstream — 7 "plugin SDK wishlist" issues — so the
surface gets specified before it gets built.

> Open PRs are **under review, not merged**. Every number above is one click from the search query
> that produces it.
