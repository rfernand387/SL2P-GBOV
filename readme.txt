This is a jupyter notebook that produces a json file with matchups of a GEE feature collection corresponding to 
GBOV in-situ measurements and the output of the LEAF-Toolbox L2B processor.  The json file contains a list
of dictionaries, one per GEE feature.  Each dictionary contains keys for the original GEE feature keys in addition to keys corresponding to sampled values from 
ALL L2B products, spatially aggregated using a specified filter, matching the feature spatially and temporally within specified windows in space and time.

An second notebook is provided that allows visualization in terms of scatter plots BUT this is specific to 
certain datasets such as LAI and fAPAR.



