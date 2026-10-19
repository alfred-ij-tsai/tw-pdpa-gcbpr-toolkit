# Taiwan Personal Data Protection Act Compliance Toolkit — English Edition

**Mapped to the Global CBPR System Program Requirements (Chinese Taipei, Annex B)**

Version 1.4-EN · Author: I Jung (Alfred) Tsai · Licence: CC BY-NC-SA 4.0

**➜ [Open the toolkit](https://alfred-ij-tsai.github.io/tw-pdpa-gcbpr-toolkit/en/)**　·　[Mandarin edition 繁體中文版](https://alfred-ij-tsai.github.io/tw-pdpa-gcbpr-toolkit/)　·　[Repository](https://github.com/alfred-ij-tsai/tw-pdpa-gcbpr-toolkit)

---

## What this is

A working toolkit for day-to-day compliance with Taiwan's Personal Data Protection Act (PDPA), organised around three practical situations rather than around the structure of the statute:

| Path | Situation | Open |
|---|---|---|
| A | Day-to-day compliance across the personal data lifecycle | `table-03.html` |
| B | A data subject has made a request | `dsar.html` |
| C | Personal data has been stolen, disclosed, altered, damaged or lost | `incident.html` |

Every obligation is also mapped to the Global CBPR System Program Requirements, as set out in the Annex B Enforcement Map for Chinese Taipei. That column is a supplementary reference for organisations with cross-border needs or preparing for certification; it does not affect how domestic obligations are assessed.

## Files

| File | Contents |
|---|---|
| `index.html` | Entry point |
| `table-02.html` | Sources relied on, a PDPA-to-Global-CBPR terminology map, an unofficial bilingual translation of the Executive Yuan Directions, a catalogue of statute-level special laws, and an index of sector-specific regulations |
| `table-03.html` | Personal Data Lifecycle Compliance Table — 39 obligations across seven stages |
| `table-04.html` | Data Subject Access Request Table — 26 obligations: procedural foundations, the five rights, and record-keeping |
| `table-05.html` | Personal Data Incident Table — 18 obligations: the six-stage process, plus civil liability to data subjects |
| `dsar.html` | Path B draft generator |
| `incident.html` | Path C draft generator |

Each file is a single self-contained HTML document with the CSS and JavaScript embedded. There is no build step, no dependency and no server: open the file in a browser, or serve the folder statically. Nothing entered into the generators leaves the browser.

## Why map to the Global CBPR System

**Think of it as a privacy passport.** Certify once, and that certification is recognised across the member economies, instead of rebuilding the compliance argument for every market.

Chinese Taipei is a **founding member** of the Global CBPR Forum. The National Development Council serves as the coordinating body, and the Institute for Information Industry is the recognised Accountability Agent. For organisations in Taiwan seeking international trust for cross-border data flows, the Global CBPR System is an established route that is already in place.

There is also a practical reason for choosing it as the mapping baseline: **the Annex B Enforcement Map is a public document**. That allows this toolkit to quote its questions in full and to be released under an open licence, so that anyone may use, adapt and redistribute it.

The core of this toolkit remains **day-to-day compliance with Taiwan's PDPA**. The Global CBPR column is a supplementary reference for organisations with cross-border needs or preparing for certification; it does not alter how domestic obligations are assessed.

## Version, scope and limitations

| | |
|---|---|
| **Toolkit version** | v1.4-EN (2026). Scope limited to instruments having official English translations. Version history is on the GitHub repository. |
| **Personal Data Protection Act** | Provisions in force, as translated in the official English version amended 31 May 2023. The amendments promulgated on 11 November 2025 are not yet in force; their enforcement date is to be set by the Executive Yuan. Where those amendments are relevant, they are separately flagged and quoted from the official English version dated 11 November 2025. |
| **Enforcement Rules** | Official English version, amended 2 March 2016. |
| **Specific purposes and categories** | The specific purpose and the classification of personal information of the Personal Information Protection Act, official English version, amended 1 October 2012. Note that this instrument, and the Global CBPR Annex B Enforcement Map, both use the older rendering "Personal Information Protection Act"; the current official translation of the Act itself uses "Personal Data Protection Act". |
| **Executive Yuan Directions** | Directions for the Executive Yuan and Its Subordinate Agencies on Liaison Operations for the Implementation of Personal Data Protection (amended 7 January 2025). **No official English translation exists**; the translation in this toolkit is unofficial. |
| **Mapping baseline** | Global CBPR System Program Requirements Enforcement Map for Chinese Taipei (Annex B). |
| **Reporting to the competent authority** | `table-05.html` carries one row that the Mandarin edition does not: PDPA Article 12, Paragraphs 2 to 4, the obligation to report to the competent authority, as promulgated on 11 November 2025. It is marked **NOT YET IN FORCE** wherever it appears, and its enforcement date is to be set by the Executive Yuan. It is included here because the reporting obligation is among the first things a reader outside Taiwan will look for, and its absence would be harder to interpret than its presence. |
| **Special laws and sector regulations** | Statutes that prevail over the PDPA under the proviso to its Article 1 are catalogued in `table-02.html`, Part D; sector-specific regulations made under its Article 27, Paragraph 2 are indexed in Part E. **Both are non-exhaustive**, the effects described in Part D are the author's summaries rather than quotations, and no statutory text from either layer is reproduced anywhere in this toolkit. |
| **Who this covers** | Non-government agencies. The security and maintenance obligations of government agencies fall under Article 18 of the PDPA and are further governed by the Freedom of Government Information Act, the Archives Act and the Administrative Procedure Act; they are outside the scope of this toolkit. Only provisions that apply to non-government agencies are quoted, and they are quoted verbatim; where a provision also addresses government agencies, the parts that concern government agencies only do not apply. |
| **Calculating periods** | All dates shown in the generated drafts are the raw expiry dates calculated by counting days or hours. They do not account for postponement where the final day falls on a holiday. Confirm the actual final day under Article 48 of the Administrative Procedure Act against the official working calendar for the year in question. |

## Changes in v1.4-EN (October 2026)

This edition is checked against the provisions currently in force. The PDPA amendments promulgated on 11 November 2025 and the draft regulations pre-announced by the PDPC Preparatory Office are not incorporated.

- **Corrected.** The means and the required content of a notification under Article 12 are both in Enforcement Rules Article 22 (Paragraphs 1 and 2). Earlier versions cited the content requirement as Article 23, which concerns a different matter.
- **Corrected.** The erasure rows no longer present irrecoverability as a statutory requirement. Enforcement Rules Article 6 defines deleting as erasing the data from the personal data file; an irrecoverable method is now given as recommended practice.
- **Added** to `table-03.html`: Article 2 (definitions, with Enforcement Rules Articles 2, 3 and 5) and Article 51 (exclusions and extraterritorial reach, with a National Development Council interpretation on business CCTV); Article 8, Paragraph 2 (when notice may be waived); further Enforcement Rules provisions defining the terms used in Articles 6 and 19; and a note listing the cross-border transfer restrictions currently in force (three issued under Article 21, and one National Communications Commission order issued under the former Computer-Processed Personal Data Protection Act that remains in effect), together with two prior-approval regimes that work differently: Article 15 of the Human Biobank Management Act and Article 18 of the FSC regulations on outsourcing by financial institutions.
- **Added** to the Article 12 rows: the Ministry of Justice interpretation that confirming liability is not a precondition of notification.
- **Added** to `table-05.html` and `incident.html`: Part VII, civil liability to data subjects under Articles 29 to 31.
- **Revised** in `incident.html`: the guidance on Article 12 now explains that "clarified" refers to the facts of the infringement and does not require the organisation first to confirm its own liability, citing the Ministry of Justice interpretation.
- **Corrected.** Enforcement Rules Article 8 is now quoted in full as in the official translation; earlier versions merged Article 7 into it and omitted "prescribed under paragraph 1".
- **Corrected.** Article 8, Paragraph 1 and Article 12 are now quoted as in the official translation rather than rewritten to cover non-government agencies only. Every PDPA quotation in this edition has been checked word for word against the official English translation as amended on 31 May 2023; Article 2 now also follows its subparagraph numbering and punctuation.
- **Corrected.** Statute fields that carried an editorial gloss or summary now quote the provision itself: the Enforcement Rules Article 12 items in `table-04.html` and `table-05.html`, the secure-transmission row (`copy-02`, now Article 27, Paragraph 1) and the coordination row (`coordinate-01`, now Article 22, Paragraph 1). Glosses have moved to the notes. The two rows based on Annex 1 to the Directions keep their description and now link to the translation in `table-02.html`.
- **Layout.** Per-row correction notes have moved to a collapsed version history at the foot of each table; Enforcement Rules provisions and notes are collapsed by default and open automatically when a search term matches them; the preliminary-analysis warnings are collapsed under a red heading; and in `table-03.html` the selection box now sits to the left of each row.
- **Added** to Part D1 and the cross-border transfer note: Article 15 of the Human Biobank Management Act, which makes cross-border transfer of biobank data subject to approval.

Notes in this edition rely on interpretations and announcements issued by administrative authorities; court judgments are not included.

## Disclaimer

This toolkit is a compliance reference and **does not constitute legal advice**. Provisions should be checked against the versions in force in the [Laws & Regulations Database](https://law.moj.gov.tw/ENG/). Where the English and Mandarin versions differ, the Mandarin version governs. The generated drafts are working documents; consult a qualified lawyer on any specific matter.

## Licence

Released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International licence](https://creativecommons.org/licenses/by-nc-sa/4.0/). You are free to share and adapt this work, provided you give appropriate credit, do not use it commercially, and distribute your contributions under the same licence.

## Author

I Jung (Alfred) Tsai — attorney-at-law, Taiwan
[LinkedIn](https://www.linkedin.com/in/ijungtsai) · [Threads](https://www.threads.com/@irongtsay)
