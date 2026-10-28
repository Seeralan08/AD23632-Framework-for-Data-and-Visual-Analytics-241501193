# AD23632 - Framework for Data and Visual Analytics

**Name:** Seeralan M  
**Reg no:** 241501193

This repository contains seven AD23632 experiment PDFs and an IPL sports analytics mini-project made with Power BI Desktop.

## Contents

| Item | Description |
|---|---|
| `experiments/` | Experiments 01-07 with Seeralan M and registration number on each page. |
| `Seeralan-M-Sports-Analytics.pbix` | Main interactive Power BI report. |
| `Seeralan-M_AD23632_Mini_Project_Report.pdf` | Project report with dataset scope, transformations, results, and screenshots. |
| `data/` | Prepared CSV, source archive, data dictionary, license, and provenance. |
| `screenshots/` | Power BI Desktop captures of raw data, Power Query, dashboards, and filtered records. |
| `EVIDENCE.md` | GitHub-rendered screenshot gallery. |

## Project overview

BoundaryLab analyzes 459 available men’s IPL match summaries from 2018-2024: 457 have a winner and 2 are no-result matches. The report uses season, team, winner, stage, and venue selections to explore match outcomes and scoring patterns. Match-level and team-perspective tables use distinct Match IDs for match counts.

The PBIX opens in Power BI Desktop. Its Power Query inputs embed the dataset, so refresh does not depend on a file path from the authoring computer. The bundled CSV and source archive are included for direct inspection.

## Screenshot gallery

Open the [Power BI evidence gallery](EVIDENCE.md) to see the raw data, Power Query before and after cleanup, and dashboard before and after filtering.

## Dataset source

The match data comes from [Cricsheet downloads](https://cricsheet.org/downloads/). The `data/` directory contains the original archive, prepared CSV, data dictionary, license text, and provenance record. Prepared CSV SHA-256: `9d082a804a4d54531e9f2a42f6d00850ed3aee3f8e4fd0f0a74c33b5e446a544`.

## Open the project

1. Download `Seeralan-M-Sports-Analytics.pbix`.
2. Open it in Power BI Desktop.
3. Use the overview with slicers cleared for the baseline view.
4. To reproduce the report example, select Season 2024 and Chennai Super Kings, then inspect the filtered records page.
