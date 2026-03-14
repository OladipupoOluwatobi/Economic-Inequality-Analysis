# Economic Inequality in English Households
**Module:** MSc Data Science | University of Wolverhampton  
**Tools:** R, Quarto, ggplot2, tidyverse, knitr  
**Dataset:** England Household Census 2021 (27,410 individuals)

---

## 📋 Overview
This project investigates the structure of economic inequality in English 
households using 2021 Census data. The analysis explores how gender, 
education, and housing quality intersect to shape income outcomes across 
27,410 individuals.

Built as a fully reproducible **Quarto report** with dynamic visualisations 
using ggplot2 and inline R statistics.

---

## 🔍 Key Findings

### 1. 📈 Income Distribution
The income distribution is right-skewed, with most individuals earning 
below the average. A small number of high earners significantly pull the 
mean upward.

### 2. ⚧ Gender Income Gap
An unexpected finding: **females in this sample earn more than non-females** 
across all education levels - a reversal of national trends. This highlights 
the importance of contextual analysis when interpreting income data.

### 3. 🎓 Education Impact on Income
A strong positive relationship exists between educational attainment and 
income. Higher qualifications consistently correspond to higher earnings, 
reinforcing education as a key driver of economic mobility.

### 4. 🏠 Housing Quality and Economic Status
Individuals in shared-facility accommodation earn significantly less than 
those with private amenities, demonstrating that housing conditions both 
reflect and reinforce economic inequality.

---

## 📊 Visualisations

| Chart | Description |
|-------|-------------|
| ![Income Distribution](Income%20Distribution%20Overview.png) | Right-skewed annual income distribution |
| ![Gender Income Gap](Gender%20Income%20Gap.png) | Boxplot comparison of income by gender |
| ![Education Impact](Education%20Impact%20on%20Income.png) | Income distribution across education levels |
| ![Gender Pay Gap](Gender%20Pay%20Gap%20Across%20Education.png) | Gender pay gap across all education levels |
| ![Housing Quality](Housing%20Quality%20and%20Economic%20Status.png) | Violin plot of income by housing quality |

---

## 🛠️ Libraries Used
```r
tidyverse | ggplot2 | ggthemes | knitr
```

## ▶️ How to Reproduce
1. Clone this repository
2. Place your `data.csv` file in a `data/` folder
3. Open `economic_inequality_analysis.qmd` in RStudio
4. Click **Render** to generate the full HTML report

> **Note:** Update the data file path in the .qmd file to match 
> your local directory before rendering.

---

## 📁 Files
| File | Description |
|------|-------------|
| `economic_inequality_analysis.qmd` | Quarto source file with all R code |
| `economic_inequality_analysis.html` | Rendered HTML report |
| `references.bib` | Bibliography references |
| `*.png` | Exported visualisation charts |
