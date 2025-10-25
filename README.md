DNS Traffic Analysis and Classification
This project analyzes DNS traffic data and builds several machine learning and deep learning models to classify the traffic.

Project Steps:
Load Data: The project starts by loading the DNS traffic data from a CSV file.
Basic Statistical Summary: Basic statistical summaries and visualizations are performed to understand the data distribution and identify potential issues like missing values.
Data Preprocessing:
Missing values in numeric columns are imputed using the mean strategy.
Categorical columns are encoded using Label Encoding.
Numeric columns are standardized using StandardScaler.
Processed numeric and categorical data are merged into a final dataset.
Train-Test Split: The data is split into training and testing sets for model development and evaluation.
Model Building and Evaluation (Machine Learning):
Logistic Regression: A Logistic Regression model is trained and evaluated.
Decision Tree Classifier: A Decision Tree Classifier is trained and evaluated.
Random Forest Classifier: A Random Forest Classifier is trained and evaluated.
Support Vector Machine (SVM): An SVM model is trained and evaluated.
Model Building and Evaluation (Deep Learning):
Sequential Neural Network: A Sequential Neural Network is built, trained, and evaluated.
FeedForward Neural Network: A FeedForward Neural Network is built, trained, and evaluated.
Artificial Neural Network: An Artificial Neural Network is built, trained, and evaluated.
Convolutional Neural Network: A Convolutional Neural Network is built, trained, and evaluated (note: the input shape was adjusted for this model).
Recurrent Neural Network: A Recurrent Neural Network is built, trained, and evaluated (note: the input shape was adjusted for this model).
Model Evaluation Summary: The performance of all trained models is summarized using metrics like accuracy, precision, recall, and F1-score. Confusion matrices are plotted for each model.
Comparison Plot: A bar plot is generated to visually compare the performance metrics of the different models.
Dataset:
The project uses the DNS_Dataset.csv file, which contains DNS traffic data with various features and a 'Label' column indicating the class of traffic.

Dependencies:
The project requires the following libraries:

pandas
numpy
matplotlib
seaborn
sklearn
tensorflow
keras
These dependencies can be installed using pip
