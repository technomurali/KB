5\. Feature Engineering (Create Intelligence from Data)
-------------------------------------------------------

**Goal:** Extract **useful signals** from raw data.


**Feature engineering** is the process of creating, selecting, and transforming raw data features into meaningful inputs that improve a machine-learning model’s performance.


  
**Features** are the individual measurable input variables (attributes) of data that a machine-learning model uses to learn patterns and make predictions.

### Sub-steps

*   Create new features (ratios, differences, aggregates)
    
*   Extract features from text (TF-IDF, embeddings)
    
*   Extract features from images (edges, CNN features)
    
*   Extract time-based features (lags, rolling windows)
    
*   Domain-specific feature creation
    

**Outcome:** Higher information density.



**Feature scaling** in ML is the process of transforming features to a common numerical range or scale so that no feature dominates learning due to its magnitude. it should be applied always to columns.


**Types of feature scaling in Machine Learning:**

1.  **Min–Max Scaling (Normalization)** – rescales features to a fixed range, usually \[0,1\].
    
2.  **Standardization (Z-score scaling)** – transforms features to have mean 0 and standard deviation 1.
    
3.  **Robust Scaling** – scales features using median and interquartile range, resistant to outliers.
    
4.  **MaxAbs Scaling** – scales features by dividing by their maximum absolute value (range \[−1,1\]).
    
5.  **Unit Vector Scaling (Normalization by norm)** – scales features so their vector norm becomes 1.


**Dependent variables** are the output (target) values that a model aims to predict and that depend on the input features.


**Independent variables** are the input features that influence or explain changes in the dependent (target) variable.







