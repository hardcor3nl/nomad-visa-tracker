# GAPS: nomad-visa-tracker

Checked 2026-09-29 (wave 1 sprint; earlier per-region logs from 2026-09-28 kept below). Every field listed below is null in the dataset because no primary source could be read or the official page does not state it. Nothing was filled from memory or from the old site.

## Schemes on the checklist with NO record (no official page reached; not confirmed as absent)
Poland, Lithuania, Armenia, Iceland, Norway, Seychelles, Namibia, Chile, El Salvador, Dominican Republic, Vietnam, Cambodia, Oman, Bahrain, Uzbekistan, Abu Dhabi, Saint Lucia, Jamaica, St Vincent, Trinidad and Tobago, Turks and Caicos, Anguilla, St Kitts and Nevis, Egypt, Morocco. Added 2026-09-29: Greece, Slovenia, Bulgaria, Albania, Georgia, Serbia, Moldova, Mexico, Peru, Grenada, Cayman Islands. Not confirmed as absent; see the omitted list below. Blocked hosts: several .my/.hr/.kr/.gov.br hosts.

## Notes
- Germany record has status `none`, inferred from absence on the pages checked, not from an official statement.
- Panama, Belize, Cyprus, Philippines, Czech Republic status `unclear` or mostly null.
- Brazil and Japan/Korea/Philippines partly rest on search-result excerpts of official pages (pages blocked or behind captcha); treat as needing re-verification.
- Ecuador fee: 320 USD on the page fetched, another excerpt said 460; unresolved.
- Costa Rica figures come from the tourism board (visitcostarica.com), not immigration.
- Thailand DTV fee null (only per-embassy fees confirmed).

- Wave 1 (2026-09-29) covered Europe (Portugal, Spain, Italy, Estonia, Croatia, Hungary), the Americas and the Caribbean/Africa records and added 11 records. Asia records (Thailand, Indonesia, Japan, Korea and others), Latvia, Czechia, Cyprus, Germany, Romania, Montenegro, Malta remain as before: the research runs for those were cut short and are still to do.
- Brazil rests on search excerpts of gov.br pages (blocked host); Hungary fee is inferred from the general permit fee; Italy income differs between consulates.

