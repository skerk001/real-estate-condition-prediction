# Real Estate House Condition Prediction

A machine learning project predicting residential property condition grades from real estate features, comparing multiple classification algorithms to identify the best approach for automated property assessment.

## Overview

Property condition assessment is traditionally a manual, subjective process conducted during home inspections. This project explores whether machine learning models can reliably predict a home's condition grade based on publicly available real estate data — features like square footage, year built, number of bedrooms/bathrooms, lot size, and location attributes.

## Approach

### Data Preprocessing
- Feature engineering from raw listing data
- Handling missing values and outlier detection
- Encoding of categorical variables (neighborhood, zip code)
- Feature scaling and normalization

### Models Evaluated
- **Logistic Regression** (baseline)
- **Random Forest Classifier**
- **Gradient Boosted Trees**
- **Support Vector Machine**
- **K-Nearest Neighbors**

### Evaluation
- Stratified k-fold cross-validation
- Metrics: accuracy, precision, recall, F1 score
- Feature importance analysis

## Key Findings

- Property age and square footage are the strongest predictors of condition grade
- Ensemble methods (Random Forest, Gradient Boosted Trees) outperform linear models
- Location-based features add meaningful predictive power, suggesting neighborhood effects on property maintenance

## Tech Stack

- Python 3.x
- scikit-learn
- pandas, NumPy
- matplotlib, seaborn
- Jupyter Notebook

## Author

**Samir Kerkar**  
University of California, Irvine — B.S. Mathematics  
Samir2000VIP@gmail.com
