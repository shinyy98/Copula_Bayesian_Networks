# Copula_Bayesian_Networks
A class implementation of CBN model and its applications to financial network dependency studies.
In CBN.ipynb we first demonstrated and validated the copula density formulas and then implemented the CBN class with other helper functions. We performed test using a 4-stock network with full data and a full network with one year's data. The copula used is Clayton copula.
In CBN_Experiments.ipynb we performed experiments on the 4-stock network with one year's data, this time changing copula type to compare across uniform correlation Gaussian copula, Frank copula, Gumbel copula, and Clayton copula.
In CBN_Drawdowns.ipynb we performed experiments on a 9-stock-and-index network with one year's data and a Clayton copula model. The learning is performed separately on the returns data and on the drawdowns data to compare structural change in the resulting optimal network. 
![Full Network](29_Returns_1yr_proxy_k=1.png)
