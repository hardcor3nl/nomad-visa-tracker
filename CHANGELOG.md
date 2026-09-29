# Changelog

## 2026-09-29 (wave 2)
Asia and Europe null-field runs. Cyprus values come from search excerpts of gov.cy pages (host blocked, 403) and need a browser re-check; Kazakhstan fee is [secondary]; Bulgaria and Italy figures are labelled computed or approximate in their records. Italy minIncome changed to about EUR 27,000 a year (Tunis embassy sheet, May 2026) from the earlier 24,789 / 12 figure. Record count unchanged at 55.

- cyprus-digital-nomad-visa: status unclear -> open (from search excerpts of gov.cy; host 403)
- cyprus-digital-nomad-visa: minIncome 3500 EUR/month, duration 12 months + 2-year renewal, dependants allowed, taxTreatment (183-day residency note) filled from gov.cy excerpts
- czechia-digital-nomad-program: duration (max 1 year), governmentFee 2500 CZK, healthInsurance filled from MFA long-term visa (business) and fee pages
- germany-freelance-residence-permit: governmentFee 100 EUR (Berlin eAT), processingTime 4-6 weeks (Berlin), healthInsurance required, dependants text added
- romania-digital-nomad-long-stay-visa: processingTime 30 days (+15) general residence-right procedure per IGI excerpt
- latvia-remote-work-long-stay-visa: governmentFee 90 EUR (general D visa fee, PMLP)
- montenegro-digital-nomad-residence: status unclear -> open (digitalnomads.gov.me still shows Apply now)
- greece-digital-nomad-visa: savingsAlternative none in Art. 11, governmentFee amount 75 EUR, duration.maxRenewalsText (2-year permit renewable) from Law 4825/2021 art. 11 text via e-forologia; healthInsurance unresolved
- malta-nomad-residence-permit: savingsAlternative none stated; governmentFee and processingTime verified on Residency Malta application-process page
- hungary-white-card: taxTreatment from NAV summary (residents worldwide 15%, non-residents Hungarian-source)
- bulgaria-digital-nomad-long-term-residence: minIncome COMPUTED 50 x BGN 1,077 = BGN 53,850; dependants note (none in Art. 24c)
- slovenia-digital-nomad-temporary-residence: taxTreatment from FURS guidance; minIncome amount, fee, processing left null
- portugal-d8-residence-visa: taxTreatment (AT IFICI page); duration 24 months renewable 3-year periods (AIMA)
- portugal-temporary-stay-remote-work: taxTreatment (AT IFICI page)
- italy-digital-nomad-remote-worker-visa: minIncome conflict resolved to approx EUR 27,000 a year (Tunis May 2026); taxTreatment (Agenzia Entrate impatriati)
- spain-international-teleworker: duration renewals from Ley 14/2013 arts. 74 quater/quinquies; governmentFee text extended, no single amount
- estonia-digital-nomad-visa: fee and processing verified, no change
- thailand-ltr-work-from-thailand-professional: duration, governmentFee, processingTime, taxTreatment, dependants filled from ltr.boi.go.th (checked 2026-09-29)
- japan-digital-nomad-designated-activities: taxTreatment replaced with the ISA Q&A wording (moj.go.jp)
- south-korea-workation-f-1-d: minIncome amount 52,420,000 KRW/year from Seattle consulate; LA consulate conflict (USD 66,000) noted
- kazakhstan-neo-nomad-b12-1: minIncome USD 3,000/month, processing 5 working days, insurance required (gov.kz MFA PDF); fee KZT 117,960 marked [secondary]
- taiwan-digital-nomad-visitor-visa: processingTime about two weeks (TECO Philippines)
- turkey-digital-nomad-visa: governmentFee (Houston USD 60/180 single/multiple, higher for US citizens), processingTime (LA up to 30 days after interview), healthInsurance (EUR 30,000 minimum) from consulate PDFs

## 2026-09-29 (audit)
Independent audit: Serbia and Peru removed (no usable data, see GAPS); Georgia set to none; Cayman Islands set to closed; Greece figures re-sourced (mfa.gr page states none); Bulgaria and Moldova fields annotated. 57 to 55 records.

## 2026-09-29
Wave 1 completion sprint. 46 to 57 records: added Greece, Slovenia, Bulgaria, Albania, Georgia, Serbia, Moldova, Mexico, Peru, Grenada and Cayman Islands. Filled null fields for Portugal, Spain, Italy, Estonia, Croatia, Hungary, the Americas set and the Caribbean/Africa set; statuses for Panama and Belize settled. Details:

