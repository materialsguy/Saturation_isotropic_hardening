# Fatigue Life Calculation

This README explains the criteria used to determine the saturation in this code.

## Saturation Criterion

The saturation criterion in this code is defined by the following equation:

$\frac{\sigma_{\text{amp},i} - \sigma_{\text{amp},1}}{\sigma_{\text{amp},S} - \sigma_{\text{amp},1}} < 0.95$

Where:
- $\( \sigma_{\text{amp},i} \)$ is the amplitude of the stress (maximal or minimal stress) at cycle *i*.
- $\( \sigma_{\text{amp},1} \)$ is the amplitude of stress for the first cycle.
- $\( \sigma_{\text{amp},S} \)$ is the amplitude of the stress at the saturated cycle.

By performing this criterion iteratively, the saturation of a Chaboche model can be determined. This algorithm is useful for defining the saturation of strain-controlled samples. It tracks the saturation of the maximal stresses, thereby enabling the extraction of the saturated strain range.
