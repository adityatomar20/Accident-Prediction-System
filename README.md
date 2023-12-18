# Accident Severity Prediction and Analysis

### Project Overview:
In this project, I developed a machine-learning model to classify the severity of accidents based on various features. The goal was to gain insights into accident patterns, identify regions with the highest accident frequencies, and determine peak accident times. Additionally, the model aimed to differentiate the number of accidents per hour and month to provide a comprehensive understanding of accident occurrences.

### Data Preprocessing:
The dataset was loaded from a CSV file containing information such as severity, time, location (latitude and longitude), and other relevant attributes.
Initial data exploration revealed an unbalanced dataset, prompting the removal of rows with severity values of 0, 1, or 4.
Feature Engineering:
Sales-related Features: Engineered features such as lag sales for different periods and rolling sales, capturing the trend component in accident occurrences.
Price-related Features: Incorporated features like the maximum, minimum, and standard deviation of prices for each product to consider pricing dynamics.
Calendar-related Features: Utilized calendar-related information, including weekdays and months, to account for temporal variations in accident patterns.

### Exploratory Data Analysis (EDA):
Conducted EDA through various visualizations, including a severity vs. count bar chart to understand the distribution of accident severities.
Analyzed outliers and boundaries to refine the dataset.

### Univariate Analysis:
Examined the number of accidents by the hour using a countplot, providing insights into peak accident times.
Investigated the number of accidents by month and weekday to identify any temporal patterns.

### Geographic Analysis:
Plotted accident severity on a map using latitude and longitude coordinates, differentiating between severity levels 2 and 3.
Time Analysis:
Explored the ratio of severity 0 and 1 concerning the hour of the day, revealing insights into the timing of accidents and their severity.

### Machine Learning Models:
Trained several machine learning models, including Multinomial Naive Bayes, K-Nearest Neighbors, Logistic Regression, Decision Tree, Random Forest, and Support Vector Machines.
Evaluated model performance using metrics such as accuracy, precision, recall, and F1 score.

### Feature Importance:
Determined the most important features for accident severity prediction, with latitude and longitude being identified as crucial predictors.

### Model Selection:
Choose decision tree and random forest models as they exhibited superior performance in terms of accuracy, recall, precision, and F1 score.
Learning Curve Analysis:
Explored the impact of training set size on model accuracy, revealing insights into the effectiveness of model learning with varying dataset sizes.

### Conclusion:
The developed model successfully predicts accident severity, offering valuable insights for strategic and tactical decision-making in accident management and prevention. The project showcases the importance of feature engineering, exploratory data analysis, and machine learning in understanding and predicting accident patterns.





