### Adaptation of mbpca from mogsa package for improved capability 
##### Anna Konstorum (anna.konstorum@yale.edu)

#### Purpose 
To adapt the [mbpca](https://github.com/mengchen18/mogsa/blob/master/R/mbpca.R) code from the [mogsa](https://github.com/mengchen18/mogsa) package for improved and extended capability to apply MCIA and CPCA to multi-omics data.

##### Updates include:
1. Scaling function to scale by features (not samples).
2. Added option to perform a normalized centered row profile pre-processing using the dudi.nsc function.
3. Added option to block-normalize using sum of eigenvalues from SVD.
4. Added function to calculated global scores on new data that was not used to create the original model.

