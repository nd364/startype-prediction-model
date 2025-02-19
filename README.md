# startype-prediction-model
This project focuses on predicting the type of a star based on its physical characteristics, such as temperature, luminosity, radius, and absolute magnitude. The dataset contains information about 240 stars, categorized into six different star types.

Data Processing & Feature Engineering:
The dataset was cleaned by removing missing values and duplicates.
Categorical variables like Star Color and Spectral Class were converted into numerical values for machine learning models to process.
Features were standardized using RobustScaler and StandardScaler to improve model performance.

Machine Learning Models Used:
Stochastic Gradient Descent (SGD) Classifier
A linear model trained using gradient descent.
Achieved ~84% accuracy in cross-validation.
Random Forest Classifier
A more powerful ensemble model using multiple decision trees.
Performed significantly better, achieving 100% accuracy in some cases.
