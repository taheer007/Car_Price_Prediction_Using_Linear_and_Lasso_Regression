# Car_Price_Prediction_Using_Linear_and_Lasso_Regression
This project implements machine learning models to predict used car prices based on various features such as car name, manufacturing year, kilometers driven, fuel type, seller type, transmission, and ownership details.
Project Overview:
This project focuses on predicting the selling price of used cars using machine learning regression techniques. Accurate car price prediction can help buyers and sellers make informed decisions and can be useful for car dealers, insurance companies, and online marketplaces.

We use two popular regression models—Linear Regression and Lasso Regression—to analyze the impact of various car features on the selling price and to build predictive models that generalize well on unseen data.

Objectives:
Understand the relationship between car features and their selling price.
Perform data cleaning and preprocessing, including encoding categorical variables and handling missing values.
Build and train regression models to predict car prices.
Compare the performance of Linear Regression and Lasso Regression.
Evaluate models using metrics such as R² Score and Mean Absolute Error (MAE).
Visualize data distributions and model results to gain insights.

Methodology:
1. Data Preprocessing:
    Loaded the dataset and checked for missing values.
    Converted categorical variables into numerical form using one-hot encoding.
    Split the dataset into training and testing sets.

2. Model Training:
    Trained a Linear Regression model as a baseline.
    Trained a Lasso Regression model with hyperparameter tuning to reduce overfitting and improve generalization.

3. Model Evaluation:
    Used R² Score and MAE to evaluate prediction accuracy.
    Compared both models to select the best-performing one.

4. Visualization:
     Used Matplotlib and Seaborn to plot feature distributions, correlations, and model performance.

5. Tools and Libraries Used
     Python: Programming language used for implementation.
     Pandas & NumPy: For data manipulation and numerical operations.
     scikit-learn: For building and evaluating machine learning models.
     Matplotlib & Seaborn: For data visualization.
     Jupyter Notebook: For interactive development and visualization.

Results:
  Linear Regression provided a good baseline prediction of car prices.
  Lasso Regression improved model generalization by reducing coefficients of less important features, helping to prevent overfitting.
  Achieved an R² score of approximately 0.03820080045916885 with the Lasso model, and 0.42080045916885 withLinear model indicating good predictive accuracy.

