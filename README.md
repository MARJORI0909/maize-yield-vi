# maize-yield-vi
Modelling grain corn yield prediction using vegetation indices and seed rate as predictors. 
Objective: Identifying the optimal prediction date and the most informative variables (predictors) for grain yield prediction
Variables: (1) VIs: EVI, GNDVI, NDMI, NDRE B5, NDRE B6, NDVI, OSAVI, (2) Agronomic variable: Seed rate
Target variable: grain yield (t/Ha)
Remote sensing data: VIs data derived from Sentinel-2A imagery 
Temporal variable: Days after sowing (DAS)
Training data: plot 116
Validation data: plot 113 

01_packages/
    R packages and libraries required for the analysis

02_data_structure/
    Data preparation, cleaning and organization

03_model_functions/
    Functions used for statisticalmodels

04_graphics/
    Generating figures

05_correlations/
    Correlation analysis between yield, agronomic variable and VIs

06_pca/
    Principal Component Analysis

07_predictive_data/
    Preparation of datasets used for yield prediction

08_functions adjust model/
   Functions for fitting and evaluating yield prediction models.
   
09_models/
   Creation of models based on PCA and Pearson correlation visualization

10_metrics/
   Model performance metrics for evaluating grain yield predictions: R2, RMSE, MAE

11_equation/
   Prediction equation

12_residuals/
   Normality and heteroscedasticity evaluation for training data



Data availability
The raw experimental are not publicly available due to data-sharing restrictions. The repository contains the scripts required to process, analyse, and model the data.
