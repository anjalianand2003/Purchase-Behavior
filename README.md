# Purchase-Behavior
# 🛍️ Ecommerce Purchase Behavior Analysis

This project investigates the relationship between **user profiles**, **gender**, **page views**, and **purchase behavior** using real-world e-commerce user data.

## 📦 Dataset

- **Filename:** `ecommerce-data.csv`
- **Key columns:**
  - `profile`: User type (e.g., Parent, Teacher)
  - `gender`: Male, Female, or Unspecified
  - `behavPageviews`: Browsing intensity (categorical)
  - `behavAnySale`: Whether the user made a purchase (1/0)
  - `purchasedWhen`: Timing of last purchase

---

## 🎯 Objectives

- Analyze how **pageviews vary by profile**
- Study **gender distribution** across user profiles
- Visualize **purchase recency patterns**
- Calculate **conversion rates** (purchase rates) by profile and gender

---

## 🔍 Questions Answered

| Question | Description |
|----------|-------------|
| Q1       | Convert categorical page views into numeric estimates |
| Q2       | Get summary stats of page views by profile |
| Q3       | Compute total page views by profile |
| Q4       | Gender proportions across user profiles |
| Q5       | Frequency of recent purchases by profile |
| Q6       | Visualize purchase recency by profile |
| Q7       | Proportion of recent purchases |
| Q8       | Total purchases by profile and gender |
| Q9       | Purchase rate (conversion rate) by profile and gender |

---

## 📊 Key Visuals

- **Barcharts** showing number of recent purchases by profile
- **Gender-proportional tables** across user types
- **Boxed summaries** for behavioral metrics

---

## 📈 Example Insights

- **Teachers** showed higher recent purchase rates.
- **Females** had slightly higher conversion rates than males within some profiles.
- Higher **page views** often corresponded with a higher likelihood of purchase.

---

## 💻 How to Run

```r
# Required libraries
install.packages("lattice")  # For barchart

# Run the analysis
source("ecommerce_user_analysis.R")
