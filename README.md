# Digital Nomad Visa Tracker

Digital-nomad and remote-worker residence schemes, one record per scheme: status, income rule, savings alternative, initial length, government fee, processing time, dependants and health-insurance rules, each with an official source link and a checked date. Amounts are stored as the source states them, in the source currency and period; nothing is converted. A blank means the official page did not state it or could not be read, not that no requirement exists. General information, not immigration advice.

- Canonical page: https://nomadterminal.com/visas/
- Statistics computed from this dataset: https://nomadterminal.com/visas/statistics/
- Version: 2026-09-29 (the date the data was last checked)
- Publisher: Nomad Terminal editorial, an independent research publication at https://nomadterminal.com
- Size: 55 schemes in 53 countries

## Files

| File | Contents |
|---|---|
| `nomad-visa-tracker.csv` | CSV, UTF-8. One row per scheme. 55 rows. |
| `nomad-visa-tracker.json` | The full dataset as JSON, including nested fields. |
| `schema.json` | JSON Schema for the main file. |
| `METHOD.md` | How the data was compiled and derived. |
| `GAPS.md` | What is missing or unverified. |
| `CHANGELOG.md` | Dated change log. |
| `CITATION.cff` | Citation metadata (Citation File Format 1.2.0). |

## Source method

Every fact traces to a primary source (vendor, government, or a named independent reviewer) linked in the row it belongs to, with the date it was checked. Values are stored as the source states them; nothing is converted between currencies. Empty or null means the source did not state it or could not be read, never a guess. Read METHOD.md for the full rules and GAPS.md for what is missing. We compile from public pages and do not run our own tests.

## Licence

Creative Commons Attribution 4.0 International (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/. You may copy, redistribute and adapt the data, including commercially, if you give credit and **link to the canonical page**: https://nomadterminal.com/visas/. Suggested credit: "Data: Digital Nomad Visa Tracker by Nomad Terminal, https://nomadterminal.com/visas/".

## Cite

Nomad Terminal editorial. (2026). *Digital Nomad Visa Tracker* (Version 2026-09-29) [Data set]. Nomad Terminal. https://nomadterminal.com/visas/

Machine-readable citation: see `CITATION.cff`.

## Corrections

If you find an error, tell us through the contact page on https://nomadterminal.com. Corrections are logged in CHANGELOG.md.
