# Code to estimate the saturation of the isotropic hardening of a Chaboche model 
The code is included in an example in a Jupyter Notebook. 

For more theoretical background, please check out the paper, and if you use this code or find it useful, please cite https://doi.org/10.1016/j.compositesb.2023.110715.
## Saturation Criterion

The saturation criterion in this code is defined by the following equation:

$\frac{\sigma_{\text{amp},i} - \sigma_{\text{amp},1}}{\sigma_{\text{amp},S} - \sigma_{\text{amp},1}} < 0.95$

Where:
- $\( \sigma_{\text{amp},i} \)$ is the amplitude of the stress (maximal or minimal stress) at cycle *i*.
- $\( \sigma_{\text{amp},1} \)$ is the amplitude of stress for the first cycle.
- $\( \sigma_{\text{amp},S} \)$ is the amplitude of the stress at the saturated cycle.

By performing this criterion iteratively, the saturation of a Chaboche model can be determined. This algorithm is useful for defining the saturation of strain-controlled samples. It tracks the saturation of the maximal stresses, thereby enabling the extraction of the saturated strain range.

This code is citable via Zenodo 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12771375.svg)](https://doi.org/10.5281/zenodo.12771375) 


