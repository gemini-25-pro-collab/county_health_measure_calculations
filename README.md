# County Health Rankings & Roadmaps  
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://countyhealthrankings.github.io/welcome/contribute.html)

This repository is a work in progress. It contains code and data to replicate some measures for the [County Health Rankings & Roadmaps annual data release](https://www.countyhealthrankings.org/health-data). 
At this time, we do not plan to make historical calculations public - this repo may be useful for replicating parts of the 2025 and 2026 releases and for adapting CHR&R methods for future analyses. 

## Contributions are welcome!
This repository is intended to support transparency and collaboration. Contributions are welcome from anyone interested in replicating, extending, or improving these calculations. If these scripts are adapted or expanded for other analyses, contributions back to this repository are encouraged. Helpful contributions include adding scripts to calculate new measures of county-level health and equity, updating existing scripts for new data releases, and improving documentation to support reproducibility. Please see the [Contribution Guidelines](https://countyhealthrankings.github.io/welcome/contribute.html) for more information on how to get involved. 

## Repository Structure
  
* **`inputs/`** – Standardized reference files used across multiple measures (e.g., crosswalks, FIPS codes).  

* **`raw_data/`** – Original, unprocessed data files from source systems or data providers.  
  - This folder is organized by data source. 
  - *Note: Some raw data are not included if they are not publicly available.*

* **`scripts/`** – R scripts (`.qmd`, `.Rmd`) and some SAS files for data cleaning, calculation, and formatting of measures.
  
* * **`measure_datasets/`** – Datasets with calculated values for specific health measures.  

We recommend using the `haven` R package to read `.sas7bdat` files in R. 


## Questions? 
If you prefer data or calculations in a different format, are looking for a specific measure not yet included, or have questions, please reach out via the [Discussions tab](https://github.com/countyhealthrankings/chrr_measure_calcs/discussions).

If you're looking for downloadable datasets (formatted for easy reading) or relational datasets (structured for analysis), you can find them by checking out [County Health Rankings & Roadmaps on Zenodo](https://zenodo.org/communities/countyhealthrankingsandroadmaps/records?q=&l=list&p=1&s=10&sort=newest). 

You can also email us at **info@countyhealthrankings.org**.
