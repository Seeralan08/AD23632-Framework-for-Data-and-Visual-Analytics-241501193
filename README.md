# AD23632 - Framework for Data and Visual Analytics

**Name:** Seeralan M  
**Reg no:** 241501193

This repository contains the seven AD23632 experiment records and the IPL sports analytics mini-project for Power BI Desktop.

## Files

| Item | Description |
|---|---|
| `experiments/` | Experiments 01-07 as PDFs, with the student identity updated in each page. |
| `Seeralan-M-Sports-Analytics.pbix` | Main interactive Power BI Desktop report. |
| `Seeralan-M_AD23632_Mini_Project_Report.pdf` | Mini-project report with dataset scope, Power Query steps, metrics, and original Power BI screenshots. |
| `data/dataset.csv` | Prepared 2018-2024 Cricsheet IPL match-summary snapshot used by the report. |
| `data/` | Data dictionary, source archive, license text, and retrieval provenance. |
| `screenshots/` | Captures of the raw data, Power Query, dashboard before/after filtering, and filtered records. |

## Project overview

BoundaryLab analyzes 459 available men’s IPL match summaries from 2018-2024 (457 with a winner and 2 with no result). The report uses season, team, winner, stage, and venue selections to explore match outcomes and scoring patterns. The Power BI model includes match-level and team-perspective tables; match counts use distinct Match IDs to avoid double-counting.

The main PBIX is designed to open in Power BI Desktop. Its Power Query inputs embed the dataset, so refresh does not depend on a local path from the authoring computer. The bundled CSV and source materials are provided so the dataset can also be inspected directly.

## Dataset source

The original match data is from [Cricsheet downloads](https://cricsheet.org/downloads/). The repository includes the original source archive, the prepared CSV, a data dictionary, license text, and provenance details. The prepared CSV SHA-256 is `9d082a804a4d54531e9f2a42f6d00850ed3aee3f8e4fd0f0a74c33b5e446a544`.

## Open the project

1. Download `Seeralan-M-Sports-Analytics.pbix`.
2. Open it in Power BI Desktop.
3. Use the overview page with slicers cleared for the baseline.
4. To reproduce the report example, select Season 2024 and Chennai Super Kings, then review the filtered records page.


## Screenshot gallery

View the [Power BI evidence gallery](EVIDENCE.html) for the raw data, Power Query changes, and dashboard before and after filtering.
View the [GitHub-rendered Power BI evidence gallery](EVIDENCE.md) for the raw data, Power Query changes, and dashboard before and after filtering.
