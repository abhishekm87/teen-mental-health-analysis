# Teen Mental Health Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge)

**Exploratory Data Analysis on Teen Mental Health & Social Media Usage**

## 📋 Project Overview

This project analyzes the relationship between social media usage, lifestyle factors, and mental health among **1200 teenagers** (ages 13–19). The main goal is to identify key risk and protective factors associated with depression in teens.

### Key Highlights:
- Highly imbalanced dataset (only **2.6%** depression cases)
- Strong correlations found between **sleep**, **social media usage**, **stress**, and **depression**
- Comprehensive visualizations and statistical insights

---

## 📊 Dataset

**File:** `Teen_Mental_Health_Dataset.csv`

### Features:
- **Demographics**: `age`, `gender`
- **Social Media**: `daily_social_media_hours`, `platform_usage` (Instagram, TikTok, Both), `screen_time_before_sleep`
- **Lifestyle**: `sleep_hours`, `physical_activity`, `social_interaction_level`
- **Mental Health**: `stress_level`, `anxiety_level`, `addiction_level`, `academic_performance`
- **Target**: `depression_label` (0 = No, 1 = Yes)

---

## 🔍 Key Insights

- Teens with depression spend **more time on social media** on average.
- **Lower sleep hours** is one of the strongest indicators of depression.
- Higher levels of **stress**, **anxiety**, and **social media addiction** are significantly associated with depression.
- **Physical activity** and **academic performance** tend to be lower in the depressed group.
- No strong dominance of any single platform (Instagram vs TikTok).

---

## 📈 Visualizations Included

- Correlation Heatmap
- Box plots comparing features by depression label
- Count plots (Gender vs Depression)
- Bar plots for averages

---

## 🛠️ Technologies Used

- **Python** 3.9+
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** (optional)

---

## 🚀 How to Run

1. Install dependencies:
   ```pip
   pip install pandas numpy matplotlib seaborn
   ```

3. Run the analysis:
   ```pip
   python analysis.py
   ```
   or open `Teen_Mental_Health_Analysis.ipynb`

---

## 📁 Project Structure

```
teen-mental-health-analysis/
├── Teen_Mental_Health_Dataset.csv
├── analysis.py
├── Teen_Mental_Health_Analysis.ipynb
├── visualizations/
│   ├── correlation_heatmap.png
│   ├── depression_by_gender.png
│   └── ...
├── README.md
└── requirements.txt
```

---

## ⚠️ Limitations

- Highly imbalanced dataset (only 31 depression cases)
- No causal relationships can be definitively proven
- Data is limited to ages 13–19

---

## 🔮 Future Work

- Build predictive models (Logistic Regression, Random Forest, XGBoost)
- Apply oversampling techniques (SMOTE) for better prediction
- Create an interactive dashboard (Streamlit / Power BI)
- Add statistical significance testing

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Abhishek**  
Data Analyst | Passionate about Mental Health & Data Science

---

**⭐ Star this repository if you found it helpful!**

Would you like a shorter version or a more technical/academic version of this README?
