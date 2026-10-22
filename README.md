# Sonoran AI Consulting, LLC | Grant Prospect Database

**A structured grant-research resource with a reproducible Jupyter Notebook for prospect review and descriptive analysis.**

## Overview

This repository supports Sonoran AI Consulting's work organizing and reviewing potential funding opportunities. The grant prospect database brings funder and program information into a structured table, while the accompanying notebook provides a repeatable workflow for examining the dataset, reviewing data quality, and exploring prospects by type, status, fit score, deadline and funding-cycle notes, and reported funding ranges.

The notebook is intended to support research and decision-making. It does not independently verify funding opportunities, establish legal eligibility, or guarantee a prospect's suitability.

## What's Included

| Resource                                            | Purpose                                                                                                      |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| `Grant Prospect Database.ipynb`                     | Existing notebook with initial database inspection and exploratory analysis                    
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

## Jupyter Notebook: Database Exploration and Analysis

The expanded Jupyter Notebook provides a reproducible workflow for exploring the grant prospect database and reviewing its contents.

### Analytical Components

**1. Database Overview**

* Summarize the number of prospect records and database fields.
* Identify distinct funders and programs.
* Assess the availability of funding amounts, deadlines, and status information.

**2. Data Quality Assessment**

* Identify missing values and incomplete records.
* Detect exact duplicate rows.
* Flag repeated funder and program combinations for review.

**3. Prospect Landscape**

* Examine the distribution of prospects by recorded funding type.
* Explore the composition of the prospect pipeline.
* Review the categories represented in the database.

**4. Fit Score Analysis**

* Examine the distribution of recorded fit scores.
* Summarize available scoring information.
* Support more consistent prospect review through documented evaluation criteria.

**5. Deadline and Funding Analysis**

* Review recorded deadlines and funding-cycle information.
* Summarize reported funding amounts and ranges.
* Identify records that may require additional research or verification.

**6. Prospect Review**

* Filter prospect records using keyword searches.
* Examine relevant funder and program information.
* Support follow-up research and prospect evaluation.

**7. Data Maintenance**

* Establish repeatable data-quality checks.
* Encourage consistent status labels and scoring criteria.
* Support ongoing verification of funding information.

## Getting Started

### Requirements

The notebook uses Python and the following libraries:

* Python 3
* Jupyter Notebook or JupyterLab
* pandas
* NumPy
* Matplotlib

### Installation

Install the required dependencies using:

```bash
python -m pip install pandas numpy matplotlib jupyter
```

### Running the Notebook

1. Clone or download the repository.
2. Locate the grant prospect CSV file.
3. Place the CSV in the repository root or the `data/` directory.
4. Confirm that the filename and location match the notebook's `DATA_CANDIDATES` configuration.
5. Open `notebooks/Grant Prospect Database - Preview.ipynb` in Jupyter.
6. Run the cells sequentially to generate the database overview, data-quality summaries, and visualizations.

The original notebook can also be used to review the existing exploratory analysis.

## Data Quality and Responsible Interpretation

The usefulness of grant research depends on the accuracy, completeness, and timeliness of the underlying information.

Recommended practices include:

* Verify funding amounts, eligibility requirements, deadlines, and application instructions against current funder sources.
* Record source URLs and the date each prospect was last verified.
* Document the criteria and scale used to calculate fit scores.
* Standardize prospect status labels and define what each status represents.
* Review duplicate and incomplete records before prioritizing opportunities.
* Treat missing information as unknown rather than as evidence of ineligibility or poor alignment.
* Keep confidential information and unnecessary personal data out of public repository files and notebook outputs.

The notebook provides descriptive analysis of the available dataset. Its outputs should not be interpreted as independent verification of funding opportunities or definitive eligibility determinations.

## Potential Future Enhancements

Future development may include:

* Adding source URLs and last-verified dates to prospect records.
* Standardizing deadline and funding-cycle fields.
* Documenting the fit-scoring methodology.
* Developing a consistent prospect prioritization framework.
* Expanding data validation and maintenance procedures.
* Adding additional visualizations and summary metrics as the database grows.

## Project Status

This repository is an evolving grant-research and exploratory-analysis resource for Sonoran AI Consulting.

The grant prospect database serves as the central research resource, while the Jupyter Notebook provides a foundation for structured analysis, data-quality review, and ongoing improvement of prospect research workflows.

The project can evolve alongside the organization's funding research needs, analytical capabilities, and data-management practices.
