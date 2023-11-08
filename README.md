<script type="text/javascript" async
        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>


# Fatigue_life_Cu
 
The saturation criterion in this code is defined by: 

\[
\frac{\sigma_{\text{amp},i} - \sigma_{\text{amp},1}}{\sigma_{\text{amp},S} - \sigma_{\text{amp},1}} < 0.95
\]

Where σ_(amp,i) is the amplitude of the stress (maximal or minimal stress) at cycle i, σ_(amp,1) the amplitude of stress for the first cycle, and σ_(amp,S) the amplitude of the stress at the saturated cycle.

By performing this criterion iteratively, the saturation can be determined.
The algorithm can be used to define the saturation of the strain-controlled samples.
he algorithm tracks the saturation of the maximal stresses, thereby enabling the extraction of the saturated strain range.
