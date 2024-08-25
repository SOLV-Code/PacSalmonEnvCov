# Open-Source Data System for *Pacific Salmon Environmental Covariates* (PSEC)

## Purpose

Population models for Pacific salmon (*Oncorhynchus* spp.) increasingly consider environmental covariates to improve forecasts or develop estimates of management reference points that respond to changing conditions. These analyses generally draw on the same suite of environmental covariates, but with potentially significant differences in the data treatment details. Some of the widely used series are publicly available (e.g. Pacific Decadal Oscillation index), and for some of the common covariates raw source data is published online (e.g., sea surface temperature records from British Columbia lighthouses). Specific data sets used in published analyses are increasingly shared via github repositories or as supplementary files to the papers, but these are not routinely updated with new records.

Despite this growing amount of data available online, there is no centralized public source of directly usable environmental covariate series to support routine exploration and testing of hypotheses. To address this gap, we are building an open-source data system using existing GitHub functionality. 

## Guiding Principles

[**Pacific Salmon Environmental Covariates (PSEC)**](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon) focuses on building a data set and comprehensive context through collaborative development in a human-centered framework that minimizes technical obstacles for contributors. An open-source collaborative approach for building a data resource has great potential, but is also unpredictable and open-ended. Scope, structure, and contents of this resource will evolve through active contributions and debate.

Three guiding principles have shaped the evolution of the repository so far:

* Make it easy access to the data
* Make it easy to contribute data and context information
* Foster discussion of the data

### Make it easy to access the data

[Individual source data](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/DATA) and the [merged file with all covariates](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/OUTPUT) are stored as *csv* files which work seamlessly across operating systems and software applications. Background information and metadata are documented in the *README.md* for each data set.  Data processing and merging is done with [R code](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/CODE).

### Make it easy to contribute data and context information

The initial entry for a new data set can be just two basic files: 

* a csv file with covariate time series and some details in the header 
* a brief README.md file with some context for the data file

Over time, the entry can then grow to include R code that directly downloads raw data and generates the covariate. In response to questions, the README file can build more detailed information about the data and how it is being used. 

The [DFO Fraser Sockeye Forecast data set](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/DATA/DFO_FraserSockeyeForecast) is a good example of a well-developed data entry. 

### Foster discussion of the data

*PSEC* uses the collaboration features of GitHub to foster discussion in two ways:

* [Discussion threads](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/issues) for specific questions or comments
* [Short notes](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/NOTES) that can be edited directly in your browser (Just click the pencil icon at the top of the note)


*Test1*

<img src="https://github.com/SOLV-Code/PacSalmonEnvCov/blob/main/docs/assets/images/Dags&Ducks&3dPrints.PNG"
	width="400">


*Test2*

![image test](/PacSalmonEnvCov/docs/assets/images/Dags&Ducks&3dPrints.PNG)

