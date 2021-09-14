## Motivations, concerns and selection biases when posting preprints: a survey of bioRxiv authors

This repository contains the underlying code and data for the study:

[Fraser, N., Mayr, P., and Peters, I. (2021). Motivations, concerns and selection biases when posting preprints: a survey of bioRxiv authors.](https://doi.org/10.1101/2021.09.07.459259)

The code and data contained in this repository is also archived via Zenodo: https://doi.org/10.5281/zenodo.5255880

An overview of the most important files and directories is provided below:

- [`design/`](design) contains files relevant to the survey design, including a printable summary of the entire survey ([`design/survey_printable.pdf`](design/survey_printable.pdf)), a simplified schematic of the survey workflow ([`design/survey_design_overview.pdf`](design/survey_design_overview.pdf)) and all exported LimeSurvey template files.
- [`email_retrieval.Rmd`](email_retrieval.Rmd) and [`email_cleaning.Rmd`](email_cleaning.Rmd) document the processes used to retrieve email addresses of corresponding authors of  [bioRxiv](https://biorxiv.org) preprints from the bioRxiv platform, and clean/validate  those addresses for inviting to participate in the survey. Note that raw email addresses have not been included in this dataset.
- [`main_analysis.Rmd`](main_analysis.Rmd) documents the main analysis of survey responses, including the generation of all figures shown in the manuscript.
- [`regression_analysis.Rmd`](regression_analysis.Rmd) documents the ordinal logistic regression analysis on survey response data as documented in the manuscript.
- [`data/`](data) contains anonymised survey response data ( [`data/response_data_anonymised.csv`](data/response_data_anonymised.csv)). Note that free-text comments have been removed from this dataset to prevent participant identification.
- [`outputs/figures/`](outputs/figures) contains all figures (in .png format) generated from [`main_analysis.Rmd`](main_analysis.Rmd).
