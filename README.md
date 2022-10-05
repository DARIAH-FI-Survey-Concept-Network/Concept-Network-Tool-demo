# Concept-Network-Tool-demo

A demo version of a software package for the discovery of a network of related concepts from unstructured texts in the DARIAH-FI project.

## Tutorial

### Requirements

1. [Jupyter Notebook installation](https://jupyter.org/install) with R kernel (via [`IRkernel` R-package](https://github.com/IRkernel/IRkernel)).

2. Your own data. For example, download [FSD3360 Helsingin Sanomat Loneliness Survey 2014](https://services.fsd.tuni.fi/catalogue/FSD3360?tab=description&lang=en&study_language=en) from the Finnish Social Data Archive. Use file format which can be imported into R.

3. The input data for the tool must be in [CONLL-U](https://universaldependencies.org/format.html) formatted CSV. See [`UDPipe`](https://cran.r-project.org/web/packages/udpipe/index.html) package for R how to convert data to CONLL-U format.


### Pipeline 

| Order 	| Input                                                                         	| Notebook                 	| Output                                                                        	|
|-------	|-------------------------------------------------------------------------------	|--------------------------	|-------------------------------------------------------------------------------	|
| 0.    	| Any data file imported into R                                                 	| `Data Preparation Tutorial.ipynb` 	| `csv` file in [CONLL-U](https://universaldependencies.org/format.html) format 	|
| 1     	| `csv` file in [CONLL-U](https://universaldependencies.org/format.html) format 	| `Concept Network Tool.ipynb` 	|                                                                               	|


#### 0. Data preparation

See `Data preparation.ipynb` notebook.

#### 1. Concept Network Tool

See  `Concept networks.ipynb` notebook.


#### In Development

- `Manual Concept Extraction.ipynb`

