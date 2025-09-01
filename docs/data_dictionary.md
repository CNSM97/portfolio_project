# Data Dictionary – World Happiness Report (2005–2024)

This data dictionary documents the variables of both datasets:  
- **2005–2023**: Long-term data from World Happiness Report data  
- **2024**: Most recent cross-sectional dataset, with additional whisker & dystopia values  

---

## Variables Overview

| Variable                  | Description                                                                                          | Source / Notes                                                                 |
|----------------------------|------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| `Country name`             | Name of the country                                                                                 | World Happiness Report                                                         |
| `Regional indicator`       | Region the country belongs to                                                                       | Only explicitly included in the 2024 dataset                                   |
| `Ladder score`             | Happiness score (0–10), based on the Cantril Ladder question                                        | Gallup World Poll                                                              |
| `Upper whisker`            | Upper bound of the confidence interval for the ladder score                                         | World Happiness Report (2024 dataset)                                          |
| `Lower whisker`            | Lower bound of the confidence interval for the ladder score                                         | World Happiness Report (2024 dataset)                                          |
| `Log GDP per capita`       | Natural logarithm of GDP per capita (PPP, constant 2017 intl $), extrapolated where necessary       | World Bank WDI, OECD/World Bank forecasts (for 2023)                           |
| `Social support`           | Share of respondents with friends/relatives they can rely on in times of need (binary 0/1 responses)| Gallup World Poll                                                              |
| `Healthy life expectancy`  | Expected years lived in good health, interpolated/extrapolated for missing years                    | WHO Global Health Observatory                                                  |
| `Freedom to make choices`  | Satisfaction with freedom to choose what to do with one’s life                                      | Gallup World Poll                                                              |
| `Generosity`               | Residual from regressing donations on log GDP per capita                                           | Gallup World Poll                                                              |
| `Perceptions of corruption`| Average perception of corruption in government and businesses                                      | Gallup World Poll                                                              |
| `Positive affect`          | Average of: laughter, enjoyment, and doing interesting things (since WHR 2022)                     | Gallup World Poll                                                              |
| `Negative affect`          | Average of: worry, sadness, and anger                                                               | Gallup World Poll                                                              |
| `Dystopia + residual`      | Benchmark ensuring no country scores below hypothetical “Dystopia”                                 | World Happiness Report (2024 dataset)                                          |

---

## Notes on Data Sources

- **Gallup World Poll (GWP):** Underpins many variables (social support, freedom, generosity, corruption, affect).  
- **World Bank WDI / OECD forecasts:** Basis for GDP data (`Log GDP per capita`).  
- **WHO Global Health Observatory:** Basis for life expectancy.  
- **World Happiness Report methodology:** Defines residuals, whiskers, and dystopia values.  

---

## Differences Between Datasets

- **2005–2023:**  
  - Does not include `Upper whisker` / `Lower whisker`  
  - Does not explicitly include `Regional indicator`  
  - Focused on longitudinal core variables  

- **2024:**  
  - Includes `Upper whisker`, `Lower whisker`, and `Dystopia + residual`  
  - Explicit `Regional indicator` column  
  - Same core variables as earlier years  

---
