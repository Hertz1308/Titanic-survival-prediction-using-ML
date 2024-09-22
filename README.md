# Titanic-survival-prediction-using-ML
In this project, I analyzed the Titanic dataset to predict which passengers survived the disaster using logistic regression. I began by loading the dataset and inspecting it for missing values and duplicates. Irrelevant columns such as Cabin, PassengerId, Name, and Ticket were removed to simplify the analysis. Missing values in the Age and Embarked columns were handled by filling them with the mean and mode, respectively, and duplicates were dropped.

I then performed exploratory data analysis (EDA) by visualizing the distribution of key variables like Survived, Pclass, Sex, Age, and Fare using bar plots, pie charts, histograms, and box plots. This helped to gain insights into the data's structure and patterns.

Next, I prepared the data for modeling by converting categorical variables like Sex and Embarked into numerical form using one-hot encoding. The dataset was then split into training and test sets (80% training, 20% testing) using sklearn. I trained a logistic regression model on the training set to predict survival outcomes.

The model's performance was evaluated using accuracy, precision, recall, F1 score, and a confusion matrix. The final results were summarized in a classification report, highlighting the model's effectiveness in predicting survival with an accuracy of approximately 79%.
