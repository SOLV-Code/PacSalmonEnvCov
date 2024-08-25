# Open-Source Data System for *Pacific Salmon Environmental Covariates* (PSEC)

## Purpose

Population models for Pacific salmon (*Oncorhynchus* spp.) increasingly consider environmental covariates to improve forecasts or develop estimates of management reference points that respond to changing conditions. These analyses generally draw on the same suite of environmental covariates, but with potentially significant differences in the data treatment details. Some of the widely used series are publicly available (e.g. Pacific Decadal Oscillation index), and for some of the common covariates raw source data is published online (e.g., sea surface temperature records from British Columbia lighthouses). Specific data sets used in published analyses are increasingly shared via github repositories or as supplementary files to the papers, but these are not routinely updated with new records.

Despite this growing amount of data available online, there is no centralized public source of directly usable environmental covariate series to support routine exploration and testing of hypotheses. To address this gap, we are building an open-source data system using existing GitHub functionality. 

## Guiding Principles

[**Pacific Salmon Environmental Covariates (PSEC)**](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon) focuses on building a data set and comprehensive context through collaborative development in a human-centered framework that minimizes technical obstacles for contributors. An open-source collaborative approach for building a data resource has great potential, but is also unpredictable and open-ended. Scope, structure, and contents of this resource will evolve through active contributions and debate.

Three guiding principles have shaped the evolution of the repository so far

* *Make it easy access to the data*: [Individual source data](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/DATA) and the [merged file with all covariates](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/OUTPUT) are stored as *csv* files which work seamlessly across operating systems and software applications. Background information and metadata are documented in the *README.md* for each data set.  Data processing and merging is done with [R code](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/CODE).
* *Make it easy to contribute data and context information*: TEXT revision tracking
* *Foster discussion of the data*: Text


## Links

* [Repository main page](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main)
* [Summary of current coverage](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/NOTES/Current_Coverage)
* [Comparison of data sets](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/NOTES/ScopeOfAnalyses)
* [Data sets and descriptions](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/DATA)

