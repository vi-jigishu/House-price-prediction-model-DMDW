# House Prices Prediction Model(Predictive modelling)

### (Note: All the data visualization graphs are eaily accessible in the .ipynb file along with the code. Thank you.)

## Motivation

The housing market is one of the most critical sectors in the global economy, influencing everything from personal wealth to national economic policies. Accurate prediction of house prices can benefit various stakeholders, including buyers, sellers, real estate agents, and financial institutions. This project aims to build and evaluate different machine learning models to predict house prices based on a variety of features like lot size, year built, and the number of rooms. By doing so, we hope to provide insights into the most important factors influencing house prices and create a robust model that can make reliable predictions.

## Dataset collectio

For the model i browsed datasets available on Kaggle and decided to use the classic House-Price-prediction dataset to practice the predictive modelling techniques i have learned. This model aims to predict the house prices in various locality across USA depending on more than 40 parameter, of which i have tested and selected some 9 odd parameters for my model. 

## Models Used
I have trained the model over 4 different algotithims and found teh Gradient Boosting tcehnique to be teh most accurate, although the random forest method produced closely accurate results, by comparing the mean absolute errors of the different models. Hence the final result plots are all based on teh Gradient Boosting model.

1. **Decision Tree Regressor**: A model that splits the data into different branches to make predictions, easy to interpret but prone to overfitting.
2. **Max Leaf Node Decision Tree**: An optimized version of the decision tree with a limited number of leaf nodes to prevent overfitting.
3. **Random Forest**: An ensemble of decision trees, each trained on a different subset of the data, which improves the model's accuracy and robustness.
4. **Gradient Boosting Model**: An ensemble method that builds models sequentially, each new model focusing on correcting the errors of the previous one, leading to high accuracy.

## Key Observations

- **Feature Importance**: Features like `OverallQual`, `1stFlrSF`, and `YearBuilt` were among the most significant predictors of house prices, highlighting the importance of both the size and quality of a house.
- **Model Performance**: The Gradient Boosting Model outperformed the other models in terms of accuracy, demonstrating the effectiveness of boosting techniques in capturing complex patterns.
- **Residual Analysis**: The residuals showed that while the models performed well overall, there were some outliers where predictions deviated significantly from the actual values, indicating areas for further improvement.
- **Hyperparameter Tuning**: Adjusting parameters like `n_estimators`, `max_depth`, and `learning_rate` in the Gradient Boosting Model significantly improved the model's performance.

## Project Structure

- **Data Preprocessing**: Handling missing values(dropping the null rows).
- **Model Training and Evaluation**: Training the models on the training set, evaluating them using cross-validation, and selecting the best model based on performance metrics like Mean Absolute Error (MAE).
- **Visualization**: Visualizing feature importance, residuals, and the distribution of predictions to gain insights into the model's behavior.
- **Prediction**: Generating predictions for the test dataset and checked its accuracy by compairing with the testing dataset.





## Summary

Through this project, I’ve gained a deeper understanding of various machine learning techniques and how they apply to real-world problems, specifically in predicting house prices. I’ve learned how different models, like Decision Trees, Random Forest, and Gradient Boosting, operate and the strengths and weaknesses of each. This project has taught me the importance of data preprocessing, such as handling missing values, feature engineering, and scaling, to improve model accuracy. I've also realized the significance of hyperparameter tuning and how small adjustments can have a substantial impact on the model's performance. Additionally, visualizing data and model results has helped me better understand the underlying patterns and the effectiveness of each model.








# All the code and README file has been written by Priyanshu Bhusan, Roll.no.22052327 for submission of DMDW project, CSE37.

