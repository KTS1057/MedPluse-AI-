
<div align="center">

# 🩺 MedPulse AI — Clinical Decision Support System

[![Live Demo](https://img.shields.io/badge/Live_App-Streamlit_Cloud-%23FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://medpluse.streamlit.app/)
[![Model Accuracy](https://img.shields.io/badge/Accuracy-88.4%25-brightgreen?style=for-the-badge)](https://medpulse-app.streamlit.app/)
[![ROC-AUC](https://img.shields.io/badge/ROC--AUC-0.92-blue?style=for-the-badge)](https://medpulse-app.streamlit.app/)
[![Status](https://img.shields.io/badge/Status-Active_&_Deployed-success?style=for-the-badge)](#)

*An end-to-end, transparent healthcare machine learning system delivering real-time risk stratification for Diabetes and Cardiovascular diseases.*

[🌐 Launch MedPulse AI Portal](https://medpulse-app.streamlit.app/) 

---

</div>

## 📌 Executive Overview

Traditional clinical AI tools often operate as opaque **"black boxes,"** generating risk outputs without explaining the underlying biological factors. **MedPulse AI** bridges this critical trust gap by incorporating **Explainable AI (XAI)** directly into a live diagnostic workspace. 

By calculating and rendering dynamic feature importance vectors, the system allows healthcare providers and patients to pinpoint exactly which clinical metrics—such as glucose concentration, blood pressure, or chest pain indicators—drive each risk classification.

---

## 🛠️ Tech Stack & Ecosystem

<p align="left">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/streamlit-%23FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=Plotly&logoColor=white" alt="Plotly" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

---

## 📊 Model Performance & Validation

The core ML engine employs a **Random Forest Ensemble** architecture, trained on multivariate clinical datasets and validated via rigorous **5-Fold Cross-Validation** to prevent overfitting and guarantee real-world generalization.

| Evaluation Metric | Score Achieved | Clinical Impact |
| :--- | :---: | :--- |
| **Model Accuracy** | **88.4%** | Highly reliable baseline for early-stage screening |
| **ROC-AUC Score** | **0.92** | Strong discriminative capability between high/low risk classes |
| **Validation Method** | **5-Fold CV** | Eliminates data leakage and variance across subsets |

---

## 🌟 Key Capabilities & Features

* **🫀 Dual Diagnostic Portals:** Dedicated, independent risk assessment modules tailored specifically for **Cardiovascular Health** and **Diabetic Indicators**.
* **🔍 Explainable AI (XAI) Engine:** Translates complex `feature_importances_` matrices into clear visual charts, making predictions fully interpretable.
* **🎨 Glassmorphic Dashboard UI:** Modern dark-mode interface built with Streamlit, Plotly visual gauges, and custom CSS styling.
* **⚡ Optimized Caching:** Memory-efficient model loading using Streamlit resource management (`@st.cache_resource`) for sub-second inference speeds.

---

## 🔄 Pipeline & Architecture Workflow

```markdown
```text
[ Patient Biometric Data ] 
           │
           ▼
[ Feature Preprocessing & Scaling ]
           │
           ▼
[ Random Forest Ensemble Engine ] ──► (Generates Prediction Probability)
           │
           ▼
[ XAI Importance Vector Extraction ] ──► (Calculates Feature Weights)
           │
           ▼
[ Interactive UI / Plotly Gauge & Radar Charts ]



## 📂 Project Structure

<pre>
├── assets/                  # Visual assets and styling components
├── models/
│   ├── diabetes_model.pkl   # Serialized Random Forest model for diabetes
│   └── heart_model.pkl      # Serialized Random Forest model for heart disease
├── app.py                   # Main Streamlit application and UI logic
├── requirements.txt         # Environment dependencies
└── README.md                # Technical documentation
</pre>

---

## 💡 Engineering Concepts Applied

* **Ensemble Learning:** Combined decision trees via Random Forest models to minimize variance and stabilize predictions across complex biometrics.
* **Global Feature Importance Mapping:** Extracted structural model weights to demystify black-box decision logic for medical professionals.
* **Stratified Risk Scoring:** Normalized raw multivariate physiological variables into unified risk indices.
* **State Management:** Implemented caching strategies to handle large serialization objects seamlessly without sacrificing memory or speed.

---

## 🎓 Key Learning Outcomes

* Built an end-to-end Machine Learning pipeline from data cleaning and scaling to model serialization (`.pkl`).
* Integrated custom Python machine learning models into a real-time web application framework using Streamlit.
* Translated abstract statistical attributes (`feature_importances_`) into intuitive graphical dashboards.
* Deployed and maintained cloud-hosted machine learning applications integrated with GitHub version control.

---

## 🔮 Roadmap & Future Scope

- [ ] **Survival Analysis:** Implement time-to-onset probability models for chronic long-term conditions.
- [ ] **EHR Integration:** Connect to standardized healthcare APIs (e.g., FHIR) for automatic record syncing.
- [ ] **Automated Optimization:** Incorporate Optuna/GridSearchCV pipelines for dynamic hyperparameter tuning.
- [ ] **Exportable Diagnostics:** Add one-click PDF report generation for clinician records.

---

## 👩‍💻 Developed By

**Kratarth Srivastava**  
*B.Tech in Artificial Intelligence & Data Science*  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
