# Open-Source Data System for *Pacific Salmon Environmental Covariates* (PSEC)

![DAGsDucks3DPrints](/PacSalmonEnvCov/images/Dags&Ducks&3dPrints.PNG)

## Purpose

Despite the growing amount of environmental data available online, there is no centralized public source of directly usable environmental covariate series to support routine exploration and testing of hypotheses in salmon models. To address this gap, we are building an open-source data system using existing GitHub functionality. 

Population models for Pacific salmon (*Oncorhynchus* spp.) increasingly consider environmental covariates to improve forecasts or develop estimates of management reference points that respond to changing conditions. These analyses generally draw on the same suite of environmental covariates, but with potentially significant differences in the data treatment details. Some of the widely used series are publicly available (e.g. Pacific Decadal Oscillation index), and for some of the common covariates raw source data is published online (e.g., sea surface temperature records from British Columbia lighthouses). Specific data sets used in published analyses are increasingly shared via github repositories or as supplementary files to the papers, but these are not routinely updated with new records.



## Guiding Principles

[**Pacific Salmon Environmental Covariates (PSEC)**](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon) focuses on building a data set and comprehensive context through collaborative development in a human-centered framework that minimizes technical obstacles for contributors. An open-source collaborative approach for building a data resource has great potential, but is also unpredictable and open-ended. Scope, structure, and contents of this resource will evolve through active contributions and debate.

Three guiding principles have shaped the evolution of the repository so far:

* Make it easy access to the data
* Make it easy to contribute data and context information
* Foster engagement with the data

### Make it easy to access the data

[Individual source data](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/DATA) and the [merged file with all covariates](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/OUTPUT) are stored as *csv* files which work seamlessly across operating systems and software applications. Background information and metadata are documented in the *README.md* for each data set.  Data processing and merging is done with [R code](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/CODE).

### Make it easy to contribute data and context information

The initial entry for a new data set can be just two basic files: 

* a csv file with covariate time series and some details in the header 
* a brief README.md file with some context for the data file

Over time, the entry can then grow to include R code that directly downloads raw data and generates the covariate. In response to questions, the README file can build more detailed information about the data and how it is being used. 

The [DFO Fraser Sockeye Forecast data set](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/DATA/DFO_FraserSockeyeForecast) is a good example of a well-developed data entry. 

### Foster engagement with the data

Environmental factors interact with salmon throughout their entire life cycle, but also interact with each other, creating complex causal pathways that can create serious pitfalls for your analyses. We are exploring tools that help individuals and teams work through these complexities: **Ducks**, **DAGs**, and **Tangible Data**

![DuckImage](/PacSalmonEnvCov/images/Duck_Image.PNG]

The [Rubber Duck Technique](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/wiki/Rubber-Duck-Technique) is a problem solving trick used in software development: Try to explain your code problem out loud to the rubber duck, and along the way you can catch flaws in your logic. The underlying idea is to use some device that forces you to convert technical details into simple, natural language, which changes how you think about the problem. The same technique can help us think through the thicket of potential covariates for salmon models.

*PSEC* uses the collaboration features of GitHub to encourage verbal thinking about environmental covariates in two ways:

* [Discussion threads](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/issues) for specific questions or comments
* [Short notes](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/tree/main/NOTES) on broader topics that can be edited directly in your browser (Just click the pencil icon at the top of the note)

![DAGImage](/PacSalmonEnvCov/images/DAG_Image.PNG]

[Directed Acyclic Graphs (DAGs)](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/wiki/Causal-Inference) are a graphical tool for thinking about causal relationships and building blueprints for quantitative models. DAGs focus on major pathways and directions of influence, setting aside specific relationships and numeric parameters for subsequent steps in the analysis. Think of DAGs as the bridge between a high-level verbal description and an initial version of the model code. All three stages then need to be refined through many rounds of review, discussion, and testing until the fundamental logic is sound and the code accurately implements that logic.


![3dPrint_Image](/PacSalmonEnvCov/images/3dPrint_Image.PNG]

Even the most polished plots are still limited to page or screen. Interactive tools like Shiny Apps allow us to get closer to the data and look at it in different ways, but turning data series into tangible, physical objects can encourage even more active engagement. With the increasing accessibility of [3D printing](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/wiki/Tangible-Data:-3D-Prints) this is becoming feasible on a small scale, and you can [use R for the first step](https://github.com/SOLV-Code/Open-Source-Env-Cov-PacSalmon/blob/main/CODE/5_Create_3D_Prints.R).




