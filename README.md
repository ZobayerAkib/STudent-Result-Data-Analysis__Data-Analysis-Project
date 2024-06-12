## Student Result Analysis using Regression Models

### Overview

In this project, we aimed to analyze student results using machine learning regression models. We divided the dataset into an 80:20 ratio for training and testing purposes. Our goal was to predict the scores of various subjects ('math_score', 'history_score', 'physics_score', 'chemistry_score', 'biology_score', 'english_score', 'geography_score') based on the number of weekly self-study hours.

### Model Training and Evaluation

We utilized two regression models for training:
- **Linear Regression (LR)**
- **Random Forest Regression (RDF)**

After training the models, we evaluated their performance using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared (R²)**


### Results

| Model                   | MAE    | MSE     | RMSE    | R²      |
|-------------------------|--------|---------|---------|---------|
| Linear Regression (LR)  | 10.5696| 157.1996| 12.5121 | 0.0699  |
| Random Forest (RDF)    | 10.3420| 155.1183| 12.4352 | 0.0810  |

### Conclusion

Both models yielded similar results, with the Random Forest Regression slightly outperforming the Linear Regression model. However, the overall predictive performance indicates that the relationship between weekly self-study hours and subject scores may be more complex and may require further investigation or feature engineering.

### Data Source

The dataset used for this analysis is sourced from [Kaggle].
