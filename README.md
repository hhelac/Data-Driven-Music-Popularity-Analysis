# SoundInsight: Spotify & YouTube Data Analysis ♫📊

A comprehensive data-driven statistical analysis exploring the relationship between audio features (such as danceability, energy, and valence) and track popularity metrics across two major digital platforms: **Spotify** and **YouTube**. 

This project was developed utilizing a rich Kaggle dataset to uncover underlying pattern variations in modern digital music consumption.

## 🚀 Project Overview

The core objective of this study is to apply robust statistical methods to analyze how specific audio characteristics influence a song's cross-platform success and listener engagement.

### Key Milestones:
- **Exploratory Data Analysis (EDA):** Deep dive into continuous and discrete variables, mapping out the characteristics of music datasets.
- **Statistical Modeling & Distributions:** Analysis of highly skewed data (like `Stream` and `Views`) using log-transformations to correctly evaluate long-tail distributions.
- **Hypothesis Testing:** Implementing goodness-of-fit ($\chi^2$), normality tests (Shapiro-Wilk, Kolmogorov-Smirnov), and visual validation via QQ-plots to rigorously test statistical assumptions.
- **Inferential Statistics:** Calculating confidence intervals for means and proportions, alongside $\chi^2$ tests of independence for categorical variables.

---

## 📉 Predictive Modeling: Linear Regression Analysis

The highlight of this project is the development of a **Multiple Linear Regression Model** aimed at predicting a song's total streaming numbers (`Stream`) based on its structural and technical audio characteristics.

### Model Architecture:
* **Dependent Variable (Target):** `Stream` (Spotify Streams)
* **Independent Variables (Features):** Technical audio features including *Danceability*, *Energy*, *Valence* (musical happiness), *Acousticness*, *Instrumentalness*, *Liveness*, and *Speechiness*.

### Statistical Interpretation & Takeaways:
* **The $R^2$ Paradox ($R^2 \approx 0.01$):** While a low Coefficient of Determination ($R^2$) indicates that standalone technical audio features possess limited overall predictive power (meaning music popularity is heavily driven by external factors like marketing, social media trends, and artist loyalty), the model's coefficients revealed highly significant structural trends.
* **Feature Impact:** * **Positive Impact:** Tracks with higher *Danceability* and *Energy* demonstrated a statistically significant positive correlation with streaming numbers, proving that rhythmic and upbeat elements are core drivers for viral hits.
  * **Negative/Surprising Impact:** Higher *Valence* (happier tone) showed a slight negative correlation, suggesting that modern streaming audiences often lean towards tracks with more complex, moodier, or melancholic emotional undertones.

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python 3
- **Environment:** Google Colab / Jupyter Notebook
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Statistical Computing:** `scipy.stats`, `statsmodels` / `sklearn`

## 👥 Collaboration & Acknowledgments

Academic project developed as part of the Computer Science and Informatics curriculum at the **Faculty of Electrical Engineering (ETF Sarajevo)**. 

*Note: This project was built in collaboration with fellow university colleagues as a team effort.*
