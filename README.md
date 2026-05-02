# 🚦 Road Traffic Accident Severity Prediction

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=26&pause=1000&color=E24B4A&center=true&vCenter=true&width=900&lines=Road+Traffic+Accident+Severity+Prediction;Machine+Learning+%7C+Feature+Engineering+%7C+SHAP+Explainability;LightGBM+%7C+Random+Forest+%7C+SVM+%7C+%7E84%25+Accuracy" alt="Typing Animation"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/LightGBM-2F4F4F?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/SHAP-FF6B6B?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

---

## 🎯 About the Project

A machine learning project that predicts road traffic accident severity using real-world data. Five ML models were trained, compared, and explained using SHAP — with the best model achieving **~84% accuracy**.

- **Dataset:** 12,317 accident records with 32 features
- **Target:** `Accident_severity` → Slight Injury / Serious Injury
- **Best Model:** LightGBM (~84–86% accuracy)

---

## ⚡ Features

### 📊 Data Preprocessing
- Missing value imputation (mode for categorical, median for numeric)
- Label encoding for all categorical features
- Dropped low-impact columns

### 🔧 Feature Engineering
- `casualty_per_vehicle` — ratio of casualties to vehicles involved
- `accident_complexity` — casualties × vehicles involved
- `experience_risk` — driver age × driving experience
- `traffic_cluster` — K-Means clustering on accident patterns

### 🤖 Models Trained & Compared

| Model | Performance |
|-------|-------------|
| Logistic Regression | Lower |
| Decision Tree | Moderate |
| Random Forest | High |
| SVM | Moderate |
| **LightGBM** | **Best (~84–86%)** ✅ |

### 🔍 Explainability
- **SHAP values** used to explain individual predictions
- **Feature importance** analyzed across 5 algorithms
- Top predictors: `Number_of_casualties`, `Driving_experience`, `Road_surface_conditions`

---

## 💡 Key Insights

- 🌧️ Rainy and wet road conditions correlate with higher accident severity
- 🛣️ Earth and gravel roads show more severe accidents than asphalt
- 👨 Most accidents involve male drivers aged 18–30
- ⚖️ Class imbalance exists — slight injuries outnumber serious injuries

---

## 🗂️ Project Structure

```
road-traffic-accidents/
├── Road_Traffic_Accidents.ipynb     # Main Jupyter Notebook
└── README.md
```

---

## 🌟 Support

If you found this project helpful, please give it a **⭐ Star** — it means a lot! 🚀

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=20&duration=3000&color=E24B4A&center=true&vCenter=true&width=600&lines=Star+the+repo+if+this+helped+you!;Contributions+and+feedback+welcome!" alt="Typing SVG">
</p>

---

## 👩‍💻 Author

**Hadia Imran**
