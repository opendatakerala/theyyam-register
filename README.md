# Theyyam Register: An Inventory of Theyyam, the Intangible Cultural Heritage of North Malabar

തെയ്യം രജിസ്റ്റർ: ഉത്തര മലബാറിന്റെ അമൂർത്ത സാംസ്കാരിക പൈതൃകമായ തെയ്യങ്ങളുടെ പട്ടിക

**Version 0.1.0-pre (pre-release) · 3 November 2026 · Licence: CC0 1.0 · DOI: [10.5281/zenodo.23895185](https://doi.org/10.5281/zenodo.23895185)**

> A list of 102 Theyyam deity forms of North Malabar that have a Wikidata item, with their Wikidata ID, Malayalam name and English name.

Published as part of the **Wiki Loves Theyyam** initiative.

Prepared by: Manoj Karingamadathil & Shagil Muzhappilangad
Repository: https://github.com/opendatakerala/theyyam-register
Corrections: https://github.com/opendatakerala/theyyam-register/issues

---

This is a **pre-release**. It is the first dataset from the Theyyam Register, a larger list of about 365 theyyams with their performing communities, kavus and sources, which will follow. This first release covers only the theyyams that already have a Wikidata item, so each row can be checked against Wikidata.

## Files

| File | Contents |
|---|---|
| `datapackage.json` | [Frictionless Data Package](https://specs.frictionlessdata.io/tabular-data-package/) descriptor: metadata, licence, sources and the table schema. |
| `data/theyyam-wikidata.csv` | The data: 102 rows, UTF-8, comma-separated, sorted by English name. |

## Fields

| Field | Title | Description |
|---|---|---|
| `wikidata_id` | Wikidata ID | Wikidata item ID (`Q…`). Unique; the primary key. Open as `https://www.wikidata.org/wiki/<id>`. |
| `name_ml` | Malayalam name | The theyyam's name in Malayalam script. |
| `name_en` | English name | A romanised English name. Spellings vary widely between sources; this is one common form. |

## Sources

Names and Wikidata IDs were compiled from:

- Malayalam Wikipedia – [തെയ്യങ്ങളുടെ പട്ടിക](https://ml.wikipedia.org/wiki/തെയ്യങ്ങളുടെ_പട്ടിക), the list of theyyams
- Malayalam Wikipedia – articles in [വർഗ്ഗം:തെയ്യങ്ങൾ](https://ml.wikipedia.org/wiki/വർഗ്ഗം:തെയ്യങ്ങൾ)
- English Wikipedia – articles in [Category:Theyyam](https://en.wikipedia.org/wiki/Category:Theyyam)
- Wikidata – items linked to those articles
- English names cross-checked against Kerala Tourism, theyyamcalendar.com and TheyyamWiki

Overview pages that describe theyyam in general were left out. These are *Theyyam*, *Mappila Theyyam*, *ഭഗവതി തെയ്യം* and the list page itself.

## Known issues

These are items to resolve on Wikidata before the full release:

- **Possible duplicates.** Two Wikidata items exist for Poomaruthan: Q20581714 (*പൂമാരുതൻ തെയ്യം*) and Q20581703 (*പൂമാരുതൻ*). Q20581703's Malayalam article is marked for merging.
- **Related items.** Angadaivam (Q13109807), Angakkaran (Q16133620) and *Angakkaranum Pappooranum* (Q13109813) are three items for closely related theyyams. Kundora Chamundi (Q13111304) and Kundadi Chamundi (Q13111301) are probably the same theyyam under two names.
- **Group items.** Q16136267 (*മാരിത്തെയ്യങ്ങൾ*, Mari Theyyangal) covers a group of theyyams rather than one. Q20582865 (*മുക്രിത്തെയ്യം*, Mukri Theyyam) covers the Mukri figures of Mappila Theyyam.
- **Uncertain status.** Q13113612 (ബലിക്കള), Q31704341 (ബപ്പിടൽ), Q31704318 (മഞ്ഞടുക്കം) and Q20574367 (ഉച്ചാരതെയ്യം) are filed under theyyams on Malayalam Wikipedia, but may describe rituals or festivals rather than single theyyams.
- **Coverage.** Sources speak of about 400–456 theyyams; only about a quarter have a Wikidata item yet.

## Licence

To the extent possible under law, the compilers have dedicated this dataset to the public domain under **[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)**. You may copy, change and redistribute it, including commercially, without asking. Wikidata uses the same terms.

## How to cite

> Karingamadathil, M., & Muzhappilangad, S. (2026). *Theyyam Register: An Inventory of Theyyam, the Intangible Cultural Heritage of North Malabar* (version 0.1.0-pre) [Data set]. Wiki Loves Theyyam. Zenodo. https://doi.org/10.5281/zenodo.23895185
