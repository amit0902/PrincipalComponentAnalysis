# PrincipalComponentAnalysis
## This has PCA model
 #### I have approached this data-set with Standardization of Data-Frame.
 #### Post Transformation, i have applied  PCA (Principal Component Analysis) to reduce dimension to get better analysis.
 #### After PCA on Standardized Data, then applied different clustering method as mentioned in Problem Statement:
         -- H-Cluster
         -- K-Means 
 #### For every clustering method Silhouette Score was a metric to verify Cluster Number.
 #### I have used Yellow-brick Library which i explored on previous assignment.
 #### Furthermore i have used 3-D plot for 3 PCA components.
 #### Additionally applied tSNE on dataset to check ouput, plotted tSNE output.

## Conclusions:

-- From PCA we can verify that the 3 clusters formed for each type is near to original data-frame.
-- t-SNE should be used for a Non-Linear High Dimensional Model to verify its performance compared to PCA.

## Note:
#### For this assignment i have attached jupyter notebook file and 2 csv files having clusters namely:
-- PCAHdfStd, PCAKdfStd
