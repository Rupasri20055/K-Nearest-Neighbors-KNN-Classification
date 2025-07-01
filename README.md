# K-Nearest-Neighbors-KNN-Classification

Task 6: K-Nearest Neighbors (KNN) Classification

About this Task:
Hey! In this task, I worked with the Iris dataset to build a classification model using the K-Nearest Neighbors (KNN) algorithm. The goal was to classify the flower species based on their sepal and petal measurements.

 What I did in this task:
 
1️ Imported the Iris dataset using Pandas from a CSV file.

2️ Checked the number of rows, columns, and previewed the data using .head().

3️ Converted the Species categorical column into numeric values using LabelEncoder.

4️ Split the data into features (SepalLength, SepalWidth, PetalLength, PetalWidth) and target (Species).

5️ Divided the data into training and testing sets (80%-20%) using train_test_split().

6️ Standardized the numeric columns using StandardScaler so that all features are on the same scale.

7️ Fitted a KNN Classifier model using KNeighborsClassifier() with k=5 and trained it on the scaled training data.

8️ Predicted values for the test data and evaluated the model performance:

Printed Accuracy Score

Displayed Confusion Matrix

Displayed Classification Report (Precision, Recall, F1-Score)

9️ Experimented with different K values (1, 3, 5, 7, 9) to see how the accuracy changes, and plotted a K vs Accuracy graph.

10 Selected two features (PetalLengthCm and PetalWidthCm) and plotted the decision boundaries using a contour plot and scatterplot to visualize how the KNN model classifies different regions.