## Wave 1 field gaps still open (2026-09-29)
- portugal-d8-residence-visa.taxTreatment: no official page read states a tax treatment for D8
- portugal-d8-residence-visa.dependants.allowed: AIMA and visa portal pages fetched do not address family for this category
- portugal-d8-residence-visa.savingsAlternative: official pages do not state one (a 12x RMMG claim appeared only on private sites)
- portugal-temporary-stay-remote-work.duration.initialMonths: page says stay under a year; no single figure
- portugal-temporary-stay-remote-work.taxTreatment: not stated on official pages read
- portugal-temporary-stay-remote-work.dependants.allowed: not stated for this visa on pages read
- spain-international-teleworker.governmentFee.amount: fee varies by nationality and consulate; no single figure
- italy-digital-nomad-remote-worker-visa.taxTreatment: no consulate page read states tax treatment
- croatia-digital-nomad-temporary-stay.processingTime.text: MUP page and search results state no decision deadline
- hungary-white-card.taxTreatment: OIF factsheet silent; NAV page found was general foreign-citizen guidance, not scheme-specific
- hungary-white-card.governmentFee: White Card not listed separately on fee page; 110 EUR is inferred from general residence-permit fee
- brazil-vitem-xiv-digital-nomad.governmentFee.amount: fee varies by consulate/nationality, no single official figure
- brazil-vitem-xiv-digital-nomad.dependants: no readable official page (gov.br blocks automated access)
- brazil-vitem-xiv-digital-nomad.taxTreatment: not on any readable page
- argentina-nomada-digital-transitory-residence.dependants: fetched official pages silent; a search excerpt about family fees could not be tied to a page
- argentina-nomada-digital-transitory-residence.taxTreatment: not stated
- colombia-digital-nomad-visitor-visa.processingTime: not stated on pages read
- costarica-remote-workers-law-10008.processingTime: not stated; migracion.go.cr 403
- ecuador-visa-nomada.processingTime: not stated
- uruguay-hoja-identidad-provisoria-nomada.dependants/health/tax/processing: not stated
- panama-short-stay-remote-worker.dependants/tax: not stated; extension rule conflicts
- belize-work-where-you-vacation.taxTreatment/processingTime: not stated
- mexico.taxTreatment/healthInsurance: not stated; amounts vary by consulate
- peru.minIncome/fee/processing: no regulation found
- bahamas-beats.taxTreatment: FAQ silent; nothing new found
- bahamas-beats.minIncome: FAQ states no professional income threshold (financial proof only for students)
- barbados-welcome-stamp.healthInsurance: not mentioned on visitbarbados.org page (barbadoswelcomestamp.bb redirects to it)
- barbados-welcome-stamp.savingsAlternative: not mentioned
- bermuda-work-from-bermuda-one-year-certificate.taxTreatment/dependants/renewal: 2020 policy page silent
- bermuda-work-from-bermuda-one-year-certificate.minIncome.amount: policy states only 'sufficient means and/or continuous source of annual income'
- cabo-verde-nomadas-digitais.duration/minIncome/processingTime/taxTreatment/dependants: official e-portaldef page and English homepage do not state them; only secondary/search sources (not read) claim 6 months + 6 renewal, so left null; status stays unclear (online application 'Brevemente')
- kenya-digital-nomad-permit-class-n.minIncome.amount: eFNS infopack states no minimum; secondary sources conflict (24,000/36,000/55,000 USD) and were not used
- kenya-digital-nomad-permit-class-n.processingTime/dependants/healthInsurance/taxTreatment: eFNS infopack silent; immigration.go.ke work-permits page does not list Class N
- kenya-digital-nomad-permit-class-n.duration.initialMonths: 1 or 2 years, no single value
- mauritius-premium-visa.processingTime: not stated by EDB or residency.mu; secondary snippets not used
- mauritius-premium-visa.savingsAlternative: none stated
- south-africa-remote-work-visa.governmentFee.amount: DHA says 'applicable fee'; only consulate-specific C$32 known
- south-africa-remote-work-visa.dependants/healthInsurance/processingTime: DHA PDF silent
- montserrat-remote-workers-stamp: gov.ms notice omits income threshold; USD 70,000 from programme site only
- grenada-remote-employment-act-permit.processingTime: statute silent
- cayman-islands-global-citizen-certificate.processingTime/taxTreatment: regulations silent
- slovenia-digital-nomad-temporary-residence.minIncome.amount: gov.si gives a formula (2x average net salary), no euro figure; slovenia.si figure ambiguous
- slovenia-digital-nomad-temporary-residence.governmentFee/processingTime/taxTreatment/savingsAlternative: not stated on pages read
- albania-unique-permit-digital-mobile-workers.minIncome.amount/governmentFee: set by regulation/Council of Ministers' Decision, not read; e-Albania and mb.gov.al procedure pages unreadable
- albania-unique-permit-digital-mobile-workers.duration.maxRenewalsText/taxTreatment: not in Art. 68
- bulgaria-digital-nomad-long-term-residence.minIncome.amount: statute gives 50 minimum monthly wages; euro amount not on an official page read; D-visa fee (mfa.bg, blocked by bot manager) not verified
- bulgaria-digital-nomad-long-term-residence.dependants/taxTreatment/savingsAlternative: not found
- moldova-digital-nomad-right-of-residence.minIncome.amount: MDL amount not stated on pages read; governmentFee and taxTreatment null
- georgia-remotely-from-georgia: minIncome, fee, processing, whereToApply, dependants, insurance null; programme page unreachable; 1% small-business status not confirmed on rs.ge (JS page)
- serbia-digital-nomad-temporary-residence: all requirement fields null; implementing act criteria not found on official pages
- greece-digital-nomad-visa: mfa.gr and migration.gov.gr blocked (403); tax (50% new-resident break), official fee, processing, dependants, insurance unverified

### Omitted this wave
- Chile: no official SERMIG/ChileAtiende page showing a nomad or remote-work scheme found (Law 21.325 lists only general categories)
- El Salvador: official migracion.gob.sv pages list general temporary residence only; no nomad scheme found; rree.gob.sv 403
- Dominican Republic: no official DGM/MIREX/tourism page showing a nomad scheme found (migracion.gob.do 403)
- Seychelles: workation site 403/522; ics.gov.sc pages found list only Gainful Occupation and residence permits, no workation permit
- Saint Lucia Live It: stlucia.org pages 404; govt.lc non-immigrant visa page shows no nomad category; Live It seen only via search excerpt as a tourism extended-stay programme, not a permit
- St Kitts and Nevis: no official remote-worker scheme found; only work visa and CBI pages
- Jamaica: no official page found showing a nomad scheme; only secondary sites
- Namibia: mhaiss/mha.gov.na results show work visas/permits only, no nomad scheme
- Morocco: official diplomatie.ma/maroc.ma results show e-visa only, no nomad scheme
- Egypt: sis.gov.eg and egypt.gov.eg results show no nomad visa announcement
- Vietnam: evisa.gov.vn / xuatnhapcanh.gov.vn results show standard e-visa (max 90 days) only, no nomad scheme
- Cambodia: immigration.gov.kh / evisa.gov.kh results show standard visas only, no nomad scheme
- Armenia: official mfa.am and migration pages show temporary/permanent/special residency only, no nomad scheme found
- Poland: gov.pl visa pages show no digital nomad scheme; not recorded as none (no explicit official statement)
- Lithuania: migracija.lrv.lt / keliauk.urm.lt show D-visa generally, no nomad scheme found; not recorded as none

## Per-field gaps (raw agent logs)

### parts/p1-gaps.md
# p1 gaps (checked 2026-09-28)

