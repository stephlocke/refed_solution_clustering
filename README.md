# ReFed data analysis

ReFed is a US nonprofit working to reduce food waste in the US. They make data available on their [ReFed](https://refed.org/) site.

This analysis will use the food waste reduction solutions dataset to help explore which solutions could be looked at in a group.

## R

The first version of this solution is written in Rmarkdown in the [R/](R) directory. The clustering file gets data from the `data/` directory, uses DataExplorer to produce initial EDA files (saved in `eda/`) and then perform k-means clustering.
