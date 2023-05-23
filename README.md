# wine_fraud

Wine Fraud Detection using Support Vector Machines (SVM)
This project aims to detect wine fraud using Support Vector Machines (SVM) algorithm. The dataset used in this project contains various chemical properties of red and white wines, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, quality, and type. The "quality" column serves as the target variable that indicates whether the wine is genuine or fraudulent.

#**EDA**
Exploratory Data Analysis (EDA) was performed to understand the data and detect any data quality issues or outliers that might affect the model's performance. The EDA process includes checking for missing values, outliers, and examining the distribution of each feature. The visualizations such as histograms, box plots, and scatter plots were used to summarize the data.

#**Feature Engineering**
After the EDA process, feature engineering was performed to transform the data to make it more suitable for the SVM algorithm. The feature engineering process includes scaling the features using the StandardScaler function from the sklearn.preprocessing library.

#**Model Selection**
SVM algorithm was selected as the model for this project due to its ability to handle high dimensional data and its ability to classify data with non-linear boundaries. The model was trained on the training set using the SVC function from the sklearn.svm library. The hyperparameters of the model were tuned using the GridSearchCV function to achieve the best performance.

#**Model Evaluation**
The model was evaluated using the test set, and the performance was measured using various metrics such as accuracy, precision, recall, and F1-score. The model achieved a good accuracy in detecting wine fraud, which indicates that it can be used to detect wine fraud with high accuracy.

#**Conclusion**
In conclusion, this project demonstrates the effectiveness of SVM in detecting wine fraud using various chemical properties of wines. The model achieved high accuracy in detecting wine fraud, indicating that it can be used to identify fraudulent wines with high confidence
