# 📊 Exploratory Data Analysis Portfolio

A collection of 5 exploratory data analysis projects built using Python, pandas, matplotlib, and seaborn. Each project explores a different domain — sports, music, medicine, e-commerce, and education — with a focus on finding meaningful insights through visualization and statistical analysis.

---

## 🗂️ Projects Overview

| # | Project | Domain | Records | Charts | Target |
|---|---|---|---|---|---|
| 1 | Olympic Games | Sports | 70,000 | 15+ | Medal & participation patterns |
| 2 | Spotify Churn | Music / Business | 8,000 | 20+ | User churn behavior |
| 3 | Breast Cancer Diagnosis | Medical | 569 | 33+ | Malignant vs Benign |
| 4 | Amazon Sales | E-Commerce | 1,465 | 19 | Pricing & discount patterns |
| 5 | Student Habits | Education | 1,000 | 22 | Academic performance |

---

## 🏅 Project 1 — Olympic Games (120 Years of History)

**Dataset:** 70,000 athlete-event records | 1896–2016 | Summer & Winter Olympics

**Key Questions:**
- How has Olympic participation grown over 120 years?
- How has gender representation evolved?
- Do physical attributes (height, weight, age) differ by sport?
- What separates medal winners from non-medalists?

**Key Insights:**
- 86% of Olympic athletes never won a medal
- Female participation grew from near 0% in 1896 to ~40% by 2016
- Medal winners are on average 2.7cm taller than non-medalists
- Gymnasts peak at ~20 years while sailors compete well into their 30s

**Tools:** Python | pandas | matplotlib | seaborn | NumPy

---

## 🎵 Project 2 — Spotify User Churn Analysis

**Dataset:** 8,000 user records | Subscription, behavior, and device data

**Key Questions:**
- Which subscription type churns the most?
- Do listening habits differ between churned and active users?
- Does screen time or offline usage affect retention?

**Key Insights:**
- Family plan users churn more than Free users (27.5% vs 24.9%) — unexpected
- Offline listening users are more likely to stay active
- Near-zero correlation between all numeric features and churn — dataset is synthetically randomized
- Recognizing when data lacks predictive signal is as important as finding insights

**Tools:** Python | pandas | matplotlib | seaborn | NumPy

---

## 🔬 Project 3 — Breast Cancer Diagnosis

**Dataset:** 569 real medical records | University of Wisconsin | 30 features from FNA images

**Key Questions:**
- Which physical measurements best distinguish malignant from benign tumors?
- Do worst features outperform mean features as predictors?
- Can a visual profile of each tumor type be built from the data?

**Key Insights:**
- `concave points_worst` is the strongest predictor at 0.79 correlation
- Malignant tumors score higher on all 30 features without exception
- Fractal dimension is the only feature where benign and malignant are identical (0.0629 vs 0.0627)
- Worst features consistently outperform mean features in predictive power
- 33+ visualizations including radar chart, 3D rotating GIF, ridgeline plot, and Cohen's d analysis

**Tools:** Python | pandas | matplotlib | seaborn | scikit-learn | scipy | pillow

---

## 🛒 Project 4 — Amazon Sales Analysis

**Dataset:** 1,465 Amazon product listings | 9 categories | Prices, discounts, ratings

**Key Questions:**
- Which categories are most discounted and most expensive?
- Does discount percentage affect customer ratings?
- What pricing patterns exist across Amazon product categories?

**Key Insights:**
- Electronics is the core revenue driver — highest count (526) and highest average price (₹10,127)
- Discount percentage has near-zero correlation with rating (-0.16) — discounts don't buy better ratings
- AmazonBasics dominates the most reviewed products with 426,973 reviews
- The 41–60% discount tier is the sweet spot — 508 products fall here
- Cables and accessories are discounted up to 94% — likely used as loss leaders

**Tools:** Python | pandas | matplotlib | seaborn | NumPy

---

## 📚 Project 5 — Student Habits vs Academic Performance

**Dataset:** 1,000 student records | Daily habits mapped against exam scores

**Key Questions:**
- What habit has the strongest relationship with exam performance?
- Does attendance predict academic success?
- Do background factors like parental education affect scores?
- How does screen time impact performance?

**Key Insights:**
- Study hours dominates with a correlation of 0.83 — nothing else comes close
- Mental health is the second strongest factor at 0.32
- Attendance has a surprisingly weak correlation of just 0.09
- Excellent students spend 1.2 fewer hours on screens daily than poor performers
- Gender, parental education, internet quality, and extracurricular participation have virtually zero impact

**Tools:** Python | pandas | matplotlib | seaborn | scipy | NumPy

---

## 🛠️ Tech Stack

```
Language    : Python 3.12
Libraries   : pandas, NumPy, matplotlib, seaborn, scipy, scikit-learn, pillow
Environment : Jupyter Notebook
Version Control : Git / GitHub
```

---

## 📈 Skills Demonstrated

| Skill | Projects |
|---|---|
| Data cleaning & preprocessing | All projects |
| Univariate analysis | All projects |
| Bivariate & multivariate analysis | All projects |
| Correlation analysis | All projects |
| Feature engineering | Projects 2, 4, 5 |
| Statistical analysis (Cohen's d, KDE, CDF) | Project 3 |
| Medical data interpretation | Project 3 |
| Business insight generation | Projects 2, 4 |
| Time series visualization | Project 1 |
| 3D visualization & animation | Project 3 |

---

## 🚀 How to Run Any Project

1. Clone the repository
2. Navigate to the project folder
3. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn pillow jupyter
```
4. Open the notebook
```bash
jupyter notebook <project_name>.ipynb
```

---

## 👤 Author

**NIO**
Transitioning from Instructional Design & Project Management (CAPM certified) into Data Analytics. Building a portfolio one project at a time.

- 📁 3 Data Cleaning Projects completed
- 📊 5 EDA Projects completed
- 🚀 Next: SQL projects and Machine Learning

---

## 📂 Data Sources

| Project | Source |
|---|---|
| Olympic Games | [Kaggle — Bhanu Pratap Biswas](https://www.kaggle.com/datasets/bhanupratapbiswas/olympic-data) |
| Spotify Churn | [Kaggle — Nabiha Zahid](https://www.kaggle.com/datasets/nabihazahid/spotify-dataset-for-churn-analysis/data) |
| Breast Cancer | [Kaggle — Wasiq Ali Yasir](https://www.kaggle.com/datasets/wasiqaliyasir/breast-cancer-dataset/data) |
| Amazon Sales | [Kaggle — Mehak Iftikhar](https://www.kaggle.com/code/mehakiftikhar/amazon-sales-dataset-eda) |
| Student Habits | [Kaggle — Jayaanta Naath](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance) |
