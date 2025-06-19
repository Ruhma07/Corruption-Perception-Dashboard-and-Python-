# Corruption Perception Dashboard

> A data-driven analysis of global corruption trends using indicators, governance metrics, socio-economic factors, and development indices across 3,000 rows and 33 columns.

---

## 📌 Project Overview

This project provides an in-depth exploration of global corruption perception trends over two decades (2000–2023), using data that spans multiple sectors, countries, and development indicators. The dataset consists of **3,000 rows** and **33 columns**, covering:

- Corruption Perceptions Index (CPI) scores
- Sector-wise corruption metrics
- Political and freedom indicators
- Socio-economic and development indicators
- Governance and institutional quality metrics

The goal is to understand how corruption correlates with governance, economic conditions, human development, and political freedoms across different regions and time periods.

---

## 🗂️ Dataset Structure

| Rows | Columns | Description |
|------|---------|-------------|
| 3,000 | 33 | Contains corruption indicators, governance metrics, socio-economic indicators, and development indices for multiple countries over time |

### Sample CPI Score Distribution Over Time

| Year | CPI Score |
|------|-----------|
| 2000 | 51.96     |
| 2001 | 52.88     |
| 2002 | 53.71     |
| 2003 | 55.45     |
| 2004 | 54.70     |
| 2005 | 55.86     |
| 2006 | 50.59     |
| 2007 | 57.55     |
| 2008 | 53.74     |
| 2009 | 53.44     |
| 2010 | 56.61     |
| ...  | ...       |
| 2023 | 53.72     |

---

## 🔍 Key Insights

### Global CPI Trends
- CPI scores show fluctuating trends between 2000 and 2023.
- Peaks occurred around **2011** and **2020**.
- Significant declines observed in **2006** and **2016**.

### Top 10 Least Corrupt Countries (Latest Year)
- Benchmark nations with the highest CPI scores.
- Reflect strong governance and anti-corruption frameworks.

### Bottom 10 Most Corrupt Countries (Latest Year)
- Highlight areas with institutional challenges and poor governance practices.

### Regional Disparities
- Certain regions consistently perform better in terms of perceived integrity.
- Average CPI scores by region reveal persistent inequality in corruption levels.

---

## 📊 Sector-Wise Corruption Analysis

| Sector | Normalized Contribution (%) |
|--------|-----------------------------|
| Legislative Corruption       | 20.28% |
| Public Sector Corruption     | 20.03% |
| Judicial Corruption          | 19.96% |
| Executive Branch Corruption  | 19.91% |
| Police Corruption            | 19.82% |

### Top 5 Countries by Sector Corruption

#### Public Sector Corruption

| Country | Score |
|--------|-------|
| Russia | 8.68  |
| Japan  | 8.30  |
| Germany| 7.61  |
| UK     | 6.13  |
| USA    | 5.72  |

#### Judicial Corruption

| Country | Score |
|--------|-------|
| Germany| 9.77  |
| France | 9.50  |
| UK     | 7.04  |
| Japan  | 6.71  |
| China  | 6.54  |

*(Similar tables exist for Police, Executive, and Legislative corruption)*

---

## 🧠 Political & Freedom Indicators

### Democracy Index (Top 5)

| Country | Index |
|--------|-------|
| China  | 7.41  |
| USA    | 5.33  |
| Russia | 4.16  |
| Germany| 4.10  |
| India  | 3.88  |

### Civil Liberties (Top 5)

| Country       | Index |
|---------------|-------|
| Japan         | 9.66  |
| South Africa  | 8.07  |
| Russia        | 8.06  |
| UK            | 7.95  |
| USA           | 5.36  |

---

## 💰 Socio-Economic Indicators

### GDP per Capita (Top 5)

| Country       | GDP per Capita |
|---------------|----------------|
| South Africa  | $64,838        |
| UK            | $58,491        |
| India         | $35,448        |
| Russia        | $31,281        |
| Japan         | $19,209        |

### Unemployment Rate (Lowest)

| Country | Rate (%) |
|---------|----------|
| India   | 1.08     |
| USA     | 2.34     |
| Germany | 4.06     |
| Russia  | 4.53     |
| Brazil  | 5.02     |

---

## 🏛️ Governance & Institutional Quality

### Government Effectiveness (Top 5)

| Country | Score |
|--------|-------|
| China  | 7.86  |
| France | 6.90  |
| UK     | 5.44  |
| Japan  | 2.69  |
| USA    | 1.41  |

### Human Rights Index (Top 5)

| Country       | Index |
|---------------|-------|
| France        | 7.46  |
| UK            | 7.18  |
| Japan         | 5.93  |
| South Africa  | 4.29  |
| Germany       | 3.92  |

---

## 📈 Development Indicators

- **HDI vs CPI Correlation**: `0.488`
- **Internet Penetration vs CPI Correlation**: `0.455`

### Top 5 HDI Scores

| Country | HDI   |
|---------|-------|
| Japan   | 0.782 |
| Brazil  | 0.633 |
| India   | 0.569 |
| France  | 0.496 |
| Russia  | 0.466 |

---

## 📉 Outlier Detection

### Anomaly Countries (High GDP, Low CPI)

| Country | GDP per Capita | CPI Score |
|---------|----------------|-----------|
| India   | $35,448        | 34        |
| UK      | $58,491        | 10        |

---

## 📈 Top 3 Improving & Declining Countries

### Top 3 Improving (Positive CPI Changes)

- **Drivers**: Judiciary and education reform
- **Correlations**:
  - Judicial Corruption: `+0.828`
  - Education Corruption: `+0.454`
  - Legislative Corruption: `-0.999`

### Top 3 Declining (Negative CPI Changes)

- **Drivers**: Rise in public sector, police, and political party corruption
- **Correlations**:
  - Public Sector Corruption: `-0.997`
  - Police Corruption: `-0.958`
  - Political Party Corruption: `-0.901`

---

## 🧩 Advanced Insights

### CPI vs Democracy Index & HDI

Scatterplots show relationships between CPI, HDI, democracy index, and GDP per capita. For example, India has a high GDP per capita ($35k) but a relatively low CPI score (34), suggesting governance inefficiencies.

---

