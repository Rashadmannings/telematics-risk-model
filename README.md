# Telematics Risk Model

This project simulates a telematics-driven auto insurance pricing model. It demonstrates:
- Signal processing techniques applied to vehicle sensor data
- Feature engineering pipelines
- Risk classification using driver behavior
- Premium prediction using statistical modeling
- Streamlit dashboard for business presentation

---

### 📦 Project Goals
1. Extract telematics features (speed, acceleration, braking) from raw trip data
2. Build a risk scoring model based on driving behavior
3. Predict insurance premium based on risk and profile
4. Deliver insights via an interactive dashboard

---

### 📁 Folder Structure
telematics-risk-model/
├── data/ # Raw and cleaned data
├── notebooks/ # Jupyter notebooks for exploration and modeling
├── src/ # Reusable Python scripts (feature engineering, modeling)
├── models/ # Saved trained models
├── reports/ # Visuals, SHAP explainers, business summaries
└── README.md # Project overview

---

### 🔧 Tools Used
- Python, pandas, numpy, scikit-learn, matplotlib
- scipy.signal, tsfresh, SHAP
- Streamlit for dashboarding
- GitHub for version control
- (Optional) MLflow or DVC for experiment tracking
