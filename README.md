# model_single_cell_RNA_counts_pymc

Testing to model single cell RNA counts with a bayesian mixture model using the python package ‘pymc’.

The counts are modelled with a mixture of 3 distributions.
A dirac delta for the zero inflation and 2 poisson or negative binomial distributions for the sometimes bimodal nature of the single-cell RNA counts.

Linear regression models could also be used as priors, using information such as batch, sequencing depth etc.
