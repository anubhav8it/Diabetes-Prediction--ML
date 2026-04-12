# Data Preprocessing

The dataset was preprocessed to improve its quality and make it suitable for model training.

First, missing values were handled using median imputation. For each feature containing missing data, the median value of that feature was calculated and used to fill the missing entries. This method is robust to outliers and helps maintain the data distribution.

Next, outliers were detected and removed using the Interquartile Range (IQR) method. The first quartile (Q1) and third quartile (Q3) were calculated, and the interquartile range (IQR = Q3 − Q1) was used to identify extreme values. Data points lying outside the acceptable range were removed to reduce noise and improve model accuracy.

After cleaning the data, feature scaling was applied using StandardScaler. This step standardized all features so that they have a mean of zero and a standard deviation of one, ensuring that all variables contribute equally during model training.

Following preprocessing, feature selection was performed using the Forward Selection method. In this approach, the model starts with no features and adds one feature at a time based on its contribution to improving model performance. At each step, the feature that provides the best improvement (based on evaluation metrics such as accuracy) is selected. This process continues until no significant improvement is observed.

Through forward selection, only the most relevant features were retained, reducing dimensionality and improving the efficiency and performance of the model.

Finally, the dataset was divided into input features (X) and the target variable (Outcome), making it ready for training the machine learning model.
