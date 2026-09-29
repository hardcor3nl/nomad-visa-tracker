# Method: nomad-visa-tracker

**Scope.** National digital-nomad / remote-worker residence schemes, one record per scheme. The target of ~50-60 open schemes was not reached: 55 records, of which 46 are marked open. Countries where no official page could be reached are listed in GAPS.md rather than guessed.

**Canonical source.** This folder is the single source of truth: the site reads `nomad-visa-tracker.json`, `METHOD.md`, `GAPS.md` and `CHANGELOG.md` from here at build time (sites/nomadterminal/src/lib/tracker.ts) and serves the CSV/JSON downloads from it. `src/data/visas.json` is legacy and is not the tracker.

**Wave 1 (2026-09-29).** 55 records validated against schema.json (jsonschema, 0 errors). Secondary (law-firm or relocation) pages appear only in `secondarySources` and their field text is prefixed "[secondary]".

**Sources.** Government, embassy, consulate and official immigration or tourism-authority portals only. Every fact field carries a `source` URL; `sources` lists every page used. Law-firm pages appear only in `secondarySources`. The old Nomad Terminal `visas.ts` and guides were used only as a checklist of scheme names, never as data.

**Values.** Amounts are stored exactly as stated, in source currency and period. No currency conversions are included in this version, so no exchange rates apply. Text is paraphrased or translated (marked "(translated)").

**Nulls.** A field is null when the official page does not state it or could not be read. A null is not a statement that the requirement does not exist.

**Status.** `open` = an official page seen on the check date describes a currently available scheme; `unclear` = pages conflict or are unreadable; `closed`/`none` = official statement or absence, noted in `statusNote`. Some status values rest on pages that do not date themselves; re-check before publishing as fact.

**Known weaknesses.** Several records rely on search-result excerpts of official pages or tourism boards because the primary host blocked automated access (see GAPS.md). These should be re-verified in a browser before publication.

**Compilation.** Research was split across five parallel Sonnet research agents by region, merged by script (deduplicated by id, sorted by country), and checked for schema key completeness. Full JSON Schema validation was not run (validator not installed).

**Re-check cadence.** Monthly for fees, income thresholds and status; immediately on any reported change. Log each change in CHANGELOG.md.
