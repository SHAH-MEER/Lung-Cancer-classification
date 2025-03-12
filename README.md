# 🚀 Lung Cancer Prediction using Machine Learning

## 📝 Project Overview
This project focuses on predicting the likelihood of lung cancer using machine learning models. The dataset contains various health-related attributes and a target variable indicating the presence or absence of pulmonary disease. We perform exploratory data analysis, preprocess the data, and apply machine learning models such as Logistic Regression, Decision Trees, and Random Forests to make predictions.

## 📊 Dataset
- **📂 Source:** Lung Cancer Prediction Dataset
- **📏 Size:** 5000 samples, 18 columns
- **🎯 Target Variable:** `PULMONARY_DISEASE` (Binary: 0 = No, 1 = Yes)
- **📌 Features:** Includes demographic information, lifestyle factors, and medical history (e.g., age, gender, smoking status, family history, oxygen saturation, etc.)

## 🔄 Process Workflow
### 1️⃣ Data Import & Inspection
- 📥 Load dataset into a Pandas DataFrame
- 🔍 Check data structure using `.info()`
- 🔢 Convert categorical target variable to numerical format

### 2️⃣ Exploratory Data Analysis (EDA)
- 📊 Visualize the distribution of key variables (Age, Gender, Smoking habits, etc.)
- 📉 Use histograms and bar charts to explore relationships between features and the target variable

### 3️⃣ Data Preprocessing
- 📌 Separate feature matrix `X` and target vector `y`
- 🔀 Split data into training and testing sets (80% training, 20% testing)
- 🎭 Encode categorical variables if necessary

### 4️⃣ Model Training & Evaluation
- 🤖 **Logistic Regression:** Hyperparameter tuning using GridSearchCV, evaluate accuracy and classification report
- 🌳 **Decision Tree Classifier:** Optimize `max_depth`, evaluate model performance
- 🌲 **Random Forest Classifier:** Tune `n_estimators`, assess accuracy and confusion matrix

### 5️⃣ Results & Model Performance
- 📊 Model accuracy and evaluation metrics for each classifier
- 🔎 Confusion matrices to analyze true positives, false positives, etc.

## ⚙️ Installation & Dependencies
To run this project, install the required libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## ▶️ Running the Code
Execute the script in a Jupyter Notebook or Python environment:
```python
python lung_cancer_prediction.py
```

## 🔮 Future Enhancements
- 🔍 Feature engineering and selection for better model performance
- 🤖 Testing deep learning models for improved accuracy
- 🌐 Deploying the model as a web application

## 🤝 Contributing
Feel free to contribute by improving data preprocessing, testing new models, or optimizing hyperparameters.

## 📜 License
This project is open-source and available under the MIT License. 🎉

