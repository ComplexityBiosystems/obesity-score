# Integrative analysis of pathway deregulation in obesity
This repository contains data and code used in

F. Font-Clos, S. Zapperi, C.A.M. La Porta  
Integrative analysis of pathway deregulation in obesity  
*npj Systems Biology and Applications (accepted)*  
[insert link](https://github.com/ComplexityBiosystems/obesity-score)

### Input files
All the necessary datasets, including gene-expression data, pathway gene sets, and gene names dictionaries are stored in the [data folder](https://github.com/ComplexityBiosystems/obesity-score/tree/master/data).

### Jupyter Notebooks
The main findings of the paper can be reproduced executing the following notebooks:

1. [SVDmerge to remove batch effects and merge gene-expression data](https://github.com/ComplexityBiosystems/obesity-score/blob/master/notebooks/1.SVDmerge_to_remove_batch_effects.ipynb)
2. [Extracting the obesity signature](https://github.com/ComplexityBiosystems/obesity-score/blob/master/notebooks/2.Extracting_the_obesity_signature.ipynb)
3. [The obesity score correlates with BMI](https://github.com/ComplexityBiosystems/obesity-score/blob/master/notebooks/3.The_obesity_score_correlates_with_BMI.ipynb)

### Output files
When executing the notebooks in order, several output files are generated. These include merged gene-expression data, the obesity signature and some figures. All output files are stored in the [output folder](https://github.com/ComplexityBiosystems/obesity-score/tree/master/output)

### Installation
Please notice that you **don't need to clone** or install any of the dependencies if you just want to inspect the code and results of the manuscript. Github renders jupyter notebooks natively, so you can view all [notebooks](https://github.com/ComplexityBiosystems/obesity-score/tree/master/notebooks) online.

If you want to **run the code one your machine**, the you must clone the repository locally and install all dependencies.

### Dependencies
In addition to standard python packages such as  `numpy, pandas, matplotlib` and `seaborn`, the code uses R's [princurve](https://cran.r-project.org/web/packages/princurve/index.html) package to compute PDS via `rpy2`.

### Contact
Please contact [Francesc Font-Clos](mailto:francesc.font@gmail.com) for computational matters and [Caterina A. M. La Porta](mailto:caterina.laporta@unimi.it) for questions related to the manuscript's content.




