# Advanced ML DL Course Assignment I
Contributors: Adi Dokhan, Lilac Muhanna

## Project Overview
This project focuses on predicting daily bicycle rentals using environmental and temporal data. The dataset comprises 8,164 entries, each detailing daily conditions and rental counts. We preprocessed this data and engineered features to best expose the underlying patterns to three predictive models.

## Models Developed
1. Random Forest Regressor  
2. AdaBoost Regressor  
3. Reduced Feature AdaBoost Regressor

Each model aimed to minimize the RMSE and maximize the R^2 Score, with the best performance exhibited by the Reduced Feature AdaBoost Regressor.

## Results
Best Model: Reduced Feature AdaBoost Regressor  
Test MSE: 418.46  
R^2 Score: 0.984  
The Reduced Feature AdaBoost Regressor delivered the most accurate predictions, highlighting the significant impact of feature selection on model performance.

## Conclusion
This analysis demonstrates the effectiveness of ensemble methods in predictive modeling for count data influenced by time and environmental factors. Future improvements could explore more complex feature engineering and alternative ensemble methods.

## Libraries Used
Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
