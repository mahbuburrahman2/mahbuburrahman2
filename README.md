<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0f2027,100:00ffd5&height=160&section=header&text=ML%20Economic%20Prediction%20System&fontSize=32&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Comparative%20ML%20Study%20for%20Economic%20Forecasting&descAlignY=60&descSize=14&descColor=9ca3af" />

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

![IEEE Paper](https://img.shields.io/badge/Research-IEEE%20Style%20Paper-00ffd5?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-4ade80?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-9ca3af?style=flat-square)

</div>

---

## Overview

A research-oriented machine learning system that analyzes and predicts economic trends using real-world datasets. The project includes a **comparative study of three ML models**, evaluated against standard regression metrics, and a live **Streamlit web app** for real-time prediction.

> 📄 An IEEE-style research paper is included in the `paper/` directory.

---

## Key Results

| Model | MAE | MSE | R² Score |
|-------|-----|-----|----------|
| Linear Regression | — | — | — |
| Decision Tree | — | — | — |
| **Random Forest** ✅ | **—** | **—** | **best** |

> **Finding:** Random Forest outperformed the other models, handling nonlinear relationships in economic data most effectively.

> ⚠️ Fill in your actual metric values above — even rough numbers (e.g. R²: 0.87) make this table 10× more impactful.

---

## Models Implemented

- **Linear Regression** — baseline predictor for linear economic trends
- **Decision Tree** — captures nonlinear splits in feature space
- **Random Forest** — ensemble method; best overall performance

---

## System Architecture

```
Raw Data
   │
   ▼
Data Preprocessing Pipeline
   │  (cleaning · normalization · feature engineering)
   ▼
Model Training Module
   │  (Linear Regression · Decision Tree · Random Forest)
   ▼
Evaluation Module
   │  (MAE · MSE · R² Score)
   ▼
Streamlit Web App  ←→  Real-time Prediction
```

---

## Project Structure

```
ML-Economic-Prediction-System/
├── data/               # Raw and processed datasets
├── notebooks/          # Exploratory data analysis
├── src/                # Core ML pipeline
├── app/
│   └── streamlit_app.py
├── models/             # Saved trained models
├── paper/              # IEEE-style research paper
└── website/            # Academic portfolio page
```

---

## Getting Started

**Clone the repo**
```bash
git clone https://github.com/mahbuburrahman2/ML-Economic-Prediction-System.git
cd ML-Economic-Prediction-System
```

**Install dependencies**
```bash
pip install -r requirements.txt
```

**Run the Streamlit app**
```bash
streamlit run app/streamlit_app.py
```

---

## Research Focus

- Comparative analysis of ML models for economic forecasting
- Predictive modeling of real-world economic indicators
- Performance evaluation using standard regression metrics
- Data-driven decision support systems

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mahbubur--rahman1-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahbubur-rahman1/)
[![Email](https://img.shields.io/badge/Email-mahbuburstechhaven%40yahoo.com-F59E0B?style=flat-square&logo=yahoo&logoColor=white)](mailto:mahbuburstechhaven@yahoo.com)

---

<div align="center">

*If this project was useful to you, a ⭐ goes a long way.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ffd5,100:0d1117&height=100&section=footer"/>

</div>
