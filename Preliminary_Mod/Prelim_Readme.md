# Preliminary model creation 

- Variance Inflation Factor is calculated using the raster layers to check for multicollinearity.
- Resulting layers are input to 4 different model algorithms.
    - Random Forest
    - Generalized Linear Model
    - Generalized Additive Model
    - Ensemble Model
        - Incorporates RF, GLM, GAM

## Final model selection
The fimal model algorithm was selected based off model performance and resource investment for model creation. 

Random Forest and Ensemble performed near-identically; however, Random Forest is substantially less time and CPU intensive
