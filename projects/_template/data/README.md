# Data

## Source
**Identify the original dataset and where to obtain it:**
- Dataset: <Official dataset name>
- Publisher: <Organisation or individual>
- URL: <Direct dataset or landing-page link>
- Version / release: <Version, release date, or access date>

_Prefer the original publisher over a third-party copy. Record the version or release date when the data changes over time._

## License / terms
**Explain whether and under what conditions the data can be used:**
- License: <License name>
- Usage restrictions: <Applicable restrictions>
- Attribution: <Required attribution, if any>
- Commercial use: <Allowed / prohibited / unclear>
- Redistribution: <Allowed / restricted / unclear>

_Check the actual license or terms of use rather than assuming that publicly accessible data is free to redistribute. If the terms are unclear, say so._
_For datasets without a formal license, record that explicitly._

## Download steps
**Document how someone can obtain the data from scratch:**
1. Visit <official dataset URL>.
2. Navigate to <dataset or release>.
3. Download <filename>.
4. Extract the archive into `data/raw/`.
5. Verify the downloaded files against the expected filenames and structure.

_If the project downloads data through an API or script, document the endpoint, parameters, and execution command instead._
_Important: Distinguish between the original data and derived data. Raw data should remain unchanged so that the analysis can be reproduced._

## Files and size
**Document what the project expects to find locally:**
| File | Format | Rows × columns | Size | Description |
|---|---|---:|---:|---|
| `dataset.csv` | CSV | <rows × columns> | <size> | <Description> |

_For Excel workbooks, specify the relevant sheet if necessary. For compressed archives, distinguish the archive size from the extracted data size._
_If the data hasn't been downloaded yet, label these figures as expected rather than presenting them as verified facts._
_For a dataset containing multiple files, list each file separately._

## Notes
**Record known issues that could affect the analysis:**
- Missing values: <Affected columns and extent of missingness>
- Duplicates: <Whether duplicate records exist>
- Class imbalance: <Relevant only to classification datasets>
- Outliers: <Known or suspected anomalies>
- Data quality: <Known inconsistencies or limitations>
- Potential bias: <Sampling, coverage, or representation concerns>

_Distinguish between verified problems and issues that still need to be investigated. Don't claim that a dataset has missing values or class imbalance until it has been checked._