# Fatigue Life Calculation

Welcome to the Fatigue Life Calculation repository. This README provides an overview of the criteria and algorithm used to determine the saturation in this code.

## Saturation Criterion

### Definition

The saturation criterion in this code is expressed through the following mathematical equation:

\[
\frac{\sigma_{\text{amp},i} - \sigma_{\text{amp},1}}{\sigma_{\text{amp},S} - \sigma_{\text{amp},1}} < 0.95
\]

### Parameters

The variables involved in this equation have the following meanings:

- \( \sigma_{\text{amp},i} \) represents the amplitude of the stress (maximal or minimal stress) at cycle \( i \).
- \( \sigma_{\text{amp},1} \) stands for the amplitude of stress during the first cycle.
- \( \sigma_{\text{amp},S} \) signifies the amplitude of the stress at the saturated cycle.

### Usage

By applying this criterion iteratively, it becomes possible to determine the point of saturation. This algorithm is particularly valuable for defining the saturation of strain-controlled samples. It closely monitors the saturation of the maximal stresses, allowing for the extraction of the saturated strain range.

Thank you for exploring our Fatigue Life Calculation code. Please refer to the "Getting Started" section for instructions on using this codebase effectively.