## Null fields
- portugal-d8-residence-visa.minIncome.amount: not stated on the official page(s) fetched
- portugal-d8-residence-visa.duration.initialMonths: not stated on the official page(s) fetched
- portugal-d8-residence-visa.taxTreatment.text: not stated on the official page(s) fetched
- portugal-d8-residence-visa.dependants.allowed: not stated on the official page(s) fetched
- portugal-d8-residence-visa.healthInsurance.required: not stated on the official page(s) fetched
- portugal-temporary-stay-remote-work.minIncome.amount: not stated on the official page(s) fetched
- portugal-temporary-stay-remote-work.duration.initialMonths: not stated on the official page(s) fetched
- portugal-temporary-stay-remote-work.taxTreatment.text: not stated on the official page(s) fetched
- portugal-temporary-stay-remote-work.dependants.allowed: not stated on the official page(s) fetched
- portugal-temporary-stay-remote-work.healthInsurance.required: not stated on the official page(s) fetched
- spain-international-teleworker.governmentFee.amount: not stated on the official page(s) fetched
- spain-international-teleworker.taxTreatment.text: not stated on the official page(s) fetched
- italy-digital-nomad-remote-worker-visa.governmentFee.amount: not stated on the official page(s) fetched
- italy-digital-nomad-remote-worker-visa.processingTime.text: not stated on the official page(s) fetched
- italy-digital-nomad-remote-worker-visa.taxTreatment.text: not stated on the official page(s) fetched
- estonia-digital-nomad-visa.taxTreatment.text: not stated on the official page(s) fetched
- estonia-digital-nomad-visa.dependants.allowed: not stated on the official page(s) fetched
- croatia-digital-nomad-temporary-stay.processingTime.text: not stated on the official page(s) fetched
- croatia-digital-nomad-temporary-stay.taxTreatment.text: not stated on the official page(s) fetched
- hungary-white-card.governmentFee.amount: not stated on the official page(s) fetched
- hungary-white-card.taxTreatment.text: not stated on the official page(s) fetched
- latvia-remote-work-long-stay-visa.governmentFee.amount: not stated on the official page(s) fetched
- latvia-remote-work-long-stay-visa.processingTime.text: not stated on the official page(s) fetched
- latvia-remote-work-long-stay-visa.taxTreatment.text: not stated on the official page(s) fetched
- latvia-remote-work-long-stay-visa.dependants.allowed: not stated on the official page(s) fetched
- czechia-digital-nomad-program.minIncome.amount: not stated on the official page(s) fetched
- czechia-digital-nomad-program.duration.initialMonths: not stated on the official page(s) fetched
- czechia-digital-nomad-program.governmentFee.amount: not stated on the official page(s) fetched
- czechia-digital-nomad-program.taxTreatment.text: not stated on the official page(s) fetched
- czechia-digital-nomad-program.healthInsurance.required: not stated on the official page(s) fetched
- cyprus-digital-nomad-visa.minIncome.amount: not stated on the official page(s) fetched
- cyprus-digital-nomad-visa.duration.initialMonths: not stated on the official page(s) fetched
- cyprus-digital-nomad-visa.governmentFee.amount: not stated on the official page(s) fetched
- cyprus-digital-nomad-visa.governmentFee.text: not stated on the official page(s) fetched
- cyprus-digital-nomad-visa.processingTime.text: not stated on the official page(s) fetched
- cyprus-digital-nomad-visa.taxTreatment.text: not stated on the official page(s) fetched
- cyprus-digital-nomad-visa.dependants.allowed: not stated on the official page(s) fetched
- cyprus-digital-nomad-visa.healthInsurance.required: not stated on the official page(s) fetched
- germany-freelance-residence-permit.minIncome.amount: not stated on the official page(s) fetched
- germany-freelance-residence-permit.duration.initialMonths: not stated on the official page(s) fetched
- germany-freelance-residence-permit.governmentFee.amount: not stated on the official page(s) fetched
- germany-freelance-residence-permit.governmentFee.text: not stated on the official page(s) fetched
- germany-freelance-residence-permit.processingTime.text: not stated on the official page(s) fetched
- germany-freelance-residence-permit.taxTreatment.text: not stated on the official page(s) fetched
- germany-freelance-residence-permit.dependants.allowed: not stated on the official page(s) fetched
- germany-freelance-residence-permit.healthInsurance.required: not stated on the official page(s) fetched
- romania-digital-nomad-long-stay-visa.minIncome.amount: not stated on the official page(s) fetched
- romania-digital-nomad-long-stay-visa.duration.initialMonths: not stated on the official page(s) fetched
- romania-digital-nomad-long-stay-visa.governmentFee.amount: not stated on the official page(s) fetched
- romania-digital-nomad-long-stay-visa.processingTime.text: not stated on the official page(s) fetched
- romania-digital-nomad-long-stay-visa.taxTreatment.text: not stated on the official page(s) fetched
- romania-digital-nomad-long-stay-visa.dependants.allowed: not stated on the official page(s) fetched
- romania-digital-nomad-long-stay-visa.healthInsurance.required: not stated on the official page(s) fetched