- portugal-d8-residence-visa: minIncome.amount null -> 3680 EUR/month (4 x RMMG 920 EUR for 2026 per DGERT; computed, visa page states only the multiple)
- portugal-d8-residence-visa: duration.initialMonths null -> 24 (AIMA: temporary residence permit valid 2 years, renewable in 3-year periods)
- portugal-d8-residence-visa: healthInsurance.required null -> true (general travel insurance in residency document list)
- portugal-temporary-stay-remote-work: minIncome.amount null -> 3680 EUR/month (4 x RMMG 920 EUR for 2026; computed)
- portugal-temporary-stay-remote-work: healthInsurance.required null -> true (general travel insurance in temporary-stay document list)
- spain-international-teleworker: taxTreatment.text null -> special regime for relocating workers (IRNR-style option, 6 tax years), AEAT
- spain-international-teleworker: governmentFee.text expanded with full 2026 nationality table; amount left null (varies by nationality)
- spain-international-teleworker: minIncome re-verified unchanged (2,442 EUR/month; SMI 1,221 EUR for 2026, RD 126/2026)
- italy-digital-nomad-remote-worker-visa: governmentFee.amount null -> 116 EUR (Paris consulate; varies by consulate)
- italy-digital-nomad-remote-worker-visa: processingTime.text null -> varies by consulate (30-90 days remote workers, 120 days nomads)
- italy-digital-nomad-remote-worker-visa: minIncome conflict noted in notes (24,789 vs 25,500 EUR), value unchanged
- estonia-digital-nomad-visa: taxTreatment.text null -> 183-day residency test (EMTA, e-Residency FAQ)
- estonia-digital-nomad-visa: dependants.allowed null -> true (spouse, minor child, dependent adult child may apply)
- croatia-digital-nomad-temporary-stay: taxTreatment.text null -> income of digital nomads exempt from taxation per Tax Administration 2021 changes page
- hungary-white-card: governmentFee.amount null -> 110 EUR (consulate residence-permit fee; HUF alternatives in text)
- malta-nomad-residence-permit: no field changes; income threshold and status re-confirmed
- Brazil: e-visa from 1 Sept 2026 noted, fee varies by consulate, insurance, processing (excerpts only)
- Argentina: fee 32 UMSM (1 UMSM=$1000), TIE 24H, where to apply
- Colombia: SMMLV 2026 COP 1,750,905 basis, tax residency rule
- Costa Rica: duration 12m+1yr, USD 50,000 insurance, income tax exemption per tourism board
- Ecuador: fee 320 confirmed, SBU 2026 USD 482
- Uruguay: 6 months renewable once
- Panama: settled open, B/.36,000/yr, 9 months, USD 250, insurance
- Belize: settled open (BTB page); immigration site silent
- New: Mexico temporary resident (Las Vegas 2026 sheet); Peru (unclear, legal status not operational)
- antigua: closure re-confirmed from official notices page; PDF still 404; notes updated
- aruba: taxTreatment filled from aruba.com (no Aruba tax, income paid by home-country company)
- curacao: government ownership supported by curacao.com tourist board article; fee discrepancy ($294 vs ANG 535) noted
- dominica: taxTreatment and healthInsurance source filled from official WIN FAQ
- montserrat: taxTreatment (gov.ms) and duration source filled; income USD 70,000 cross-checked on programme site the-stamp page
- mauritius: minIncome USD 1500/month (EDB FAQ PDF), dependants, duration filled
- south-africa: minIncome now sourced to DHA PDF (R650 796); duration text from DHA heading (3 months to 3 years)
- NEW grenada-remote-employment-act-permit from Act No. 3 of 2021 (status unclear)
- NEW cayman-islands-global-citizen-certificate from 2023 Revision regulations (status unclear; deadline 31 Oct 2022, expiry 30 Nov 2024 unless extended)
- slovenia-digital-nomad-temporary-residence: new, gov.si notice of 2025-11-21
- albania-unique-permit-digital-mobile-workers: new, Law 79/2021 Art. 68 (statute PDF)
- bulgaria-digital-nomad-long-term-residence: new, State Gazette amendment + Council of Ministers service register (translated)
- moldova-digital-nomad-right-of-residence: new, IGM and Invest Moldova pages
- georgia-remotely-from-georgia: new, status unclear (past-tense tourism authority description, visa-free year)
- serbia-digital-nomad-temporary-residence: new, status unclear (enabling clause only)
- greece-digital-nomad-visa: new, mostly from search excerpt of mfa.gr page; needs browser re-verification

## 2026-09-28
Initial compilation, 2026-09-28. 46 records across 44 countries (39 open, 6 unclear, 1 closed, 1 none). About 63% of checkable fields verified from government, embassy or official-portal pages; the rest are null (see GAPS.md). Replaces the blocked earlier run.

- 2026-09-29 audit: italy minIncome corrected from approx 27,000 to 24,790 (decree DM 29 Feb 2024 art. 3(1)(a): 3 x EUR 8,263.31 exemption level, Sistema TS); Tunis May 2026 sheet (says approximately 27,000, unexplained) kept as a consulate figure.
