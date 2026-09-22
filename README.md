# SunSum website and Sunroom demo

[Open the website](https://nicolassalazar-pro.github.io/sunsum-ui-demo/) |
[Open Sunroom](https://nicolassalazar-pro.github.io/sunsum-ui-demo/#/concepts/sunroom) |
[Source PR #72](https://github.com/pocketcalculator/sunsum-community-solar-virtual-power-plant/pull/72) |
[Connection and deployment guide](https://github.com/pocketcalculator/sunsum-community-solar-virtual-power-plant/blob/2711ccce5e086c8ccdf065aadf36f9013ad51aad/docs/ws1/connection-and-deployment-guide.md)

The bare URL opens the **public SunSum landing page**. Choose **Open Sunroom
workspace** for the explicitly fictional, browser-local experience; no account
or password is required. Existing workspace deep links and legacy aliases
continue to work. There is one Sunroom design, not a second Gridline interface.

## Explore

- Site-owner, operator and investor workflows, an action-first operator view,
  linked map/list selection, contextual guidance and document history.
- Filters, lifecycle sorting, 25/50/100-row pages, card/list parity and return
  continuity through detail, Documents, Activity and Reports.
- A slim, sliding perspective pill beside the theme control, with keyboard,
  touch cancellation and reduced-motion support.
- Canonical Need, Opportunity and Impact stories with their three supplied,
  publication-approved clips. Play/Pause and Mute/Unmute are independent;
  leaving a topic stops playback. Nothing autoplays.

Fresh scenarios contain **50 fictional records**. Existing saved scenarios
and browser-local progress keep their migration/recovery path. Use fictional
details only. Public `#/join` is an unsaved participation preview; synthetic
Sunroom's local drafts and exports are separate from that preview.

## Static demo versus the dynamic application

| Experience | Data and authority |
| --- | --- |
| This GitHub Pages site | Fictional local workflows; no session/API transport or real service writes |
| Explicit server-demo | The separate Next application with an isolated mock store and deliberate seeded-session switching |
| Connected workspace | The same dynamic `/app` with approved database configuration, legitimate sign-in/mapping and fresh service authorization |

The dynamic application uses existing authorized reads and one deliberate
nonbinding project-interest command. It never replaces a failed connected
read with these samples or automatically retries an uncertain write. Its
role selector cannot grant real permissions.

The static site does not perform real sign-in, uploads, provider/GIS lookups,
paid assessments, financial execution, messaging or live AI generation.
Its document examples and generated exports are not uploaded originals.

## Download and operate

[Application/static bundles and the operator kit](https://github.com/pocketcalculator/sunsum-community-solar-virtual-power-plant/actions/runs/35685363163/artifacts/10677096134)
contain `sunsum-app-source.zip`, `sunsum-synthetic-demo.zip`, a schema-2
integrity manifest and setup/deployment documentation. GitHub artifact downloads
may require signing in. The guide provides separate static, server-demo and
connected starts, plus source-ZIP/operator-overlay instructions.

Source revision: `2711ccce5e086c8ccdf065aadf36f9013ad51aad`.
`demo-build.json` identifies the exact source and compiled asset hashes.
PR72 follows externally merged PR62; it does not undo that predecessor.

Production sign-in/mapping integration and confirmed host/database/Blob
configuration remain separate work. New profile/contact-list, candidate-parcel
and project-original frontend operations are not enabled merely because their
backend APIs exist. Actual WS4 output and per-site GIS enrichment agreements
also remain separate. **No Azure deployment was performed by this work.**

This repository contains compiled assets, intentionally synthetic screenshots,
approved media and attribution. GitHub Pages serves `main`; `.nojekyll`,
relative assets and hash routes preserve the existing hosting prefix.
See `LICENSE.txt`, `THIRD-PARTY-LICENSES.txt` and `AUDIO-CREDITS.txt`.
The third-party recordings are **not licensed under the software's MIT license**.
