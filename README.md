# covid-19_wikipedia

This repository contains code to replicate the analyses of the paper `COVID-19 research in Wikipedia`.

To create the required datasets, and in particular to get [Dimensions](https://docs.dimensions.ai/dsl) and [Altmetric](https://api.altmetric.com) data, see [this repository instead](https://github.com/CWTSLeiden/cwts_covid). 

## Data sources

We consider publications from the following sources:

* [CORD19](https://pages.semanticscholar.org/coronavirus-research) 
* [Dimensions](https://docs.google.com/spreadsheets/d/1-kTZJZ1GAhJ2m4GAIhw1ZdlgO46JpvX0ZQa232VWRmw/edit#gid=2034285255)
* [WHO](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/global-research-on-novel-coronavirus-2019-ncov)

A dataframe containing these publications [is provided](data/df_meta.csv).

## Contents

* [Notebook_1_startup](Notebook_1_startup.ipynb) descriptive exploration.
* [Notebook_2_topic_modelling](Notebook_2_topic_modelling.ipynb) Topic models.
* [Notebook_3_specter](Notebook_3_specter.ipynb) [SPECTER embeddings](https://github.com/allenai/paper-embedding-public-apis#specter) and clustering.
* [Notebook_4_citation_network](Notebook_4_citation_network.ipynb) bibliographic coupling network clustering.
* [Notebook_5_regression](Notebook_5_regression.ipynb) regression analyses.

## How to cite

TBD.
