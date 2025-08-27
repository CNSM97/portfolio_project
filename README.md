# Determinants of Happiness: An Exploratory Data Analysis of the World Happiness Report (2005–2024)

> This project analyzes World Happiness Report data (2005–2024) to explore the main social, economic, and health factors that influence happiness worldwide, using exploratory data analysis and regression modeling.

## 📊 Project Overview

**Problem Statement:** 

Happiness is increasingly recognized as a key indicator of societal progress, yet the factors that drive it remain complex and vary across countries and over time. Without a clear understanding of these determinants, it is difficult to explain differences in well-being levels or identify long-term global trends. 

This project addresses this gap by analyzing the most recent World Happiness Report data (2024) to evaluate the relative importance of social, economic, and health-related drivers, while also exploring how happiness scores have evolved worldwide from 2005 to 2024.

**Objective:** 

The project aims to conduct a detailed analysis of the year 2024 to evaluate the key determinants of happiness and their relative importance. In addition, historical data from 2005–2024 will be used for time series analysis to observe trends in the development of the Happiness Score across countries and regions.

**Methods:** 

- **Exploratory data analysis (EDA)** for investigating distributions, correlations, and cross-country differences
- **Visualizations** (e.g. time series plots, heat maps, regression plots) for representing relationships and trends across years and regions
- **Regression modeling** (linear regression with VIF checks) for evaluating the relative importance of happiness determinants in 2024
- **Comparative analysis** (2024 vs. 2005–2024) for identifying key drivers and long-term developments in happiness scores

## 🎯 Key Findings

<!-- Hier deine wichtigsten Erkenntnisse in 3-5 Bullet Points -->
- 📈 **Erkenntnis 1:** Kurze Beschreibung
- 🔍 **Erkenntnis 2:** Kurze Beschreibung  
- 💡 **Erkenntnis 3:** Kurze Beschreibung

## 📁 Repository Structure

```
├── data/
│   ├── raw/                    # Originaldaten
│   └── processed/              # Bereinigte Daten
├── notebooks/                  # Jupyter Notebooks
│   └── 01_exploration.ipynb    # Datenexploration
├── src/dpp                     # Python Module
├── test/                       # Unit Tests
├── pyproject.toml              # Projektkonfiguration
└── docs/                       # Zusätzliche Dokumentation
```

## 🔧 Technologies Used

**Programming Languages:**

- Python (3.12)

**Libraries & Frameworks:**

- pandas, numpy (data processing)
- matplotlib, seaborn (visualization)
- scikit-learn (modeling, regression analysis)

**Tools:**
<!-- z.B. Jupyter, Git, Docker, etc. -->
- Jupyter Notebooks (exploration & reporting)
- Git/GitHub (version control & portfolio hosting)
- UV Packetmanager (dependency management)

## 📊 Data

**Source:** 
<!-- Woher kommen deine Daten? -->
- World Happiness Report (2005–2024), available at: https://worldhappiness.report/ed/2024/
- Kaggle dataset “World Happiness Report- 2024”, available at: https://www.kaggle.com/datasets/jainaru/world-happiness-report-2024-yearly-updated/data

**Dataset Size:** 
<!-- Anzahl Zeilen/Spalten, Dateigröße -->
- Historical dataset (2005–2023): 2363 rows × 11 columns
- 2024 dataset: 143 rows × 12 columns

**Key Features:** 
<!-- Beschreibung der wichtigsten Variablen -->
- **Ladder score** (dependent variable, national happiness level based on the Cantril ladder (0–10))
- **Log GDP per capita** (economic prosperity adjusted for purchasing power)
- **Social support** (availability of friends or relatives in times of need)
- **Healthy life expectancy** (expected years of healthy living)
- **Freedom to make life choices** (perceived autonomy in everyday decisions)
- **Perceptions of corruption** (public trust in government and institutions)
- **Generosity** (propensity to donate (income-adjusted residual))


## 🤖 Methodology

### Data Preprocessing
<!-- Kurze Beschreibung deiner Datenbereinigung -->
- Handling missing values and inconsistent formats
- Harmonizing differences between 2024 and historical datasets (notably “Healthy life expectancy”)
- Standardizing feature scales for regression analysis

### Modeling Approach  
<!-- Welche Modelle hast du getestet? -->
- Linear regression to estimate the contribution of each factor
- Variance Inflation Factor (VIF) to check multicollinearity
- Comparative analysis of 2024 vs. historical trends

### Evaluation
<!-- Wie hast du die Ergebnisse bewertet? -->
- Coefficient interpretation
- Goodness-of-fit metrics (R², adjusted R²)
- Cross-country comparison of predictions vs. actual scores

## 📈 Results

**Model Performance:**
<!-- Deine besten Metriken (Accuracy, RMSE, etc.) -->

**Key Visualizations:**
<!-- Verweis auf Key-Plots in deinen Notebooks -->

## 🚀 Reproducibility

### Setup
```bash
# Repository klonen
git clone [DEIN-REPO-LINK]
cd [REPO-NAME]

# Dependencies installieren
uv sync
```

### Execution Order
```bash
# Notebooks in dieser Reihenfolge ausführen:
# 1. notebooks/01_exploration.ipynb
# 2. notebooks/02_preprocessing.ipynb  
# 3. notebooks/03_modeling.ipynb
# 4. notebooks/04_results.ipynb
```


## 🎓 About this Project

**Context:** 
This project was developed as part of a personal data analytics portfolio to showcase exploratory data analysis, regression modeling, and documentation skills.

**Timeline:** 
August 2025 (3 weeks)

**Author:** 
Charlotte Sánchez Marlótica

## 📞 Contact

**GitHub:** [@DeinUsername](https://github.com/DeinUsername)  
**Email:** deine.email@beispiel.de  
**LinkedIn:** [Dein Profil](https://linkedin.com/in/dein-profil)

## 🙏 Danksagungen

<!-- Hier kannst du Personen oder Ressourcen erwähnen, die dir geholfen haben -->

---

**⭐ Wenn dir dieses Projekt gefällt, gib gerne einen Star!**
