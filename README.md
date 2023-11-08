# Fatigue Life Calculation

This README explains the criteria used to determine the saturation in this code.

## Saturation Criterion

The saturation criterion in this code is defined by the following equation:

```markdown
$\frac{\sigma_{\text{amp},i} - \sigma_{\text{amp},1}}{\sigma_{\text{amp},S} - \sigma_{\text{amp},1}} < 0.95$

Where:

    σamp,iσamp,i​ is the amplitude of the stress (maximal or minimal stress) at cycle ii.
    σamp,1σamp,1​ is the amplitude of stress for the first cycle.
    σamp,Sσamp,S​ is the amplitude of the stress at the saturated cycle.
