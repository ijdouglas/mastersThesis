# RCADS predictive modeling
## Highlights
### Random Forest distributions
![](./rcadsMountainPlot.png)
Distributions of RCADS total *t*-score predictions generated from individual trees built on bootstrap resamples of the data. The prediction from the random forest is outlined in white and masked in green, while the dashed black line represents the true distribution of RCADS scores. Semi-transparent density curves reflect the predictions of individual trees.

### Variable importances
`source(Scripts/misc/vimPlot)`
![](./FC_vimplot.jpeg)
These are the most explanatory variables in predicting RCADS from the functional connections between (Harvard-Oxford) parcels in the brain (functional connectivity matrices). Overall, 20% of the variance is explained by the random forest model. *Generate this plot using `vimPlot.R`*

The following plot provides the variable importances of all features in the RF predicting RCADS from structural MRI volumes. 
![](./str_vimplot.jpeg)