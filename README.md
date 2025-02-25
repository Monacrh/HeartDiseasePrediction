## Heart Disease Prediction using KNN and Decision Tree ## 

Member:
- Ari Ramadhan 
- Bryan Dhaniel 
- Romario Viegas Fransisco Marcal

### Explanation of the Problem to Be Solved
Heart disease is a leading cause of death globally. Early detection and diagnosis of heart disease are crucial for effective treatment and prevention of serious health complications. This dataset contains various medical features that can help identify patients at risk of developing heart disease. The objective of this problem is to use the provided features to predict whether a patient has heart disease or not.

### Explanation, Statistics, and Sources of the Dataset Used
This dataset was sourced from Kaggle and contains 14 features of medical and demographic features, such as:

- Age: The patient's age (numeric).
- Sex: Gender of the patient (1 = male, 0 = female).
- Chest Pain Type (cp): The type of chest pain experienced by the patient (categorical).
- Resting Blood Pressure (trestbps): The patient's resting blood pressure (numeric).
- Serum Cholesterol (chol): The level of serum cholesterol in the blood (numeric).
- Fasting Blood Sugar (fbs): Whether the patient’s fasting blood sugar level is above 120 mg/dl (binary: 1 = true, 0 = false).
- Resting Electrocardiographic Results (restecg): The results of the patient's resting electrocardiographic test (categorical).
- Maximum Heart Rate (thalach): The maximum heart rate achieved by the patient during exercise (numeric).
- Exercise Induced Angina (exang): Whether the patient experienced angina during exercise (binary: 1 = yes, 0 = no).
- Oldpeak: Depression induced by exercise relative to rest (numeric).
- Slope: The slope of the peak exercise ST segment (categorical).
- Number of Major Vessels (ca): The number of major vessels colored by fluoroscopy (numeric).
- Thalassemia (thal): The thalassemia type of the patient (categorical).
- Target: The occur of heart disease (binary: 1 = presence, 0 = absence).

### Explanation of Dataset Pre-Processing
- Handling missing and duplicated data. We identified and imputed missing values and duplicated data where applicable, even though the dataset already mentioned that there is no missing data but we think that it is a best practice to always check it.
- Outlier detection. We identified outliers using boxplot and there's outlier.
- Remove Outlier, since we have an outlier we have to remove it


### Training and Testing Distribution Mechanism
The dataset was split into training and testing subsets to evaluate model performance effectively. The split ratio was 70% for training and 30% for testing. To further validate the model's performance, Stratification to handle potential class imbalance and k-fold cross-validation were employed during the training phase, providing a more reliable evaluation by testing the model on different data partitions.


Dataset Page: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data
