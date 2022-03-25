Ci4d3: Causal inference for drug discovery and development
===
Jitao David Zhang, Tom Michoel, Zhiwen Jiang

We offer practitioners of drug discovery and development reproducible tutorials for doing causal inference with Python and R. It accompanies a review article on the same topic which will be published soon.

The repository is currently being actively updated. Feedback through issues and pull requests are welcome.

The repository is shared with the CC-BY 4.0 license.

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
