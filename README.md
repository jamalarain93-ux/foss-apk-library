# FOSS APK Library

A curated, **license-verified** library of free & open-source Android APKs, sourced from the [F-Droid](https://f-droid.org) repository. Every app here is redistributable under its own open-source license — no paid, cracked or pirated software is included.

## What is in this repo

| | |
|---|---|
| **APKs catalogued** | 658 |
| **Categories** | 115 |
| **Distinct licenses** | 20 |
| **Total size** | 13854.6 MB |
| **Source** | F-Droid (f-droid.org) |

## Files

- **`index.csv`** — the master index sheet. One row per app with: name, package, category, version, license, direct APK link, APK size, source-code link and the F-Droid page.
- **`media.csv`** — icon and screenshot links for every app (keyed by package).
- **`LICENSE-NOTES.md`** — how licensing was determined and what each license allows.
- **`categories.md`** — the full category breakdown.

## How to use

Every row in `index.csv` carries a **direct APK link** (`apk_url`) served by F-Droid over HTTPS. You can download any app straight from that link, or open its F-Droid page for the full description and changelog.

```bash
# example: download one app
curl -L -o app.apk "<apk_url from index.csv>"
```

## Licensing

All apps are published on F-Droid, which only distributes free and open-source software. The exact license for each app is recorded in the `license` column of `index.csv`. The most common licenses here are:

| License | Apps |
|---|---|
| GPL-3.0-only | 197 |
| MIT | 131 |
| GPL-3.0-or-later | 126 |
| Apache-2.0 | 104 |
| AGPL-3.0-only | 24 |
| AGPL-3.0-or-later | 19 |
| GPL-2.0-only | 13 |
| MPL-2.0 | 8 |
| BSD-3-Clause | 7 |
| GPL-2.0-or-later | 5 |
| ISC | 5 |
| EUPL-1.2 | 4 |

See `LICENSE-NOTES.md` for what each license permits.

## Categories

658 apps across 115 categories — see `categories.md` for the full breakdown.

## Attribution

All APKs are the work of their respective upstream developers. This repository is an index — it links to the canonical F-Droid-hosted builds and records each app's license and source-code URL. If you redistribute an app, keep its license and attribution intact.

_Generated 2026-10-01._
