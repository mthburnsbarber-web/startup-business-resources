# Omission research audit — October 29, 2026

The startup directory now contains **640 resource entries: 150 original and 490 supplemental**. This update adds **489 entries beyond the previous 151-entry version**, which already included Z Fellows. Counts describe records, not unique companies, cash grants or open applications.

## What was reviewed

| Source set | Coverage |
| --- | --- |
| Historical supplemental resource list dated October 22 | All 61 groups reconciled; [row-by-row details](HISTORICAL-RECONCILIATION.md) |
| [StartupCreds](https://www.startupcreds.com/programs) | All 550 discovery records screened; 499 new source URLs retrieved and compared with the original list |
| [AWS Activate offers](https://startups.aws.com/offers) | All 89 distinct offer URLs in the retrieved public catalog reviewed; repeated cards and overlapping programs consolidated |
| [Onward Scout accelerators](https://onwardscout.com/opportunities/accelerators) and [fellowships](https://onwardscout.com/opportunities/fellowships) | All three pages of each catalog reviewed, covering 102 records |
| Targeted official-source research | 103 provider, program, grant, competition and historical-tool sources |

These sets overlap. Their totals must not be added together as a count of unique programs. Third-party catalogs supplied leads; program descriptions, conditions and inclusion decisions used official provider pages, official partner catalogs and organizer-hosted competition pages. A small number of restricted pages are identified as such; an HTTP response or indexed page does not prove open intake.

## Reconciliation results

| Decision across discovery records | Records |
| --- | --- |
| Unverified | 61 |
| Added | 490 |
| Not added | 74 |
| Already covered | 172 |
| Outside startup scope | 47 |

[Every discovery record and decision](data/research-audit.csv) · [Source evidence for every supplemental entry](data/program-evidence.csv) · [HTTP checks](data/link-checks.csv)

## Material distinctions

- Founder fellowships, equity investment, grant competitions, software credits, paid offers and ordinary founder tools have separate categories.
- Credits tied to paid spend, partner membership, funding stage or geography are not described as unconditional cash grants.
- Vapi’s page said applications were on hold. The Coach K page listed October 27 and the 500 Global page listed October 11, both before this review. These are flagged in their entries.
- Z Fellows is ADD01. Original IDs and names are preserved, including legacy tracks; duplicate discovery links do not create duplicate entries.
- Databricks’ platform program is separate from the original Neon database route. The general ClickHouse offer is separate from the original Y Combinator route. Pega/Launchpad credit tiers are consolidated.
- MazeHQ’s AWS security offer is identified separately from Maze design-research software. Tiger Data is identified as the current Timescale brand.
- OpenAI’s direct page blocked automated access; its entry is an official resource hub with current benefits unverified. Other restricted or thinly rendered sources retain explicit limits in the evidence and link checks.
- Some historical tool names identify ordinary products rather than startup programs. Their entries say so. The historical Meta and NEI shorthand does not establish a particular application cycle.

## Limits and maintenance

This is a bounded omission audit of the named source sets and historical records, not a claim to contain every startup program worldwide. Unverified leads remain visible in the audit; they are not silently promoted into active funding offers. Application windows, program names, benefits, prices and eligibility can change after this dated review.

No application was submitted through this research. Private workbooks, applicant status, correspondence, credentials and receipts are not published.

[Browse the expanded directory](guides/startup-programs.md) · [Directory home](README.md)