## Failed / blocked pages
- https://www.mfa.gr/en/services/working-in-greece-as-a-digital-nomad/ : HTTP 403 (curl and WebFetch); Greece omitted, no record
- https://www.gov.cy/en/migration/... digital nomad announcement and gov.cy PDF scheme guide: HTTP 403 (curl and WebFetch); Cyprus emitted as unclear with no data
- Bulgaria: mfa.bg pages fetched contained no digital-nomad scheme text; news page blocked by bot check (Radware); Bulgaria omitted
- https://www.make-it-in-germany.com/... : bot-check captcha page; Germany used auswaertiges-amt and BAMF instead
- https://vistos.mne.gov.pt/.../temporary-stay/remote-work, vistos root (WebFetch 403), vm.ee digital-nomad slug 404, mae.ro/en/node/2054 connection reset, mzv.gov.cz New York nomad page 404
- Lithuania, Poland: only search excerpts seen, no primary page confirming absence or existence of a nomad scheme; omitted

## Notes
- Estonia 3,960 EUR/month is the teleworking row of the MFA subsistence table; not explicitly labelled a minimum income.
- Italy figures on the New York consulate page are labelled as of 2024; verify against a current page.
- Spain fee, Italy fee vary by consulate/nationality; not captured as a single figure.
- Czech: a search excerpt claimed an income threshold of CZK 60,530/month but the fetched pages did not state it, so it was not used.
- Germany 'none' status is inferred from the absence of a nomad scheme on the pages checked.
- Czech general zivno visa not verified; Estonia workinestonia.com is a state agency site (Enterprise Estonia), used as primary.


### parts/p2-gaps.md
# p2 gaps (checked 2026-09-28)

## Countries omitted (no verified official page)
- Albania: search returned only generic unique-permit forms; no digital-nomad category verified. Omitted.
- Serbia: welcometoserbia.gov.rs/temporary-residence lists no nomad basis but links "Digital nomads in Serbia"; that page not found (404 guess). Law on Foreigners reportedly recognises digital nomads via Government act (search summary only). Omitted.
- Georgia: "Remotely from Georgia" only seen via search snippets (geoconsul.gov.ge/en/news/16, COVID-era). Current status unverified. Omitted.
- Armenia: mfa.am/migration pages show no nomad scheme in search results; not verified as none. Omitted.
- Iceland: island.is permit-based-on-work page lists no remote-work category; search summary says long-term visa provision repealed; not confirmed on a page. Omitted.
- Norway: udi.no returned 403. Omitted.
- Seychelles: workcation.seychelles.travel 403; ics.gov.sc not fetched. Omitted.
- Namibia: no digital nomad scheme found on mha.gov.na results; not verified as none. Omitted.
- Egypt, Morocco: not researched (budget). Omitted.

## Null fields
- montenegro-digital-nomad-residence.minIncome.amount: page says only "financial means of support"
- montenegro-digital-nomad-residence.governmentFee: not on page
- montenegro-digital-nomad-residence.taxTreatment: not on page
- montenegro-digital-nomad-residence.savingsAlternative: not on page
- south-africa-remote-work-visa.duration.initialMonths: DHA PDF text not extractable; consulate page silent
- south-africa-remote-work-visa.governmentFee.amount: fee only shown as consulate-specific C$32 in text
- south-africa-remote-work-visa.processingTime: not stated
- south-africa-remote-work-visa.dependants/healthInsurance: not stated
- south-africa-remote-work-visa.savingsAlternative: not stated
- mauritius-premium-visa.minIncome.amount: no amount on pages retrieved
- mauritius-premium-visa.processingTime: not stated
- mauritius-premium-visa.savingsAlternative: not stated
- kenya-digital-nomad-permit-class-n.minIncome.amount: no minimum stated
- kenya-digital-nomad-permit-class-n.governmentFee.amount: two fees (200 processing + 1000/yr), in text
- kenya-digital-nomad-permit-class-n.processingTime/taxTreatment/dependants/healthInsurance/savingsAlternative: not stated
- kenya-digital-nomad-permit-class-n.duration.initialMonths: 1 or 2 years, not a single value
- cabo-verde-nomadas-digitais.minIncome.amount, duration, processingTime, taxTreatment, dependants, healthInsurance(insurance), savingsAlternative: not on page

## Failed pages
- https://www.island.is/en/long-term-visa-for-remote-work: 404
- https://www.gov.ge/en/page/remotely-from-georgia: 503
- https://www.dha.gov.za/index.php/immigration-services/digital-nomad-visa: 404
- https://www.gov.me/en/article/digital-nomads: 404
- https://www.seychelles.travel/en/discover/workation: 522; https://workcation.seychelles.travel/: 403 (x2)
- https://www.udi.no/en/want-to-apply/work-immigration/: 403
- https://www.geoconsul.gov.ge/en/news/16: timeout (x2)
- https://stopcov.ge/...remotely...: 503
- https://mha.gov.na/all-visa-general-information: 503
- https://welcometoserbia.gov.rs/digital-nomads: 404
- https://island.is/en/get-a-long-term-visa/supporting-documents: 404
- DHA Remote Work PDF: fetched but text not extractable (no pdftotext)


### parts/p3-gaps.md
# p3 gaps (checked 2026-09-28)

