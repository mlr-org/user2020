# useR! 2020 online tutorial on mlr3

The tutorial will be held by Bernd Bischl ([home page](https://www.slds.stat.uni-muenchen.de/), [twitter](https://twitter.com/BBischl)) and Michel Lang ([twitter](https://twitter.com/michellangts)) on [August 7th, 15:00 UTC](https://arewemeetingyet.com/UTC/2020-08-07/15:00/useR!%202020%20Tutorial:%20mlr3) for approximately 3 hours.
The event is hosted by the [RLadies Galápagos](https://twitter.com/rladiesgps).

**UPDATE**: The recording can be found on [Youtube](https://youtu.be/T43hO2o_nZw).

## About

Our tutorial introduces the package [mlr3](https://mlr3.mlr-org.com) for modern, state-of-the-art machine learning in R.
The `mlr3` ecosystem provides a one-stop solution for all machine learning (ML) needs, spanning preprocessing, model learning and evaluation, ensembles, visualization, and hyperparameter tuning (via [mlr3tuning](https://mlr3tuning.mlr-org.com)).
Its pipeline system [mlr3pipelines](https://mlr3pipelines.mlr-org.com) allows to easily express complex workflows, and to quickly prototype new ideas and applications.
Whether you are applying ML to solve a practical prediction problem, implementing learning algorithms as a research software engineer or researching ML by empirical means,
`mlr3` can help make your workflow more readable and efficient.


## Learning Objectives

The main objective of the tutorial is to introduce and familiarize users with `mlr3` and its ecosystem.
This will allow participants to take advantage of its functionality for their own projects, in particular:

* how to benchmark and compare different machine learning approaches in a statistically sound manner,
* how to build complex machine learning workflows, including preprocessing and stacked ensembles,
* automatic hyperparameter tuning and pipeline optimization (AutoML),
* how to get the technical "nitty-gritties" for ML experiments right, e.g., speed up by parallelization, encapsulation of experiments in external processes or working on databases.


## Target Audience

We target to users with at least basic knowledge of machine learning concepts who are not yet familiar with `mlr3`.
We require a working knowledge of R at medium level.
One should know R's general type system and basic operations.
Some experience with [R6](https://cran.r-project.org/package=R6) and [data.table](https://cran.r-project.org/package=data.table) definitely help, but is not essential.


## Course Materials

Slides can be found in the pdf directory of this repository.
The examples are rendered in the [gallery](https://mlr3gallery.mlr-org.com/) with tag [german credit](https://mlr3gallery.mlr-org.com/#german_credit).

Install these packages for the examples:

```{r}
install.packages("mlr3")
install.packages("mlr3learners")
install.packages("data.table")
install.packages("mlr3viz")
install.packages("ggplot2")
install.packages("mlr3tuning")
install.packages("paradox")
install.packages("mlr3filters")
install.packages("remotes")
install.packages("praznik")
install.packages("ranger")
install.packages("kknn")
install.packages("xgboost")
install.packages("rchallenge")
install.packages("skimr")
install.packages("DataExplorer")
remotes::install_github("mlr-org/mlr3pipelines")
```

We also highly recommend to check out our [book](https://mlr3book.mlr-org.com/).
The most time efficient way to get into the package is to read the [cheat sheets](https://cheatsheets.mlr-org.com/).

## Schedule 

The tutorial is split into 3 parts (55 min each, talk + use case), in the middle there will be a 15 min coffee break:

1. mlr3
2. mlr3tuning 
3. mlr3pipelines

At the end of each session we will answer questions asked and upvoted via [sli.do](https://app.sli.do/event/tazsdetb).
