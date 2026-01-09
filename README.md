# House Price Prediction with SHAP (Linear Regression)

This project demonstrates how SHAP (SHapley Additive exPlanations) can be used
to interpret a Linear Regression model trained on a real-world housing dataset.

## Objective
- Train a house price prediction model using Linear Regression
- Understand how each feature contributes to predictions
- Visualize feature importance using SHAP

## Dataset
- California Housing Dataset (from scikit-learn)
- Contains information such as median income, house age, number of rooms,
  population, and geographic location

## Model Used
- Linear Regression

## Why SHAP?
Although Linear Regression is an interpretable model, SHAP provides deeper insight
by explaining individual predictions and showing how each feature contributes
positively or negatively to the predicted house price. SHAP also provides clear
visualizations that make model behavior easier to understand.

## Explainability Techniques
- SHAP Summary Plot (global feature impact)
- SHAP Feature Importance Bar Plot

## Results
The SHAP analysis shows that features like median income and location
have the strongest influence on house price predictions, while other features
have smaller or mixed effects.

## Technologies Used
- Python
- scikit-learn
- SHAP
- Pandas
- Matplotlib

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Python script or Jupyter Notebook

## Learning Outcome
This project helped me understand model interpretability and the importance of
explaining machine learning predictions, especially for real-world applications
such as housing price estimation.

## Author

**Afrida Jahan Marjia**
CSE Student | Aspiring Machine Learning Engineer
