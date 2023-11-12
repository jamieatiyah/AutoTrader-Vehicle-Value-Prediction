# AutoTrader Vehicle Value Prediction

This machine learning project is based on a Car Sale Adverts dataset provided by AutoTrader, one of Manchester Metropolitan University's industry partners. The dataset includes anonymized adverts with vehicle information such as make, model, color, mileage, and the selling price. The primary goal was to employ machine learning techniques to develop a regression model for predicting the selling price.

## Overview

- **Dataset:** The dataset comprises anonymized car sale adverts with various vehicle details.
- **Task:** The objective was to leverage machine learning to build a regression model for predicting the selling price.
- **Implementation:** The core machine learning modeling took place in the notebook [AutoTrader Notebook.ipynb](https://github.com/jamieatiyah/AutoTrader-Vehicle-Value-Prediction/blob/main/AutoTrader%20Notebook.ipynb).
- **Report:** A concise report, ["AutoTrader Vehicle Value Prediction"](https://github.com/jamieatiyah/AutoTrader-Vehicle-Value-Prediction/blob/main/AutoTrader%20Vehcile%20Value%20Prediction.pdf), highlights key techniques and findings from the project.

## Project Highlights

In this project, I leveraged machine learning to predict vehicle selling prices using real-world data from AutoTrader. The aim was to build a robust model that could accurately estimate a vehicle's market value based on key features.

### Key Techniques and Findings

- **Data Cleaning and Feature Engineering:** The project began with cleaning and preprocessing the dataset, addressing missing values, and engineering features to extract meaningful information.
- **Model Selection:** Extensive testing led to the identification of the Random Forest Regressor as the best-performing model for the task, showcasing superior predictive capabilities.
- **Dimensionality Reduction:** To enhance model performance, Principal Component Analysis (PCA) was implemented for dimensionality reduction, maintaining accuracy while reducing computational complexity.
- **Boosted Trees:** Exploration of Gradient Boosting Regressor and Histogram-Based Gradient Boosting Regressor models with optimized hyperparameters provided valuable insights.
- **Ensemble Modeling:** Ensemble techniques such as Voting and Stacking were employed to boost predictive power by combining multiple models.
- **Model Analysis:** Model interpretability was explored using techniques like Shap values, partial dependency plots, and permutation importance, aiding in understanding feature importance and interactions.
- **Performance on the Entire Dataset:** The final ensemble model demonstrated strong performance and generalization capabilities when applied to the complete dataset.

## Project Artifacts

- **Notebook:** The implementation details and code for the machine learning models can be found in the notebook [AutoTrader Notebook.ipynb](https://github.com/jamieatiyah/AutoTrader-Vehicle-Value-Prediction/blob/main/AutoTrader%20Notebook.ipynb).
- **Report:** A short and structured report, ["AutoTrader Vehicle Value Prediction"](https://github.com/jamieatiyah/AutoTrader-Vehicle-Value-Prediction/blob/main/AutoTrader%20Vehcile%20Value%20Prediction.pdf)), highlights key techniques and insights from the project.

## Conclusion

This project demonstrates a comprehensive approach to predictive modeling, emphasizing feature engineering, model selection, and ensemble techniques. It provides valuable insights into the vehicle pricing domain and serves as a foundation for future enhancements and applications.



