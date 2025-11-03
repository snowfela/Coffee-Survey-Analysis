# ☕ Coffee Survey Analysis

## Overview
This project analyzes **coffee consumption preferences and patterns** among survey participants, aiming to uncover insights into caffeine habits, satisfaction levels, and lifestyle correlations.  
Using Python’s data analysis libraries, it explores how different demographics engage with coffee, revealing trends in taste, frequency, and attitude toward caffeine intake.

---

## Objectives
- Load and clean survey data for analysis.  
- Investigate **coffee consumption frequency**, **favorite types**, and **age-based patterns**.  
- Visualize data to identify behavioral trends.  
- Summarize key insights about caffeine habits and satisfaction levels.

---

## Dataset
**File:** `coffee-survey.csv`  

Contains responses from participants on their coffee habits, preferences, and demographic information.  
The dataset includes fields such as:

| Column Name | Description |
|--------------|-------------|
| `age` | Age of the respondent |
| `coffee_type` | Preferred coffee type (Espresso, Latte, Cappuccino, etc.) |
| `cups_per_day` | Average number of cups consumed daily |
| `brew_method` | Preferred brewing method |
| `purchase_place` | Where they usually buy or consume coffee |
| `satisfaction_level` | Rated satisfaction with their coffee experience |

---

## Key Steps and Analysis

### 1. Loading the Dataset
- Imported data using **pandas**.
- Displayed the first few rows to understand the structure and missing values.
- Verified dataset dimensions and column consistency.

### 2. Data Cleaning and Preparation
- Checked for missing entries using `isnull().sum()`.
- Handled null values appropriately.
- Normalized categorical columns for uniformity (e.g., “Espresso” vs. “espresso”).

### 3. Exploratory Data Analysis (EDA)
- Calculated the average cups of coffee consumed per day.
- Grouped respondents by **age group** and **coffee preference**.
- Visualized patterns such as:
  - Popular coffee types among young vs. older adults.
  - Average consumption by gender or occupation (if included).
  - Correlation between coffee type and satisfaction level.

### 4. Visualization
- Created **bar charts** and **histograms** using `matplotlib` and `seaborn`.  
- Plotted trends such as:
  - Most preferred coffee type.
  - Frequency of consumption.
  - Distribution of satisfaction scores.

### 5. Key Insights
- Found that **Latte** and **Cappuccino** were the most popular choices overall.  
- Younger participants preferred **iced or flavored coffees**, while older respondents favored **espresso**.  
- Most respondents consumed **2–3 cups per day**, showing moderate caffeine intake.  
- Higher satisfaction correlated with **home-brewed coffee** and **specific brewing methods** (like French press).

---

## Tools & Libraries
- **Python**  
- **Pandas** for data manipulation  
- **Matplotlib** and **Seaborn** for visualization  
- **Google Colab** for execution and analysis  


---

## Author
Developed as a **data exploration and visualization project** to understand consumer behavior and caffeine habits through survey-based analytics.
