# Classification-Modeling
The dataset is a sample that contains patients’ information (demographics
and medical data) that relates to heart disease prediction.

The features are:

Age: age of the patient [years]

Sex: sex of the patient [M: Male, F: Female]

ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]

RestingBP: resting blood pressure [mm Hg]

Cholesterol: serum cholesterol [mm/dl]

FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]

RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]

MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]

ExerciseAngina: exercise-induced angina [Y: Yes, N: No]

Oldpeak: oldpeak = ST [Numeric value measured in depression]

ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

HeartDisease: output class [1: heart disease, 0: Normal]

As a data analyst, we are going to answer the following questions to obtain insights about the
data and to conduct predictive modeling to forecast the presence of heart failure (variable
HeartDisease).

1. Exploratory data analysis 
a) Get a description, general information, data types, and shape of the dataset.

b) Determine the frequency of distinct values for each feature in the dataset.

c) Plot all features in the dataset to check distribution using a histogram.

d) Use a correlation matrix to check for correlation between predictor variables and drop correlated features (> 0.5).

2. Feature Engineering 

a) Check and drop duplicate and missing values, if it’s the case.

b) Check and manage imbalance class, if needed.

c) Check (Use boxplots) and take care of outliers (e.g. Cholesterol, Oldpeak) by completing imputation.

d) Convert categorical data into numerical data using one-hot encoding or any other label encoding approach.

e) Rescale features to a narrow range using a normalization or standardization function.

3. Modeling 

a) Partition your data in test (30%) and training (70%).

b) Use KNN, SVM, and Decision Tree Classifier classifiers to predict the class.

4. Model evaluation and Selection 

a) Using the function GridSearchCV find the best estimators (criterion, max_depth, min_samples_leaf) for your DT model.

b) Using the best parameters for the DT run the model and get the prediction.

c) Compare the results of the models based on the metrics: precision, recall, accuracy, F-measure from steps 3.b and 4.b.

d) Plot the ROC graph for each model and compare the performance for each one (3.b and 4.b).

e) Explain which is the best model according to each criterion from 4.c) and 4.d).
