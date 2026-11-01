# Titanic Survival Prediction

A binary classification project that compares multiple machine learning
models on the Titanic dataset.

## Approach
1. Data cleaning and missing value handling
2. Categorical encoding
3. Train/test split (80/20, random_state=42)
4. Feature scaling (StandardScaler, fit on train only)
5. Train and evaluate multiple models on the same split

## Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 80.3% |
| KNN (k=5) | 79.2% |

*More models coming soon.*

## Run
pip install -r requirements.txt
jupyter notebook
