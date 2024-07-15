# Coding-Samurai-Task-1-

Step 1: Data Collection
We loaded the Iris dataset, which contains 150 samples with four features: sepal length, sepal width, petal length, and petal width, and three species: setosa, versicolor, and virginica. This dataset is a standard for classification tasks.

Step 2: Data Exploration
We visualized the relationships between the features using pair plots and examined basic statistical summaries. The dataset was balanced, with each species having 50 samples.

Step 3: Data Preprocessing
We encoded the categorical target variable, split the dataset into training and testing sets, and scaled the features using StandardScaler to standardize the data.

Step 4: Model Selection and Training
We chose the Logistic Regression model for its simplicity and effectiveness in classification tasks. The model was trained using the preprocessed training data.

Step 5: Model Evaluation
The model's performance was evaluated using the testing dataset, achieving an accuracy and F1-score of 1.00, indicating perfect predictions. We also calculated precision and recall, and visualized the confusion matrix.

Step 6: Prediction
We created a function to predict the species of a new flower based on its measurements, allowing for easy application of the model to new data.

Step 7: Visualization
We visualized the data using scatter plots and confusion matrices to better understand the model’s performance and the relationships between features.

Step 8: Model Tuning
We performed hyperparameter tuning using GridSearchCV to optimize the Logistic Regression model, improving its performance through cross-validation and parameter adjustments.