## Countries omitted (no verified official page)
- Vietnam: no official page found stating a nomad scheme or its absence; only secondary sites. Omitted.
- Cambodia: no official page found; secondary sources say none. Omitted.
- Oman: ROP visa-types page lists no nomad category but that is not an explicit statement; omitted.
- Bahrain: conflicting secondary sources, iaa.gov.bh unreachable. Omitted.
- Uzbekistan: no official source found. Omitted.
- UAE Abu Dhabi: not verified; only Dubai GDRFA record emitted.

## Failed pages
- https://evisa.imigrasi.go.id/ : 403 (WebFetch)
- https://www.workation.go.kr : ENOTFOUND
- https://www.moj.go.jp/isa/... and https://www.mofa.go.jp/... (Japan) : 403 Access Denied; embassy PDFs (chicago/boston.us.emb-japan.go.jp) also 403. Japan details come from search-result summaries of these official pages, not read directly.
- https://overseas.mofa.go.kr/... , www.immigration.go.kr , visa.go.kr, hikorea.go.kr : connection reset / unreachable. Korea read only via Seattle consulate page.
- https://dict.gov.ph/news-and-updates/19619 , officialgazette.gov.ph EO 86, pco.gov.ph EO PDF : 403/Cloudflare. Philippines from search summaries.
- https://www.thaievisa.go.th/ (JS app, no content), mfa.go.th DTV page 404, Checklist_DTV.pdf unreadable, canberra.thaiembassy.org connection reset
- https://u.ae virtual-working page : 404; used GDRFA page instead
- https://www.goturkiye.com/digitalnomad : 404; used digitalnomads.goturkiye.com
- ltr.boi.go.th main page not directly read; LTR income figure (USD 80,000) from search summary

