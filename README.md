
# 💤 Impact of Social Media on Sleep Quality 🧠📱

This data analysis project explores the correlation between social media usage patterns and sleep quality. By examining behavioral variables like screen time, content type, notification habits, and biological indicators, we uncover how excessive or poorly timed social media use impacts restfulness and health.

---

## 📌 Project Objectives
- Analyze user behavior: pre-sleep social media usage, frequency, platform preferences.
- Evaluate sleep metrics: latency, total sleep time, sleep quality ratings.
- Perform statistical tests (correlation, t-test, ANOVA) to identify significant relationships.
- Build machine learning regression models to predict sleep quality based on behavioral and physiological factors.

---

## 📁 Dataset Overview
- **Total Records**: 500 individuals
- **Key Features**:
  - `Age`, `Gender`, `Chronotype`
  - `Average Daily Social Media Use`, `Pre-Sleep Usage`
  - `Sleep Quality Rating`, `Melatonin & Cortisol Levels`
  - `Blue Light Exposure`, `Stress Level`, etc.

---

## 🔍 Key Insights
- 📉 **Significant negative correlation** between pre-sleep social media usage and sleep quality (r = -0.69).
- 🔴 Users with more than 60 minutes of pre-sleep usage show **statistically lower sleep quality** (t-test & ANOVA).
- 🌙 Sleep latency and WASO (Wake After Sleep Onset) increase with increased notification habits.
- 📊 Linear regression outperformed Random Forest for predicting sleep quality (R² = 0.69).

---

## 📊 Technologies & Tools Used
- Python: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`
- Jupyter Notebook
- Statistical Methods: Pearson Correlation, T-test, ANOVA
- ML Models: Linear Regression, Random Forest Regressor

---

## 📌 Folder Structure
```
📂 social-media-sleep-quality/
├── data/
│   └── SocialMediaUsage_SleepLatencyAnalysis_Singapore.csv
├── notebooks/
│   └── sleep_socialmedia_analysis.ipynb
├── images/
│   └── plots, heatmaps, and boxplots
├── cleaned_data.csv
└── README.md
```

---

## 📈 Model Summary
| Model              | R² Score | RMSE |
|-------------------|----------|------|
| Linear Regression | 0.694    | 0.610 |
| Random Forest     | 0.643    | 0.658 |

✅ Linear Regression was more accurate and interpretable for this regression problem.

---

## 📖 Conclusion
- Increased social media usage before sleep negatively affects sleep quality.
- Nighttime behaviors such as notification checking significantly disrupt rest.
- Awareness and digital hygiene can greatly improve sleep patterns.

---

## 📌 Reference
- 📄 [Medical Student Sleep Study](https://www.worldwidejournals.com/paripex/fileview.php?val=December_2022_1671099141__84.pdf)
- 📊 Custom dataset analyzed from Singapore sleep study survey.

---

## 🔧 Future Work
- Add deep learning models (e.g., neural nets) for non-linear prediction.
- Explore sentiment analysis of consumed content.
- Deploy a Streamlit dashboard for public awareness & feedback.

---

