Causal inference for drug discovery and development
===
Jitao David Zhang

This repository offers practitioners of drug discovery and development
reproducible tutorials for doing causal inference with Python and R. It
accompanies a review article on the same topic which will be published soon.

The repository is shared with the CC-BY 4.0 license. The context is being
actively updated. Feedback through issues and pull requests are welcome .

## Acknowledgement

I thank Tom Michoel and Zhiwen Jiang for inspirations and discussions.

## Causal inference with DoWhy package in Python

See [2021-11-dowhy.ipynb](2021-11-dowhy.ipynb). The examples are taken from the documentations of the *DoWhy* package.

### Content

* How to work with *DoWhy* in four steps:
    * Modelling
    * Identification
    * Estimation
    * Refutation
* Working with *DoWhy* and *EconML*: an non-linear example
* DoWhy API for Pandas data frames

### Reproducing the tutorial

Create a conda environment using the `environment.yml` file, install a new python kernel for Jupyter with the command below, and run the Jupyter notebook with the kernel.


```bash
conda activate causality
conda install -c conda-forge pip ipykernel
python -m ipykernel install --user --name causal --display-name "causality"
```

## Causal inference with R and Bayesian inference with RStan

See [2021-12-CausalSalad.Rmd](2021-12-CausalSalad.Rmd). The models are largely taken from the [Causal Salad 2021](https://github.com/Accio/causal_salad_2021) repository contributed by Richard McElreath.

## Causal model selection

See [2022-08-CausalModelSelectio.jmd](2022-08-CausalModelSelection.jmd). This tutorial explains and illustrates the principles of causal model selection in the analysis of molecular QTL data. The tutorial is written in [julia](https://julialang.org) using [Weave.jl](https://weavejl.mpastell.com/). If you are not familiar with [julia](https://julialang.org), download or clone the contents of this repository and open the file [2022-08-CausalModelSelection.html](2022-08-CausalModelSelection.html) in a browser. The code itself uses basic statistical and plotting functions, and should be easy to translate to other languages.