## Null fields
- thailand-dtv.minIncome.amount: not stated on the official page(s) read
- thailand-dtv.minIncome.period: not stated on the official page(s) read
- thailand-dtv.governmentFee.amount: not stated on the official page(s) read
- thailand-dtv.governmentFee.currency: not stated on the official page(s) read
- thailand-dtv.taxTreatment.text: not stated on the official page(s) read
- thailand-dtv.healthInsurance.required: not stated on the official page(s) read
- thailand-ltr-work-from-thailand-professional.duration.initialMonths: not stated on the official page(s) read
- thailand-ltr-work-from-thailand-professional.duration.maxRenewalsText: not stated on the official page(s) read
- thailand-ltr-work-from-thailand-professional.governmentFee.amount: not stated on the official page(s) read
- thailand-ltr-work-from-thailand-professional.governmentFee.currency: not stated on the official page(s) read
- thailand-ltr-work-from-thailand-professional.governmentFee.text: not stated on the official page(s) read
- thailand-ltr-work-from-thailand-professional.processingTime.text: not stated on the official page(s) read
- thailand-ltr-work-from-thailand-professional.taxTreatment.text: not stated on the official page(s) read
- thailand-ltr-work-from-thailand-professional.dependants.allowed: not stated on the official page(s) read
- indonesia-e33g-remote-worker.savingsAlternative.amount: not stated on the official page(s) read
- indonesia-e33g-remote-worker.savingsAlternative.currency: not stated on the official page(s) read
- indonesia-e33g-remote-worker.savingsAlternative.text: not stated on the official page(s) read
- indonesia-e33g-remote-worker.taxTreatment.text: not stated on the official page(s) read
- indonesia-e33g-remote-worker.dependants.allowed: not stated on the official page(s) read
- indonesia-e33g-remote-worker.healthInsurance.required: not stated on the official page(s) read
- malaysia-de-rantau-nomad-pass.savingsAlternative.amount: not stated on the official page(s) read
- malaysia-de-rantau-nomad-pass.savingsAlternative.currency: not stated on the official page(s) read
- malaysia-de-rantau-nomad-pass.savingsAlternative.text: not stated on the official page(s) read
- south-korea-workation-f-1-d.minIncome.amount: not stated on the official page(s) read
- south-korea-workation-f-1-d.savingsAlternative.amount: not stated on the official page(s) read
- south-korea-workation-f-1-d.savingsAlternative.currency: not stated on the official page(s) read
- south-korea-workation-f-1-d.savingsAlternative.text: not stated on the official page(s) read
- south-korea-workation-f-1-d.governmentFee.amount: not stated on the official page(s) read
- south-korea-workation-f-1-d.governmentFee.currency: not stated on the official page(s) read
- south-korea-workation-f-1-d.taxTreatment.text: not stated on the official page(s) read
- japan-digital-nomad-designated-activities.savingsAlternative.amount: not stated on the official page(s) read
- japan-digital-nomad-designated-activities.savingsAlternative.currency: not stated on the official page(s) read
- japan-digital-nomad-designated-activities.savingsAlternative.text: not stated on the official page(s) read
- japan-digital-nomad-designated-activities.governmentFee.amount: not stated on the official page(s) read
- japan-digital-nomad-designated-activities.governmentFee.currency: not stated on the official page(s) read
- japan-digital-nomad-designated-activities.governmentFee.text: not stated on the official page(s) read
- japan-digital-nomad-designated-activities.processingTime.text: not stated on the official page(s) read
- taiwan-digital-nomad-visitor-visa.duration.initialMonths: not stated on the official page(s) read
- taiwan-digital-nomad-visitor-visa.duration.maxRenewalsText: not stated on the official page(s) read
- taiwan-digital-nomad-visitor-visa.governmentFee.amount: not stated on the official page(s) read
- taiwan-digital-nomad-visitor-visa.governmentFee.currency: not stated on the official page(s) read
- taiwan-digital-nomad-visitor-visa.processingTime.text: not stated on the official page(s) read
- taiwan-digital-nomad-visitor-visa.taxTreatment.text: not stated on the official page(s) read
- taiwan-digital-nomad-visitor-visa.dependants.allowed: not stated on the official page(s) read
- uae-dubai-virtual-work-residence.savingsAlternative.amount: not stated on the official page(s) read
- uae-dubai-virtual-work-residence.savingsAlternative.currency: not stated on the official page(s) read
- uae-dubai-virtual-work-residence.savingsAlternative.text: not stated on the official page(s) read
- uae-dubai-virtual-work-residence.taxTreatment.text: not stated on the official page(s) read
- sri-lanka-digital-nomad-visa.savingsAlternative.amount: not stated on the official page(s) read
- sri-lanka-digital-nomad-visa.savingsAlternative.currency: not stated on the official page(s) read
- sri-lanka-digital-nomad-visa.savingsAlternative.text: not stated on the official page(s) read
- sri-lanka-digital-nomad-visa.processingTime.text: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.minIncome.amount: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.minIncome.period: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.savingsAlternative.amount: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.savingsAlternative.currency: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.savingsAlternative.text: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.governmentFee.amount: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.governmentFee.currency: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.governmentFee.text: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.processingTime.text: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.taxTreatment.text: not stated on the official page(s) read
- kazakhstan-neo-nomad-b12-1.healthInsurance.required: not stated on the official page(s) read
- turkey-digital-nomad-visa.savingsAlternative.amount: not stated on the official page(s) read
- turkey-digital-nomad-visa.savingsAlternative.currency: not stated on the official page(s) read
- turkey-digital-nomad-visa.savingsAlternative.text: not stated on the official page(s) read
- turkey-digital-nomad-visa.duration.initialMonths: not stated on the official page(s) read
- turkey-digital-nomad-visa.duration.maxRenewalsText: not stated on the official page(s) read
- turkey-digital-nomad-visa.governmentFee.amount: not stated on the official page(s) read
- turkey-digital-nomad-visa.governmentFee.currency: not stated on the official page(s) read
- turkey-digital-nomad-visa.governmentFee.text: not stated on the official page(s) read
- turkey-digital-nomad-visa.processingTime.text: not stated on the official page(s) read
- turkey-digital-nomad-visa.taxTreatment.text: not stated on the official page(s) read
- turkey-digital-nomad-visa.dependants.allowed: not stated on the official page(s) read
- turkey-digital-nomad-visa.healthInsurance.required: not stated on the official page(s) read
- philippines-digital-nomad-visa.minIncome.amount: not stated on the official page(s) read
- philippines-digital-nomad-visa.minIncome.period: not stated on the official page(s) read
- philippines-digital-nomad-visa.savingsAlternative.amount: not stated on the official page(s) read
- philippines-digital-nomad-visa.savingsAlternative.currency: not stated on the official page(s) read
- philippines-digital-nomad-visa.savingsAlternative.text: not stated on the official page(s) read
- philippines-digital-nomad-visa.governmentFee.amount: not stated on the official page(s) read
- philippines-digital-nomad-visa.governmentFee.currency: not stated on the official page(s) read
- philippines-digital-nomad-visa.governmentFee.text: not stated on the official page(s) read
- philippines-digital-nomad-visa.processingTime.text: not stated on the official page(s) read
- philippines-digital-nomad-visa.taxTreatment.text: not stated on the official page(s) read
- philippines-digital-nomad-visa.dependants.allowed: not stated on the official page(s) read


### parts/p4-gaps.md
# p4 gaps

