# LOBICO
## LOBICO in MATLAB, plot in R
### What's it
- A script used to convert the gene expression matrix into binary, hence to apply LOBICO to find the logic model
- Without complex machine learning, you can get the simple logic model of genes to detect different cancers.
- The LOBICO model will depends on CPLEX

### How it works
- Place expression matrix in ~/data, then finish binarization
- Obtain the model using MATLAB & CPLEX in ~/Model; the parameters of model can be adjusted
- Train the classification model, and get the results into the confusion table
