# Release v3.4.3 — Full English Monolingual Edition + Pipeline Completion

Changelog from `fc0d380..HEAD` (one commit):

## `ab085c9` — Full English monolingual edition + pipeline completion

- **Translation:** all 24 content notes across the seven layers translated to
  English; the repository is now a single-language edition with **zero Persian
  script and zero ZWNJ characters** in any tracked file (verified by Unicode scan).
- **Frontmatter harmonization:** every content note now carries `license: CC-BY-4.0`
  and `author` (Adel Gachkar, ORCID 0009-0006-7713-6004); status values normalized
  to the canonical vocabulary (`draft | active | canonical`).
- **CHANGELOG consolidated** (`CHANGELOG.md`): v3.4.3 changes, v3.4.2 baseline, and
  the translated v1.0.0 historical record; the stale bilingual
  `CHANGELOG_v1.0.0.md` removed.
- **`.zenodo.json` added** — upload metadata (title, creator + ORCID, MIT license,
  keywords, related identifiers) so future Zenodo deposits are correctly labeled;
  concept-DOI `10.5281/zenodo.22412461` unchanged.
- **LICENSE** copyright line corrected to `Adel Gachkar`.
- **README** expanded: family register table (seven repositories with versions),
  per-number epistemic triage (closed geometry / own simulations / empirical),
  and the Aligned-Protocol pointer to LIMEN-VACUI.
- **CITATION.cff** bumped to 3.4.3 with release date 2026-10-05.
- **Link integrity:** zero broken wikilinks (verified against the v3.4.2 registry).

## Verification battery (all pass)

| Check | Result |
|---|---|
| Persian/ZWNJ scan (30 md files) | 0 hits |
| Frontmatter coverage | 29/30 (CHANGELOG intentionally bare) |
| license + author fields | 30/30 |
| Broken wikilinks | 0 |

Model-level derivations with explicit falsification criteria; no empirical
cosmological claim is made.
