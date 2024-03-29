<img src="imgs/header.png">

# CIX 2022: Bayesian HCI

* Computational Interaction Summer School Notes
* Saarbrucken, June 2022
* **John H. Williamson, University of Glasgow**

## Notes
* This is a brief introduction to Bayesian methods for HCI. It encompasses:
  * Basic Bayesian philosophy and probability theory
  * Bayesian methods in the loop
  * Bayesian optimisation
  * Empirical analyis with Bayesian methods
  * Bayesian cognitive modelling
  * Visualisation and interaction with Bayesian models
* These notes are released under an MIT license.
* All notes are available as a Jupyter notebook. 
## Installing

I recommend having [Anaconda](https://www.anaconda.com/products/distribution) pre-installed. To create a clean environment for these notes (my recommended approach):

* `conda create -n cix_2022_jhw`
* `conda activate cix_2022_jhw`
* `conda install jupyter matplotlib numpy scipy seaborn pandas ipykernel`
* `pip install -r requirements.txt`
* `jupyter notebook`

On Windows, `pymc3` sometimes has trouble. Try:

        pip uninstall pymc3
        conda install pymc3 m2w64-toolchain -c conda-forge

## Navigating

* [Part I: Overview and admin](i_outline.ipynb)
* [Part II: Theory and practice](ii_theory_and_practice.ipynb)
* [Part III: Bayesian HCI](iii_bayesian_hci.ipynb)
