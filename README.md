# 📊 A/B Testing – Marketing Conversion Analysis

## 📌 Project Overview
This project performs **A/B Testing (Hypothesis Testing)** to evaluate whether displaying ads leads to a higher conversion rate compared to a public service announcement (PSA).

The analysis is implemented in **Python** using statistical testing techniques and follows a real-world data analytics workflow.

---

## 🛠 Tools & Libraries Used
- Python
- Google Colab / Jupyter Notebook
- pandas
- numpy
- scipy
- matplotlib

---

## 📂 Dataset
**marketing_AB.csv**

### Key Columns:
- `test_group`  
  - `ad` → Treatment group  
  - `psa` → Control group
- `converted`
  - `1` → User converted  
  - `0` → User did not convert

---

## 🧪 A/B Testing Process

### 1️⃣ Group Identification
- Control Group: `psa`
- Treatment Group: `ad`

### 2️⃣ Metric Used
- **Conversion Rate** (mean of `converted` column)

### 3️⃣ Hypothesis Definition
- **H₀ (Null Hypothesis):**  
  Conversion rate of ads = conversion rate of PSA
- **H₁ (Alternative Hypothesis):**  
  Conversion rate of ads ≠ conversion rate of PSA
- **Significance Level:** α = 0.05

### 4️⃣ Statistical Test
- Two-sample **t-test** (Welch’s t-test)
- Suitable for binary conversion data

### 5️⃣ Decision Rule
- If `p-value < 0.05` → Reject H₀
- Else → Fail to reject H₀

---

## 📊 Visualization
- Bar chart comparing conversion rates between control and treatment groups.

---

## 🔍 Key Insights
- The treatment group (ads) shows a different conversion rate compared to PSA.
- Statistical testing determines whether the difference is significant.
- Results support data-driven marketing decisions.

---

## ✅ Conclusion
This project demonstrates how A/B testing can be used to validate marketing strategies using statistical methods.  
The results help determine whether advertising campaigns lead to meaningful improvements in user conversion.

---

## 👤 Author
Divakar Pal  
Data Analytics | A/B Testing Project

