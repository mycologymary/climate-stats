This repository contains an analysis of monthly average rainfalls in Melbourne and Oxford, from 1855-205.

To run this analysis use the following command to generate a combined dataframe for the two cities:

```
Rscript src/combine-data.R
```

Then use this command to create a visualisation:

```
Rscript src/make-plot.R
```

The input data is in `data`. The results of the analysis are in `out`.

Sources for the data used are found in the file _data-sources.txt_.
