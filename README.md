Testing out API calls from R

## Execution
To execute, run the below commands:

```{r}
rstudioapi::jobRunScript(here::here("execute.R"))
```

## Structure
The project contains the following general structure:

* R: Complex or significant amounts of R code that is not appropriate for notebooks
* data-raw: Incoming datasets that should be considered readonly;
* data: Datasets produced for cleaning, analysis, or distribution after execution of scripts;
* notebooks: Notebooks that support the manipulation and analysis of the datasets; number workbooks in order of execution required and divide into subdirectories if needed
* output: Any documents or datasets intended for distribution from this project
* renv: R packages needed to execute the project
* reports: RMarkdown documents that support the manipulation and analysis of the datasets; number workbooks in order of execution required and divide into subdirectories if needed
* sql: SQL scripts to extract datasets
