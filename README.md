# 🌾 Crop Production Prediction in India
### Machine Learning Internship Project | UpSkill Campus & UCT

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![ML](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Internship](https://img.shields.io/badge/Internship-UpSkill%20Campus-purple)

---

## 📌 About This Project

This project was built as part of the **Free Summer Internship in Data Science & Machine Learning** by **UpSkill Campus & UCT (Universal Career Transformer)**.

The goal is to predict **crop production (in tons)** across different Indian states using historical agricultural data from 2001 to 2014.

---

## 🏢 About UCT
UCT (Universal Career Transformer) is an ed-tech company that upskills students with industry-relevant knowledge through internships and real-world projects in Data Science, Machine Learning, and Artificial Intelligence.

---

## 🔍 Problem Statement

India has over 1.3 billion people and agriculture is the backbone of its economy. Accurate prediction of crop production helps:
- 🌾 Farmers plan better
- 🏛️ Government manage food supply
- 📊 Agricultural agencies allocate resources

**Given:** State, District, Season, Crop type, Area cultivated, and Year  
**Predict:** Total crop production (in tons)

---

## 📊 Dataset

| Detail | Info |
|---|---|
| **Source** | [Kaggle – Crop Production in India](https://www.kaggle.com/datasets/abhinand05/crop-production-in-india) |
| **Records** | ~246,000 rows |
| **Time Period** | 2001 – 2014 |
| **States Covered** | 33 Indian States |
| **Crops Covered** | 124 different crops |

**Columns:**
- `State_Name` – State of cultivation
- `District_Name` – District of cultivation
- `Crop_Year` – Year of cultivation
- `Season` – Kharif / Rabi / Whole Year / etc.
- `Crop` – Crop name (Rice, Wheat, etc.)
- `Area` – Area cultivated (hectares)
- `Production` – **Target** – Production in tons

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data loading & manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Machine Learning models |
| Google Colab | Cloud notebook environment |

---

## 🚀 ML Models Used

| Model | MAE | R² Score |
|---|---|---|
| Linear Regression | Higher | Lower |
| **Random Forest** ✅ | **Lower** | **Higher** |

✅ **Random Forest Regressor** performed best with significantly higher R² Score.

---

## 📈 Key Visualizations

### Top 10 Crops by Production
![Top Crops](images/chart1_top_crops.png)

### Top 10 States by Production
![Top States](images/chart2_top_states.png)

### Production by Season
![Season](images/chart3_season.png)

### Year-wise Production Trend
![Trend](images/chart4_year_trend.png)

### Actual vs Predicted (Random Forest)
![Predicted](images/chart5_actual_vs_predicted.png)

### Feature Importance
![Features](images/chart6_feature_importance.png)

---

## 🔑 Key Findings

- **Area cultivated** is the most important predictor of crop production
- **Sugarcane** and **Rice** are top crops by total production volume
- **Uttar Pradesh** and **Andhra Pradesh** lead in crop production
- **Whole Year** season contributes maximum production
- Random Forest outperforms Linear Regression significantly

---

## 📁 Repository Structure

```
📦 crop-production-prediction/
├── 📓 Project4_Crop_Production_SAFE.ipynb   ← Main notebook
├── 📁 images/
│   ├── chart1_top_crops.png
│   ├── chart2_top_states.png
│   ├── chart3_season.png
│   ├── chart4_year_trend.png
│   ├── chart5_actual_vs_predicted.png
│   └── chart6_feature_importance.png
└── 📄 README.md
```

---

## ▶️ How to Run

1. Open `Project4_Crop_Production_SAFE.ipynb` in **Google Colab**
2. Run all cells from top to bottom (Shift + Enter)
3. Dataset loads automatically — no API key needed
4. Charts are auto-saved and can be downloaded

---

## 🧠 What I Learned

- How to load and explore real-world agricultural datasets
- Data cleaning: handling missing values and outliers
- Label Encoding for converting categorical text to numbers
- Training and comparing ML models (Linear Regression vs Random Forest)
- Model evaluation using MAE, RMSE, and R² Score
- Feature Importance analysis to identify key predictors
- Creating meaningful visualizations for data storytelling

---

## 🔮 Future Improvements

- Add rainfall and temperature data for better accuracy
- Try XGBoost / Gradient Boosting models
- Build a Streamlit web app for farmer-friendly predictions
- Include crop price prediction alongside production

---

## 👤 Author

**Suryakant Prajapati**  
Data Science & ML Intern — UpSkill Campus  
🔗 [LinkedIn](https://linkedin.com) | 💻 [GitHub](https://github.com)

---

## 📜 License
This project is part of an internship program by UpSkill Campus & UCT.  
Dataset credit: [Kaggle – Abhinand](https://www.kaggle.com/datasets/abhinand05/crop-production-in-india)
