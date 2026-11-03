# Zenodo upload — Theyyam Register: An Inventory of Theyyam, the Intangible Cultural Heritage of North Malabar (0.1.0-pre)

These are the values to enter on Zenodo's **New upload** form, field by field, in the order Zenodo shows them. If you publish through the Zenodo–GitHub integration instead, the `.zenodo.json` file in this package fills in the same values automatically.

---

## Files

Upload **`theyyam-wikidata-v0.1.0-pre.zip`**. You can also upload `data/theyyam-wikidata.csv` and `datapackage.json` separately, so people can preview the CSV on Zenodo without unzipping.

## Basic information

| Field | Value |
|---|---|
| **Digital Object Identifier** | If you already reserved **10.5281/zenodo.23895185** for this record, keep it. Otherwise choose "No" and Zenodo will mint one when you publish. |
| **Resource type** | Dataset |
| **Title** | Theyyam Register: An Inventory of Theyyam, the Intangible Cultural Heritage of North Malabar |
| **Publication date** | 2026-11-03 |
| **Creators** | 1. Karingamadathil, Manoj — Role: Data curator (add ORCID / affiliation if available) <br> 2. Muzhappilangad, Shagil — Role: Data curator (add ORCID / affiliation if available) |
| **Description** | Paste the text under *Description* below. |
| **Licenses** | Creative Commons Zero v1.0 Universal (CC0 1.0) |
| **Copyright** | Leave blank (CC0 waives it). |

### Description

Zenodo's editor accepts formatted text. Paste the following (an HTML version is in `zenodo-description.html`):

> A list of 102 Theyyam deity forms of North Malabar that have a Wikidata item, with their Wikidata ID, Malayalam name and English name.
>
> **Pre-release.** This is the first dataset from the Theyyam Register, a larger list of about 365 theyyams with their performing communities, kavus and sources. This first release covers only the theyyams that already have a Wikidata item, so each row can be checked against Wikidata.
>
> Published as part of the **Wiki Loves Theyyam** initiative.
>
> **Contents** (Frictionless Tabular Data Package):
> - `data/theyyam-wikidata.csv`: 102 rows, UTF-8. Fields: `wikidata_id`, `name_ml` (Malayalam name), `name_en` (English name).
> - `datapackage.json`: metadata, licence, sources and table schema.
> - `README.md`, `CITATION.cff`, `LICENSE.md`, `CHANGELOG.md`.
>
> **Sources:** Malayalam Wikipedia (list of theyyams, തെയ്യങ്ങളുടെ പട്ടിക, and category വർഗ്ഗം:തെയ്യങ്ങൾ), English Wikipedia (Category:Theyyam) and Wikidata. English names cross-checked against Kerala Tourism, theyyamcalendar.com and TheyyamWiki.
>
> **Known issues:** a few Wikidata items are possible duplicates (e.g. two items for Poomaruthan), cover a group of theyyams, or may describe rituals rather than single theyyams. These are listed in the README.

## Recommended information

| Field | Value |
|---|---|
| **Contributors** | Wiki Loves Theyyam — Role: Sponsor (or Other). Optional. |
| **Keywords and subjects** | Theyyam · തെയ്യം · Wiki Loves Theyyam · Wikidata · Kerala · North Malabar · Malayalam · ritual art · intangible cultural heritage · Frictionless Data Package |
| **Languages** | Malayalam, English |
| **Dates** | Optional: *Collected* 2026-11-02 / 2026-11-03 |
| **Version** | 0.1.0-pre |
| **Publisher** | Zenodo (default) |

## Related works

| Relation | Identifier | Scheme | Resource type |
|---|---|---|---|
| Is supplemented by | https://github.com/opendatakerala/theyyam-register | URL | Software / Other |
| Is derived from | https://ml.wikipedia.org/wiki/തെയ്യങ്ങളുടെ_പട്ടിക | URL | Other |
| Is derived from | https://en.wikipedia.org/wiki/Category:Theyyam | URL | Other |
| References | https://www.wikidata.org/wiki/Q1639582 | URL | Dataset |

## Additional notes

> Pre-release (0.1.0-pre). Prepared by Manoj Karingamadathil and Shagil Muzhappilangad for the Wiki Loves Theyyam initiative. Corrections: https://github.com/opendatakerala/theyyam-register/issues

## Communities

Optional: submit the record to a Zenodo community for Wiki Loves Theyyam or Open Data Kerala, if one exists or you create one.

---

## Before you press Publish

- [ ] The creators' names are spelled as you want them cited (Zenodo citations use *Family, Given*).
- [ ] The DOI shown on the form matches the one in `README.md`, `CITATION.cff`, `LICENSE.md` and `datapackage.json`. If Zenodo gives a different DOI, update those files and re-upload. A published Zenodo record can't change its files without a new version.
- [ ] Access is **Open**.
- [ ] After publishing, add the Zenodo DOI badge to the GitHub README.

### Releasing later versions

Use **New version** on this record for 0.1.0, the full register and later releases. Zenodo then gives each version its own DOI, plus one "concept" DOI that always resolves to the latest version. Cite the concept DOI when you mean the dataset in general, and a version DOI when you mean the exact files.
