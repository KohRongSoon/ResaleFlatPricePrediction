# HousePricePrediction

This project was carried out to identify the best machine learning models for predicting the resale flat prices in Singapore. In this project, regression models(Linear Regression and Random Forest Regressor) and classification models(Random Forest Classifier & XGBoost Classifier) were trained to predict the resale flat prices. 

Each trained models were evaluated to identify which models had the best performance for the regression and classification purpose. The results are shown below. 

|                          | Linear Regression      | Random Forest Regressor |
|--------------------------|------------------------|-------------------------|
| Mean Absolute Error      | 60724.8006             | 16595.9888              |
| Mean Square Error        | 6783905289.8624        | 623174277.0079          |
| Root Mean Square Error   | 82364.4662             | 24963.4588              |
| R-squared Score          | 0.7586                 | 0.9777                  |

|                          | Random Forest Classifier | XGBoost Classifier |
|--------------------------|--------------------------|---------------------|
| Accuracy Score           | 88.16                    | 86.18               |
| Precision                | 0.8644                   | 0.854               |
| Recall                   | 0.8521                   | 0.8088              |
| F1-Score                 | 0.8579                   | 0.8277              |

From the table above, Random Forest Regressor outperformed compared to the Linear Regression model as Random Forest Regressor has a higher R-squared score of 0.9777 as compared to Linear Regressor which R-squared score is 0.7586. For the classification model, Random Forest Classifier has a higher accuracy score of 88.16 as compared to XGBoost Classifier which is 86.18.
