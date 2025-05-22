# Titanic-survival-prediction-using-ml-techniques
In this project, I worked with the Titanic dataset to predict passenger survival using logistic regression. The workflow began with data loading and an initial review to identify missing values and duplicate entries. To simplify the dataset and focus on relevant features, columns such as Cabin, PassengerId, Name, and Ticket were removed. Missing values in the Age and Embarked columns were handled by imputing the mean and mode, respectively, and all duplicate records were dropped.

I then performed exploratory data analysis (EDA) to investigate the distributions and relationships of key variables including Survived, Pclass, Sex, Age, and Fare. A variety of visualizations—such as bar plots, pie charts, histograms, and box plots—were used to uncover patterns and extract meaningful insights.

Before modeling, categorical variables like Sex and Embarked were converted into numerical form using one-hot encoding. The data was then split into training and testing sets using an 80:20 ratio with scikit-learn.

A logistic regression model was trained on the processed data to predict survival outcomes. The model’s performance was assessed using evaluation metrics including accuracy, precision, recall, F1 score, and a confusion matrix. According to the classification report, the model achieved an accuracy of around 78%, indicating solid predictive capability for this classification task.
