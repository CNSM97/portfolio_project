# Data Dictionary – World Happiness Report (2005–2024)

This data dictionary documents the variables of both datasets:  
- **2005–2023**: Long-term data from World Happiness Report data  
- **2024**: Most recent cross-sectional dataset, with additional whisker & dystopia values  

---

## Variables Overview

| Variable                  | Description                                                                                          | Notes                                                                |
|----------------------------|------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| `Country name`             | Name of the country                                                                                 |  Report                                                         |
| `Regional indicator`       | Region the country belongs to                                                                       | Only explicitly included in the 2024 dataset                                   |
| `Ladder score`             | Happiness score (0–10), based on the Cantril Ladder question                                        |                                                                |
| `Upper whisker`            | Upper bound of the confidence interval for the ladder score                                         | Only explicitly included in the 2024 dataset                                          |
| `Lower whisker`            | Lower bound of the confidence interval for the ladder score                                         | Only explicitly included in the 2024 dataset                                          |
| `Log GDP per capita`       | Natural logarithm of GDP per capita (PPP, constant 2017 intl $), extrapolated where necessary       |                            |
| `Social support`           | Share of respondents with friends/relatives they can rely on in times of need (binary 0/1 responses)|                                                          |
| `Healthy life expectancy`  | Expected years lived in good health, interpolated/extrapolated for missing years                    |                                               |
| `Freedom to make choices`  | Satisfaction with freedom to choose what to do with one’s life                                      |                                                               |
| `Generosity`               | Residual from regressing donations on log GDP per capita                                           |                                                               |
| `Perceptions of corruption`| Average perception of corruption in government and businesses                                      |                                                               |
| `Positive affect`          | Average of: laughter, enjoyment, and doing interesting things (since WHR 2022)                     | Only explicitly included in the 2005-2023 dataset                                                              |
| `Negative affect`          | Average of: worry, sadness, and anger                                                               | Only explicitly included in the 2005-2023 dataset                                                              |
| `Dystopia + residual`      | Benchmark ensuring no country scores below hypothetical “Dystopia”                                 | Only explicitly included in the 2024 dataset                                          |

---


## Differences Between Datasets

- **2005–2023:**  
  - Does not include `Upper whisker` / `Lower whisker`  
  - Does not explicitly include `Regional indicator`  
  - Focused on long-term core variables  

- **2024:**  
  - Includes `Upper whisker`, `Lower whisker`, and `Dystopia + residual`  
  - Explicit `Regional indicator` column  
  - Same core variables as earlier years  

---
