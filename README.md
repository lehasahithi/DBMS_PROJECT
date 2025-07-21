# 🏥 Unified Healthcare Data Management and Predictive Analytics

This project presents a full-stack healthcare data warehouse and analytics platform designed to centralize patient data and provide predictive insights to assist healthcare professionals. It integrates structured database design, machine learning models, and a web application to enhance healthcare decision-making and resource allocation.

---

## 🎯 Objectives

- Centralize healthcare data from various sources (admissions, mortality, pollution).
- Design a normalized Oracle RDBMS for efficient storage and querying.
- Develop machine learning models for:
  - Predicting ICU admission duration
  - Mortality risk prediction
  - Pollution-driven health deterioration
- Provide an interactive web app for real-time data visualization and prediction.

---

## 🧱 Tech Stack

| Layer           | Technology                           |
|----------------|---------------------------------------|
| Database        | Oracle SQL (RDBMS)                   |
| Backend         | Flask (Python)                       |
| Frontend        | HTML, CSS, Jinja2 Templates          |
| Data Science    | Pandas, NumPy, Scikit-learn, Joblib   |
| Visualization   | Matplotlib, Plotly, OpenCV           |

---

## 🧩 System Modules

### 📁 1. Data Acquisition & Preprocessing
- Sources: Kaggle datasets on admissions, mortality, pollution
- ETL operations: Cleaned, encoded, and transformed datasets
- Stored in an Oracle relational database using normalized schema

### 📊 2. Database Design
- Normalized tables to eliminate redundancy
- Constraints, foreign keys, and indexing for performance and integrity
- Complex SQL queries for trend and correlation analysis

### 🤖 3. Predictive Analytics Models
- **ICU Admission Duration**
  - Model: Gradient Boosting Regressor
  - MAE: 1.52, R² Score: 0.63
- **Mortality Risk Prediction**
  - Model: Logistic Regression with L2 regularization
  - Accuracy: 91%
- **Pollution-Driven Health Deterioration**
  - Accuracy: 99%
  - Most influential features: PM2.5, PM10, NO₂

### 🌐 4. Web Application (Flask)
- CRUD operations for all data types
- Dashboards for:
  - Age-wise admission trends
  - Pollution impact on health
  - Mortality patterns
- Embedded ML models for real-time predictions

---

## 📈 Key Results

- **ICU Prediction Model**: Enabled proactive ICU bed/resource planning
- **Mortality Prediction Model**: Identified high-risk patients for early intervention
- **Pollution Impact Model**: Proved strong correlation between pollution and hospitalizations
- **Web App**: Allowed healthcare professionals to interact with models and visualize trends

---

## 🖼️ Sample Visualizations

- Hospital admissions by age group
- Monthly mortality trends
- Air pollution concentration levels over time
- AQI vs hospital admissions correlation
- Pollution’s impact on mortality (PM2.5 & PM10)

---

## 🚀 Future Scope

- Real-time deployment using cloud and wearable data
- Advanced deep learning integration (e.g., LSTMs, RNNs)
- Expansion to include behavioral and chronic health metrics
- Mobile-friendly version for hospital staff on-the-go

---

## 👨‍💻 Authors

- Bandaru Jaya Nandini  
- Mamidi Leha Sahithi  
- Siddareddy Gari Harshika  
- Daggupati Praneesha  
- Ingeti Hemanth  
- Gayathri Ramasamy *(Supervisor)*

**Institution**:  
Amrita School of Computing, Bengaluru  
Amrita Vishwa Vidyapeetham, India
