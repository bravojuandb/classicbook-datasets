# Classic Book Datasets

This repository stores the final aligned datasets used by the The [Classic Book API](https://github.com/bravojuandb/classicbook-api) and [Classic Book ETL Pipeline](https://github.com/bravojuandb/classicbook-etl-pipeline).
## Contents
- **data/** – TSV/CSV files containing manually aligned Latin and English text.
- **scripts/** – Simple Python utilities to extract raw HTML text (Latin and English) from the original websites.

## Workflow
1. Run the extraction script(s) to download raw Latin and English text.
2. Perform **manual alignment** of the texts outside this repository.
3. Save the aligned output as a `.tsv` or `.csv` in the `data/` folder.
4. The [Classic Book API](https://github.com/bravojuandb/classicbook-api) and [Classic Book ETL Pipeline](https://github.com/bravojuandb/classicbook-etl-pipeline) fetch datasets directly from this repository via their GitHub raw URLs.


## Notes
- Alignment is **manual** and not handled by any code in this repository.
- This repo does not contain transformation or loading logic — those steps live in the [Classic Book ETL Pipeline](https://github.com/    bravojuandb/classicbook-etl-pipeline).
