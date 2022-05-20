# Application of Machine Learning on a Dataset

### Data Preprocessing

Firstly, Data Preprocessing has been done which includes-

1. Load the dataset as dataframe using pandas

2. Handle missing values if needed

3. Encode categorical features if needed

4. Scale all the values between 0-1 with proper scaling technique

5. Perform Classification. Split the dataset into features and labels. (The last column which is 'income\_>50K' has been considered as the label or class)

### Comparing Accuracy of Linear Regression and Decision Tree on the Dataset

1. Perform classification and calculate accuracy using logistic regression. Perform necessary pre-processing on the dataset before classification. Use 8:2 train-test split.

2. Perform classification and calculate accuracy using decision tree. Perform necessary pre-processing on the dataset before classification. Use 8:2 train-test split.

3. Compare the accuracy and plot them as a bar chart using matplotlib/seaborn.

### Comparing Accuracy of Support Vector Machine (SVM), Neural Network (Multilayer Perceptron Classifier) and Random Forest machine learning classifiers pre-PCA and post-PCA

1. Apply necessary pre-processing steps on it

2. Divide the dataset into 8:2 train-test split and perform Support Vector Machine, Neural Network (MLPClassifier) and Random Forest on it.

3. Perform dimensionality reduction using PCA. Reduce the number of feature vectors into half

4. Apply Support Vector Machine, Neural Network (MLPClassifier) and Random Forest again on the reduced dataset.

5. Compare the accuracy of the pre-PCA and post-PCA results. Plot them against each other in a bar graph.
