 # Probability Density Functions
 
 ## Methodology
1. **Data Loading**
   - The dataset is loaded using Pandas.
   - Only the NO₂ column is used for analysis.

2. **Data Cleaning**
   - Non-numeric values are converted to NaN.
   - Missing values are removed before processing.

3. **Data Transformation**
   - A sinusoidal perturbation is applied to the data:
     `z = x + a_r sin(b_r x)`

4. **Model Definition**
   - A Gaussian-like probability model is defined.
   - Negative log-likelihood function is constructed.

5. **Parameter Estimation**
   - Parameters (λ, μ) are estimated using Maximum Likelihood Estimation (MLE).
   - Optimization is done using the L-BFGS-B algorithm.

6. **Result Analysis**
   - Optimized parameters are obtained and analyzed.
   - Histogram and fitted curve are used for visualization.
   - output:
    <img width="223" height="57" alt="image" src="https://github.com/user-attachments/assets/2049ce73-47d9-4c29-81dd-21c3645a3fa9" />

## Results and Visualization

### Histogram of Transformed NO₂ Data
<img width="516" height="400" alt="image" src="https://github.com/user-attachments/assets/63f19489-8cb1-4360-a307-7b2d44dc9d1b" />

### MLE Fitted Curve
<img width="524" height="408" alt="image" src="https://github.com/user-attachments/assets/b41a45fe-3308-4815-b189-cae950b0ad25" />



