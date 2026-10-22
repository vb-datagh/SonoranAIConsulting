# Sonoran AI Consulting, LLC | Grant Prospect Database

**A structured grant-research resource with a reproducible Jupyter Notebook for prospect review and descriptive analysis.**

## Overview

This repository supports Sonoran AI Consulting's work organizing and reviewing potential funding opportunities. The grant prospect database brings funder and program information into a structured table, while the accompanying notebook provides a repeatable workflow for examining the dataset, reviewing data quality, and exploring prospects by type, status, fit score, deadline and funding-cycle notes, and reported funding ranges.

The notebook is intended to support research and decision-making. It does not independently verify funding opportunities, establish legal eligibility, or guarantee a prospect's suitability.

## What's Included

| Resource                                            | Purpose                                                                                                      |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| `Grant Prospect Database.ipynb`                     | Existing notebook with initial database inspection and exploratory analysis                                  |
| `notebooks/Grant Prospect Database - Preview.ipynb` | Expanded notebook template for database overview, data quality, visualizations, and prospect review          |
| Grant prospect CSV                                  | Source dataset loaded by the notebook; keep the filename and path consistent with the notebook configuration |

> **Data availability:** The expanded notebook expects the grant prospect CSV to be present in the repository root or `data/` directory. Do not publish confidential, personal, or otherwise sensitive information in a public repository.

## Grant Prospect Database

The grant prospect database is the primary resource in this repository. It organizes information about potential funders and funding opportunities to support prospect research, eligibility review, and funding strategy development.

The current database fields include:

* `#` — Record or list number
* `Funder` — Funding organization or grantmaker
* `Program` — Named grant, funding program, or opportunity
* `Type` — Funder or opportunity category
* `Amount Range` — Reported funding amount, range, or award description
* `Deadline` — Reported deadline, funding cycle, or monitoring note
* `Eligibility / Alignment Notes` — Eligibility considerations, strategic alignment, and follow-up notes
* `Fit Score` — Internal prospect fit score
* `Status` — Internal prospect tracking status

The original notebook's saved outputs show 13 prospect records. This figure represents the saved notebook snapshot and may not reflect the current database size.

## Jupyter Notebook: Database
