 Heart Disease Prediction

This project focuses on building a machine learning model to predict the likelihood of heart disease based on medical and demographic features. It involves data exploration, visualization, feature scaling and selection, and experimentation with multiple classification algorithms. The objective is to assist in early diagnosis by identifying patterns and key indicators in patient data.

## 📌 Objective

To predict whether a person is likely to have heart disease using supervised machine learning techniques. The model helps in understanding feature importance and can potentially assist medical practitioners in decision-making.

## 🧠 Algorithms Used

- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
## 📊 Dataset

- The dataset contains various medical attributes such as age, sex, resting blood pressure, cholesterol levels, fasting blood sugar, maximum heart rate achieved, etc.
- Target variable: `Presence of heart disease` (binary classification: 1 = presence, 0 = absence)

## ⚙️ Workflow

1. **Data Loading & Cleaning**
   - Loaded dataset using Pandas
   - Checked for null values and handled inconsistencies

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions (histograms, boxplots)
   - Analyzed correlations using heatmaps
   - Compared feature distributions across the target variable

3. **Feature Scaling**
   - Applied standardization to numerical features to ensure uniform scale
   - Used `StandardScaler` from `sklearn.preprocessing`

4. **Feature Selection**
   - Selected relevant features based on correlation and variance
   - Removed low-importance or redundant features

5. **Model Training**
   - Split data into training and testing sets (e.g., 80:20)
   - Trained KNN, Decision Tree, and Random Forest classifiers
   - Tuned hyperparameters where necessary

6. **Evaluation**
   - Evaluated models using accuracy score
   - Compared results to identify the best-performing algorithm

## ✅ Results

- Achieved a maximum accuracy of **84%**
- Random Forest performed the best among the tested models
- Visualizations helped in understanding which features (e.g., age, cholesterol, max heart rate) most affect prediction
