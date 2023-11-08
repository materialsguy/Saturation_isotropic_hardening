# Fatigue_life_Cu
 
The saturation criterion in this code is defined by: 
(σ_(amp,i)-σ_(amp,1))/(σ_(amp,S)-σ_(amp,1) )  < 0.95
Where σ_(amp,i) is the amplitude of the stress (maximal or minimal stress) at cycle i, σ_(amp,1) the amplitude of stress for the first cycle, and σ_(amp,S) the amplitude of the stress at the saturated cycle.

By performing this criterion iteratively, the saturation can be determined.
The algorithm can be used to define the saturation of the strain-controlled samples.
he algorithm tracks the saturation of the maximal stresses, thereby enabling the extraction of the saturated strain range.
