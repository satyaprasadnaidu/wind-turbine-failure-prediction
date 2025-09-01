# 🌪️ Early Failure Prediction in Wind Turbines

This project focuses on predicting **early equipment failures in wind turbines** using sensor data.  
The aim is to detect unusual patterns in turbine behavior that could lead to failures, allowing for **preventive maintenance** and reduced downtime.

---

## 📌 Project Overview
Wind turbines are equipped with multiple sensors that monitor parameters like **temperature, power output, and wind speed**.  
Using this data, we built **machine learning models** to classify whether a turbine is healthy or at risk of failure.

- **Supervised Model:** LightGBM (Gradient Boosted Trees)  
- **Unsupervised Model:** Isolation Forest (Anomaly Detection)  
- **Evaluation Metrics:** Precision, Recall, and F1 Score  

The final results show that our models can **accurately predict failures**, which can help improve reliability and cost savings in renewable energy systems.

---

## ⚡ Workflow

### 🔹 Step 0: Setup
- Imported required Python libraries:
  - **pandas, numpy** → data handling
  - **scikit-learn** → preprocessing, model training, evaluation
  - **lightgbm** → gradient boosting classifier
  - **matplotlib & seaborn** → visualizations

### 🔹 Step 1: Data Loading
- Loaded wind turbine sensor data (CSV/Excel format).
- Combined multiple files when needed or worked with individual files.
- Inspected dataset size, columns, and missing values.

### 🔹 Step 2: Data Preprocessing
- Handled missing values.
- Scaled features using **StandardScaler**.
- Split dataset into **training (80%)** and **testing (20%)**.

### 🔹 Step 3: Model Training
- **LightGBM Classifier (Supervised Learning):**
  - Predicts turbine failure vs healthy state.
- **Isolation Forest (Unsupervised Learning):**
  - Detects anomalies in sensor readings without labeled failures.

### 🔹 Step 4: Model Evaluation
- Calculated **Precision, Recall, F1 Score**.
- Generated **classification report**.
- Visualized distribution of important sensor readings.

### 🔹 Step 5: Visualization & Dashboard
- Created charts for:
  - Distribution of wind speed
  - Predicted vs actual failures
  - Correct vs wrong predictions
- Built a **dashboard** showing KPIs:
  - Precision
  - Recall
  - F1 Score

---

## 📊 Results

- **LightGBM (Supervised):**
  - Precision: **0.99**
  - Recall: **1.00**
  - F1 Score: **1.00**

- **Isolation Forest (Unsupervised):**
  - Precision: **0.30**
  - Recall: **0.53**
  - F1 Score: **0.33**

✅ The supervised model clearly outperformed the unsupervised one.  
This shows the importance of labeled data in predictive maintenance.

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** (data processing)  
- **Scikit-learn** (ML models & evaluation)  
- **LightGBM** (supervised classifier)  
- **Matplotlib, Seaborn** (EDA & plots)  

---

## 📈 Sample Visualizations
- Distribution of wind speed  
- Actual vs Predicted Failures  
- KPI Dashboard with Precision, Recall, F1 Score  

---

## 🚀 Key Takeaways
- Machine Learning can effectively predict early failures in wind turbines.  
- Preventive maintenance helps **reduce downtime and repair costs**.  
- Supervised methods like LightGBM provide **high accuracy** when labeled data is available.  

---

## 👨‍💻 Author
**Satya**  
B.Tech (Final Year) | Data Science Enthusiast  
# wind-turbine-failure-prediction