- colombia-digital-nomad-visitor-visa.minIncome: null/unverified on fetched official page
- colombia-digital-nomad-visitor-visa.savingsAlternative: null/unverified on fetched official page
- colombia-digital-nomad-visitor-visa.processingTime: null/unverified on fetched official page
- colombia-digital-nomad-visitor-visa.taxTreatment: null/unverified on fetched official page
- costarica-remote-workers-law-10008.savingsAlternative: null/unverified on fetched official page
- costarica-remote-workers-law-10008.duration: null/unverified on fetched official page
- costarica-remote-workers-law-10008.processingTime: null/unverified on fetched official page
- costarica-remote-workers-law-10008.taxTreatment: null/unverified on fetched official page
- costarica-remote-workers-law-10008.healthInsurance: null/unverified on fetched official page
- brazil-vitem-xiv-digital-nomad.governmentFee: null/unverified on fetched official page
- brazil-vitem-xiv-digital-nomad.processingTime: null/unverified on fetched official page
- brazil-vitem-xiv-digital-nomad.taxTreatment: null/unverified on fetched official page
- brazil-vitem-xiv-digital-nomad.dependants: null/unverified on fetched official page
- brazil-vitem-xiv-digital-nomad.healthInsurance: null/unverified on fetched official page
- argentina-nomada-digital-transitory-residence.minIncome: null/unverified on fetched official page
- argentina-nomada-digital-transitory-residence.savingsAlternative: null/unverified on fetched official page
- argentina-nomada-digital-transitory-residence.processingTime: null/unverified on fetched official page
- argentina-nomada-digital-transitory-residence.taxTreatment: null/unverified on fetched official page
- argentina-nomada-digital-transitory-residence.dependants: null/unverified on fetched official page
- argentina-nomada-digital-transitory-residence.healthInsurance: null/unverified on fetched official page
- ecuador-visa-nomada.minIncome: null/unverified on fetched official page
- ecuador-visa-nomada.processingTime: null/unverified on fetched official page
- ecuador-visa-nomada.taxTreatment: null/unverified on fetched official page
- uruguay-hoja-identidad-provisoria-nomada.minIncome: null/unverified on fetched official page
- uruguay-hoja-identidad-provisoria-nomada.savingsAlternative: null/unverified on fetched official page
- uruguay-hoja-identidad-provisoria-nomada.processingTime: null/unverified on fetched official page
- uruguay-hoja-identidad-provisoria-nomada.taxTreatment: null/unverified on fetched official page
- uruguay-hoja-identidad-provisoria-nomada.dependants: null/unverified on fetched official page
- uruguay-hoja-identidad-provisoria-nomada.healthInsurance: null/unverified on fetched official page
- belize-work-where-you-vacation.savingsAlternative: null/unverified on fetched official page
- belize-work-where-you-vacation.processingTime: null/unverified on fetched official page
- belize-work-where-you-vacation.taxTreatment: null/unverified on fetched official page
- barbados-welcome-stamp.savingsAlternative: null/unverified on fetched official page
- barbados-welcome-stamp.taxTreatment: null/unverified on fetched official page
- barbados-welcome-stamp.healthInsurance: null/unverified on fetched official page
- bermuda-work-from-bermuda-one-year-certificate.minIncome: null/unverified on fetched official page
- bermuda-work-from-bermuda-one-year-certificate.savingsAlternative: null/unverified on fetched official page
- bermuda-work-from-bermuda-one-year-certificate.taxTreatment: null/unverified on fetched official page
- bermuda-work-from-bermuda-one-year-certificate.dependants: null/unverified on fetched official page
- panama-short-stay-remote-worker.minIncome: null/unverified on fetched official page
- panama-short-stay-remote-worker.savingsAlternative: null/unverified on fetched official page
- panama-short-stay-remote-worker.duration: null/unverified on fetched official page
- panama-short-stay-remote-worker.governmentFee: null/unverified on fetched official page
- panama-short-stay-remote-worker.processingTime: null/unverified on fetched official page
- panama-short-stay-remote-worker.taxTreatment: null/unverified on fetched official page
- panama-short-stay-remote-worker.dependants: null/unverified on fetched official page
- panama-short-stay-remote-worker.healthInsurance: null/unverified on fetched official page

## Countries omitted (no verified official page)
- Mexico: no nomad scheme page verified; no fetch made of INM/SRE.
- Chile, Peru: not researched (no official page found in budget).
- El Salvador: search of official domains found no nomad visa; not verified as none.
- Dominican Republic: search of migracion.gob.do/mirex found no nomad visa page; not verified.
- Bahamas (BEATS): immigration.gov.bs entry-requirements page lists no BEATS; portal.immigration.gov.bs DNS failed; 2020 press-release PDF unreadable. Status unverified.
- Cayman Islands (Global Citizen Certificate): regulations exist at legislation.gov.ky but no fee/income read; www.immigration.gov.ky DNS failed; gov.ky press release 404.

## Failed pages
- https://www.cancilleria.gov.co/en/visa-digital-nomad: 404
- https://www.migracion.go.cr/...Trabajadores-Remotos.aspx: 403; https://migracion.go.cr/nomadas-digitales/: 403
- https://www.gov.bm/work-bermuda-certificate: 404
- https://immigration.gov.bs/beats/: 404; https://portal.immigration.gov.bs/: ENOTFOUND
- https://www.immigration.gov.ky/global-citizen-certificate: ENOTFOUND; gov.ky press release: 404
- https://www.migracion.gob.pa/inicio/short-stay-remote-workers: 404; requirements PDF unreadable
- gov.br/mre Lisboa and Bogota VITEM XIV pages: captcha; https://immigration.gov.bz/permits/work-permit-style pages: captcha not hit, but no nomad permit listed
- Bahamas BEATS PDF: unreadable


### parts/p5-gaps.md
# p5 gaps

