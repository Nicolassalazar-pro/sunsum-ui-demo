# SunSum Sunroom preview

[Open Sunroom](https://nicolassalazar-pro.github.io/sunsum-ui-demo/)

An interactive community-solar preview in the original SunSum navy, gold, and
community-green styling, with light and dark themes. The base URL opens Sunroom
directly.

Sunroom includes site-owner, operator, and investor views. No account or password
is required to open the preview.

## Sunroom workflows

- Revisitable profile setup, resumable site intake, linked project maps/lists,
  and scoped owner tasks and document metadata.
- Action-first operator review, separate acceptance/stage/publication actions,
  manual example assessments with history, and editable private demo notes.
- Investor filters and preferences, illustrative comparison scenarios,
  nonbinding interest and withdrawal, and separate minimal owner notices.
- Editable project briefings and assessment reports, snapshot-based review,
  and real local HTML/CSV downloads, including scoped portfolio summaries.

Fresh or explicitly reset scenarios contain **50 fictional records**, with
**six owner-visible examples** and **47 initially published investor projects**.
Existing saved browser progress is preserved rather than
automatically expanded. Valid v1 saves migrate to the synthetic v2 format with
the original payload retained for recovery. All three roles share that
browser-local scenario.

Responsive navigation, keyboard controls, short state transitions, and
reduced-motion alternatives keep the same workflows usable across screen sizes.

## Demo boundaries

All project data and estimates are fictional. Changes stay in the viewer's
browser. Files are represented by metadata only; no original documents are
read or uploaded. HTML/CSV exports contain locally generated demo content, not
original uploaded files, signed agreements, native Word files, or editable PDFs.

No operational backend connections are configured. Real sign-in, provider
assessments, live maps, utility retrieval, investments, payments, and recipient
delivery are unavailable. Guidance is scripted and typed; there is no app
speech, microphone capture, or live AI service. Selected-project financial outcomes remain
uncalculated; existing comparison scenarios are illustrative, not investment
advice or measured performance.

Use fictional details. The role selector demonstrates the interface and is not
an authorization boundary.

## Repository and hosting

This repository contains only the compiled static demo, screenshots, and license
notices. It does not contain the development source, private project documents,
or conversation exports.

GitHub Pages serves the root of the `main` branch. The unchanged repository URL
opens Sunroom directly; relative assets and hash-based routes work under that
same hosting path. `.nojekyll` keeps the compiled files unchanged.

The original public landing (`#/`), create-profile (`#/join`), and site-owner
dashboard (`#/dashboard/site-owner`) routes remain available. Legacy
`#/concepts` and `#/concepts/gridline` links redirect to Sunroom, preserving role,
project, and workflow context.

The upstream SunSum project is
[pocketcalculator/sunsum-community-solar-virtual-power-plant](https://github.com/pocketcalculator/sunsum-community-solar-virtual-power-plant).
See `LICENSE.txt` and `THIRD-PARTY-LICENSES.txt` for attribution and licenses.
