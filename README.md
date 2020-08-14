# Machine Learning Ressources
### Files

Requires Python and Jupyter Notebook to run

```sh
ML_algorithms
ML_pipeline
```
### Machine Learning Alogithms `(ML_algorithms)`
- Machine Learning algorithms in `python.sklearn`

#### Machine Learning Pipeline `(ML-pipeline)`

Python file that goes through the whole ml process. And consists of:
- **Relevant module imports**
    - Data handling
    - Data Plotting
    - ML Base modules
    - ML Analysis
    - Neural Networks (with `python.pytorch`)
- **Data ingestion**
    - import of various data files
- **Data Preparation and Exploration**
    - Count
    - Visual Exploration
- **Data Handling**
    - Missings
    - Imputations
        - *Imputation with *mean*
        - *Imputation of categorical variables*
        - *Imputation based on distribution*
    - Dichotomization
        - *Binary*
        - *Categorical*
    - Standartization (Scaling)
    - Recursive Feature Elimination (RFE)
    - Correlation matrix
- **Data Segregation**
    - Train/Test split
    - Train/Validate/Test Split
- **Machine Learning Algorithms: Regression**
    - Linear
    - Ridge, Ridge CV
    - Lasso, Lasso CV
    - Elastic Net, Elastic Net CV
    - Robust Regressions
        - *RANSAC*
        - *TheilSen*
        - *Huber*
- Regression Model Selection
    - MAE
    - MSE
    - RMSE
    - R²
    - Adj. R²
- **Machine Learning Algorithms: Classification**
    - Logistic Regression
    - Gaussian Naive Bias 
    - Gaussian Naive Bias for multinominal Models
    - K-Neighbors Classifier
- **Classifiaction Model Selection**
    - Accuracy Score
    - Confusion Matrix
    - Precision Score
    - F1-Score
    - Classification Report
    - Log-Loss (Logistic loss, cross-entropy loss)
    - ROC-Score, AUS-Score
        - *Plotting with pyplot*
    - Calibration Plot
- **Neural Networks**
