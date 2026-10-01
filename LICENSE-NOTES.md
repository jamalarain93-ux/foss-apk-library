# License notes

## How licensing was determined

Every app in this library comes from the **F-Droid** repository. F-Droid's inclusion policy requires that an app be free and open-source software (FOSS) with a license that permits redistribution. The exact SPDX license identifier for each app is taken from F-Droid's own index metadata and recorded in the `license` column of `index.csv`.

**No paid, cracked, modded or pirated applications are included.** If an app is not FOSS, it is not in this library.

## What the licenses here allow

| License | Redistribute | Modify | Notes |
|---|---|---|---|
| GPL-3.0 / GPL-2.0 | Yes | Yes | Copyleft — derivatives must stay GPL |
| AGPL-3.0 | Yes | Yes | Copyleft, extends to network use |
| MIT | Yes | Yes | Permissive, keep the copyright notice |
| Apache-2.0 | Yes | Yes | Permissive, includes patent grant |
| MPL-2.0 | Yes | Yes | File-level copyleft |
| BSD-3-Clause | Yes | Yes | Permissive |
| LGPL | Yes | Yes | Weak copyleft (library use) |
| Unlicense / CC0 | Yes | Yes | Public domain |

## License distribution in this library

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
| CC0-1.0 | 4 |
| Unlicense | 3 |
| CC-BY-4.0 | 2 |
| WTFPL | 2 |
| LGPL-3.0-only | 1 |
| BSD-4-Clause | 1 |
| PublicDomain | 1 |
| LGPL-3.0-or-later | 1 |

## Obligations when you redistribute

1. **Keep the license.** Ship the app's original license text with the APK.
2. **Keep attribution.** Credit the upstream developer (the `source_code` column links to their repository).
3. **Copyleft apps (GPL/AGPL/MPL).** If you modify and redistribute, you must make your modified source available under the same license.
4. **No warranty.** These apps are provided as-is by their authors.

## Source of truth

The canonical build for every app is the F-Droid-hosted APK linked in `index.csv`. F-Droid independently builds and signs these from the upstream source, which is why they are safe to redistribute.
