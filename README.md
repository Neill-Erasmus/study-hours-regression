# Student Study Hours Regression

This project focuses on studying the relationship between study hours and test scores using a simple linear regression model. The dataset includes information on study hours (feature - X) and corresponding test scores (target - y).

## Linear Regression

Linear Regression is a fundamental statistical and machine learning technique used to model the relationship between a dependent variable and one or more independent variables. It assumes a linear relationship between the variables and is widely employed for predictive analysis and forecasting.

### Assumptions

Linear regression assumes a linear relationship, independence of errors, homoscedasticity, and normality of errors.

### Overfitting

Care should be taken to avoid overfitting by regularization techniques if dealing with high-dimensional data.

### Feature Scaling

Feature scaling may be beneficial for algorithms sensitive to variable scales, in this application it is not necessary.

## Dataset Overview

The dataset comprises two columns, documenting the number of hours a student studied and the corresponding marks they achieved. This dataset serves as an ideal candidate for the application of simple linear regression, where the goal is to predict a student's marks based on the number of hours they dedicated to studying.

### Features

- Hours Studied

The independent variable representing the number of hours a student spent studying.

- Marks Obtained

The dependent variable indicating the marks obtained by the student, which is influenced by the hours of study.

## Model - ```sklearn.linear_model.LinearRegression```

LinearRegression is a class in the scikit-learn library, designed for linear regression modeling. It provides an implementation of the ordinary least squares (OLS) regression algorithm, making it a fundamental tool for predictive modeling when the relationship between the independent variables and the dependent variable is assumed to be linear.

### Model Performance

The provided Mean Squared Error (MSE) of 13.88 and r-squared score of 0.97 suggest that the simple linear regression model is performing very well on the test data.

- Mean Squared Error (MSE)

The MSE value of 13.88 is relatively low, indicating that, on average, the squared differences between the actual and predicted values are small. Lower MSE values are desirable, and in this case, the model's predictions are generally close to the actual test scores.

- R-squared

The r-squared score of 0.97 is quite high, indicating that approximately 97% of the variance in the test scores can be explained by the linear relationship with the study hours. A high r-squared score suggests that the model is an excellent fit for the data and is able to capture the underlying patterns effectively.

<p align="center">
    <img src="https://github.com/Neill-Erasmus/study-hours-regression/assets/141222943/71eb53d4-873a-45dc-809c-79e4f76d963c" alt="graph">
</p>

In summary, based on these metrics, the model demonstrates high accuracy in predicting students' test scores based on their study hours. It appears to be a robust and reliable model for the given dataset.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