## Not emitted (no official page verified)
- Grenada: official gov.gd search found no digital nomad page; omitted, not confirmed none.
- Saint Lucia (Live It): stlucia.org press page returned 307/redirect; no official terms verified.
- Jamaica, Saint Vincent, Trinidad and Tobago, Turks and Caicos, Anguilla, St Kitts and Nevis: no official scheme page reached. gov.kn work-visa page mentions no remote scheme (not proof of none). Anguilla evisa.gov.ai 503, gov.ai visa page 404.
- Bonaire / Sint Maarten: not searched (budget).

## Null fields
- antigua-and-barbuda-nomad-digital-residence.minIncome/savings/fee/processing/tax/dependants/insurance: programme closed, detail pages unavailable
- dominica-work-in-nature-extended-stay.taxTreatment: official pages fetched say nothing
- curacao-at-home-in-curacao.minIncome.amount: no threshold stated; savingsAlternative: none stated
- aruba-one-happy-workation.processingTime/taxTreatment/dependants: not stated; not a permit
- montserrat-remote-workers-stamp.taxTreatment: not on pages fetched (gov.ms failed)
- barbados-welcome-stamp.healthInsurance: not stated on pages fetched; savingsAlternative.amount: none
- bahamas-beats.minIncome/taxTreatment: not stated on FAQ

## Failed pages
- https://ab.gov.ag/pdf/Discontinuation_of_the_NDR_prg.pdf: 404
- https://nomad.gov.ag/ui/: 503
- https://www.gov.ms/2021/01/29/applications-are-now-open-for-the-12-month-montserrat-remote-workers-stamp/: 503
- https://gov.ai/service/immigration--labour/immigration--labour-visas--travel: 404
- https://evisa.gov.ai/: 503
- https://www.stlucia.org/en_UK/press/dont-just-visit-live-it-saint-lucia-launches-immersive-extended-stay-program/: 404 (first search-result URL), visitaruba page 307
- https://www.immigration.gov.bs/.../BMOTA-BEATS-_Press_Release-_FINAL_10.29-converted.pdf: unreadable PDF


## Audit 2026-09-29 (independent audit of wave 1)
- Serbia: removed from the tracker. Law on Foreigners Art. 40(4) only allows the Government to regulate nomad residence by act; no criteria, fee or procedure exist on official pages, so the record held no usable field. Re-add when a regulation is published.
- Peru: removed from the tracker. Decreto Legislativo 1582 created the 'Nomada Digital' status; the Migraciones note of 20 Nov 2023 says it is granted only once regulated and in the TUPA; no regulation, income, fee or procedure found. Re-add when operational.
- Georgia: kept with status none (past-tense state programme; visa-free one-year stay is not a nomad permit).
- Cayman Islands: kept with status closed (regulation expiry 30 Nov 2024 unless extended; no extension read).
- Greece: the mfa.gr digital nomad page (browser read) states no figures and points to workfromgreece.gr; figures are sourced to workfromgreece.gr plus EY Greece and taxheaven.gr summaries of Law 4825/2021 art. 11. Primary law text still to read. 50% tax break unverified and likely not automatic.
- Bulgaria: fee, processing and insurance fields come from the general long-term residence service page, not a nomad-specific page; fees are quoted in leva and may now be in euro.
- Moldova: 90-day processing figure removed (not on the pages read).
- Brazil (audit): the four gov.br pages (Lisbon, Sofia, Helsinki, Lima) were read in full in a headed browser on 2026-09-29; income, insurance, EUR 100 fee, 90-day police registration and one renewal are confirmed. The "search excerpt" wording inside older Brazil field text is superseded. Dependants and tax remain unstated on those pages.

## Wave 2 (2026-09-29): Asia and Europe
Still null or unverified after the wave 2 runs (reason in brackets):
- Thailand DTV: government fee, tax, insurance (thaievisa.go.th is a script-only page; only per-embassy fees exist).
- Japan: fee, processing (embassy PDFs and MOFA returned 403). South Korea: fee, tax. Taiwan: duration, dependants, fee (ndc.gov.tw blocked). Philippines: everything (no official implementing guidelines found). Sri Lanka: processing (PDF silent). Indonesia: dependants, insurance, tax. Turkey: duration, dependants. Kazakhstan: tax; fee only from a private site.
- Cyprus: fee, processing, insurance; other fields from search excerpts of gov.cy (403). Czechia: income (no official amount), tax. Germany: status none still inferred (Make it in Germany and BAMF blocked); visa fee at missions. Romania: duration, fee, dependants, insurance, tax (mae.ro 503). Latvia: processing, tax, dependants, renewals. Montenegro: income, fee, tax. Slovenia: income amount (base ambiguous), fee, processing. Bulgaria: tax. Croatia: processing (no official page). Greece: insurance. Portugal: D8 dependants, temporary-stay duration and dependants.
- New schemes checked and NOT found on an official page: Poland, Lithuania, Armenia, Norway, Vietnam, Cambodia, Uzbekistan, Oman, Bahrain. Iceland has a remote-worker page on utl.is that could not be read. Serbia: enabling clause only.
