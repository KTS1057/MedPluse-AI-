
<div align="center">

# 🩺 MedPulse AI — Clinical Decision Support System

[![Live Demo](https://img.shields.io/badge/Live_App-Streamlit_Cloud-%23FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://sgmwnktwncg5ezw2lpa6ho.streamlit.app/)
[![Model Accuracy](https://img.shields.io/badge/Accuracy-88.4%25-brightgreen?style=for-the-badge)](https://sgmwnktwncg5ezw2lpa6ho.streamlit.app/))
[![ROC-AUC](https://img.shields.io/badge/ROC--AUC-0.92-blue?style=for-the-badge)](https://sgmwnktwncg5ezw2lpa6ho.streamlit.app/))
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
<pre>

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

</pre>



## 👩‍💻 Developed By

**Kratarth Srivastava**  
*B.Tech in Artificial Intelligence & Data Science*  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
