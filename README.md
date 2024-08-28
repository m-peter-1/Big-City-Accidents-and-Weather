Overview

This project delves into the intricate relationship between weather conditions and traffic accidents in Manhattan, New York. By integrating detailed traffic collision data with corresponding weather information, the study aims to predict collision risks under varying weather conditions. The insights gained from this analysis have significant implications for dynamic insurance pricing and risk management strategies.
Packages and Tools Used

    Pandas: For data manipulation and cleaning.
    NumPy: For numerical computations.
    Matplotlib & Seaborn: For data visualization.
    Scikit-learn: For developing and evaluating machine learning models.
    TensorFlow: For building and training the Deep Neural Network (DNN) model.

Case Studies
1. Predicting Collision Risks Based on Weather Conditions

The primary focus of this case study is to develop predictive models that estimate the likelihood of traffic accidents based on weather conditions. After an initial exploratory data analysis (EDA) and comprehensive data cleaning, multiple models were created to test their predictive power.

Key models developed include:

    Linear Regression: A simple model to establish baseline predictions based on individual weather variables.
    Multiple Linear Regression: An extended model incorporating multiple weather factors, offering slightly better predictions.
    Deep Neural Network (DNN): A sophisticated model that captures non-linear relationships, significantly improving prediction accuracy.

This case study addresses critical questions: How do different weather conditions affect the likelihood of traffic collisions? Can complex models like DNNs offer more accurate predictions compared to traditional linear models? The resulting models are evaluated and compared to determine their effectiveness in predicting real-world outcomes.
2. Data Cleaning and Feature Engineering

A significant portion of the project was dedicated to refining the dataset to enhance the accuracy of the predictions. This involved:

    Handling Missing Values: Special attention was given to weather variables where placeholders like 9999.9 were used, and these were carefully managed to avoid skewing the results.
    Outlier Removal: Identifying and removing extreme values that could distort the predictions.
    Feature Engineering: Creating new features such as one-hot encoded variables for days of the week and months to better capture temporal patterns.

This case study explores how effective data cleaning and feature engineering can unearth genuine effects within the dataset while maintaining the balance between over-cleaning and preserving critical data points.
3. Model Evaluation and Test Data Predictions

The final step was to test the developed models on an independent test dataset. This phase involved:

    Evaluating Model Performance: Comparing actual collision data with predicted values to assess the accuracy of each model.
    Analyzing the DNN Model: The DNN model, in particular, showed superior performance in capturing the complex relationships between weather conditions and collision risks.

This analysis provides actionable insights into how well the models generalize to new data and highlights the importance of selecting the right model and features for accurate predictions.
