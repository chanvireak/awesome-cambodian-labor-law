# Awesome Cambodian Labour Law & Regulations

> A free, structured index of Cambodian labour-law instruments — and a live showcase of the **FTK document library**.

This repository exists for two reasons:

1. **A free resource for labour compliance in Cambodia.** Employers, HR teams, unions, lawyers and researchers get a clean, navigable map of Cambodian labour regulation — what each instrument does, when it was issued, and whether it is in force.
2. **A showcase of what FTK can do.** Every regulation here is a real document held and processed in the FTK document library. Each note carries the FTK document ID of the source document, so you can see that the content is backed by a genuine, indexed instrument — not scraped text.

## Why every note carries an FTK document ID

Each regulation is its own Markdown note with YAML front matter that includes a field like:

```yaml
ftk_doc_id: 142636
ftk_indexed: true
```

- `ftk_doc_id` is the identifier of the **full document in the FTK library** (the original PDF/scan, not just this summary).
- `ftk_indexed: true` means FTK holds and has processed the source document. `false` means the instrument is listed for completeness but is not yet in the library.

This is the trust signal: the summary you read here was derived from the document's own text inside FTK. When you need the **full text, the original file, or the whole corpus with search and cross-referencing**, that lives in FTK.

## Browse the library

**558 regulations · 449 indexed in FTK (80%) · snapshot 2026-10-07**

| # | Category | Sub-categories | Instruments |
| :-- | :-- | :-- | :-- |
| 1 | [Fundamental Labor Law & General Administration](01-fundamental-labor-law-general-administration/README.md) | 3 | 25 |
| 2 | [Employment Contracts, Hiring & Staff Administration](02-employment-contracts-hiring-staff-administration/README.md) | 3 | 19 |
| 3 | [Remuneration, Seniority & Financial Benefits](03-remuneration-seniority-financial-benefits/README.md) | 3 | 22 |
| 4 | [Working Hours, Leave & Holidays](04-working-hours-leave-holidays/README.md) | 3 | 22 |
| 5 | [Occupational Safety and Health (OSH)](05-occupational-safety-and-health-osh/README.md) | 3 | 37 |
| 6 | [National Social Security Fund (NSSF)](06-national-social-security-fund-nssf/README.md) | 7 | 172 |
| 7 | [Foreign Workforce Management](07-foreign-workforce-management/README.md) | 3 | 18 |
| 8 | [Labor Relations & Dispute Resolution](08-labor-relations-dispute-resolution/README.md) | 3 | 54 |
| 9 | [Special Categories of Workers & Protected Sectors](09-special-categories-of-workers-protected-sectors/README.md) | 4 | 19 |
| 10 | [Compliance, Labor Inspections & Penalties](10-compliance-labor-inspections-penalties/README.md) | 3 | 14 |
| 11 | [Crisis Management & COVID-19 Interventions](11-crisis-management-covid-19-interventions/README.md) | 3 | 11 |
| 12 | [Education & Vocational Training](12-education-vocational-training/README.md) | 7 | 145 |

Each category folder has its own `README.md` index, and each sub-category folder holds one Markdown note per regulation.

## How to use this repository

**On GitHub.** Start at the table above, open a category, then a sub-category. Each row in a category index links straight to the regulation note.

**As an Obsidian vault.** Clone the repo and open the folder as a vault. The notes use standard YAML front matter, so you can:

- browse by **`category`** / **`subcategory`**,
- filter with **`tags`** (e.g. `minimum-wage`, `nssf`, `osh`, `foreign-workers`),
- search **`summary`** text,
- jump to the source with **`ftk_doc_id`**,
- use **`aliases`** so that searching `Prakas No. 214/25` finds the note.

**As data.** Every note's front matter is machine-readable — a good starting point for compliance checklists, dashboards or automated monitoring.

## Note format

```yaml
---
title: "2026 Minimum Wage for Textile, Garment, Footwear, Travel Goods"
aliases: ["Prakas No. 214/25"]
issue_no: "Prakas No. 214/25"
type: Prakas
category: "Remuneration, Seniority & Financial Benefits"
subcategory: "A. Minimum Wage Determination"
date: 2025-09-17
status: "Active"
jurisdiction: Cambodia
ftk_doc_id: 142636
ftk_indexed: true
tags: [cambodia, labour-law, minimum-wage, wages]
summary: "Sets the 2026 minimum wage for textile, garment, footwear and travel-goods workers."
---
```

## Status conventions

| Status | Meaning |
| :-- | :-- |
| **Active** | In force. |
| **Abrogated / Aborted** | Repealed. |
| **Superseded** | Replaced by a later instrument. |
| **Expired** | Period-based (e.g. an annual wage or holiday calendar). |
| **Pending** | Adopted but not yet in force, or a draft. |
| **Unknown** | Status not recorded in the source. |

## Scope & sourcing

- The index is kept in sync with the **FTK document library**. Summaries are derived from each regulation's own text there.
- Instruments **not yet held** in the library are still listed (for completeness) with `ftk_indexed: false`; their summary reads *"Not yet indexed in the FTK library"*. As the library grows, these get filled in.
- Entries reflect the documents as published; where a later instrument amends or replaces an earlier one, both are listed and the status column says so.

## Disclaimer

This is an informational index, **not legal advice**. Summaries are condensed and may omit detail or conditions. Always read the full instrument (available via its FTK document ID) and consult a qualified adviser before relying on it.

## About FTK

FTK is a document-processing platform that ingests, indexes and makes searchable the regulatory and administrative documents a business has to comply with. This repository is the public, human-readable face of one slice of that corpus: Cambodian labour law.
