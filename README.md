# 📊 Haberman Cancer Survival Dataset Analysis

## 📌 Objective
To analyze the survival chances of patients who underwent surgery for breast cancer using **Exploratory Data Analysis (EDA)** techniques.  
The goal is to uncover patterns, correlations, and insights that could help understand the factors influencing long-term survival.

---

## 📂 Dataset Information
- **Source:** [Haberman's Survival Dataset (Kaggle)](https://www.kaggle.com/datasets/gilsousa/habermans-survival-data-set)
- **Number of Instances:** 306  
- **Number of Attributes:** 4 (including target)  

### **Attributes**
1. **Age** - Age of patient at the time of operation (numeric)  
2. **Year** - Year of operation (year - 1900, numeric)  
3. **Nodes** - Number of positive axillary nodes detected (numeric)  
4. **Status** - Survival status (class attribute)  
   - `1` → Patient survived 5 years or longer  
   - `2` → Patient died within 5 years  

---

## 🛠️ Technologies Used
- **Python**  
- **Pandas**, **NumPy** – Data manipulation  
- **Matplotlib**, **Seaborn** – Data visualization  

---

## 📊 Analysis Performed
### 1. **Data Exploration**
- Checked dataset shape, column details, data types, and target variable distribution.

### 2. **Univariate Analysis**
- Histograms, PDFs (Probability Density Functions), CDFs (Cumulative Distribution Functions).
- Summary statistics: Mean, Median, Standard Deviation, Percentiles.

### 3. **Bivariate & Multivariate Analysis**
- Scatter plots & pair plots to visualize relationships between variables.
- Box plots & violin plots to compare survival status across variables.
- Contour plots for density visualization.

---

## 🔍 Key Observations
- Patients with **fewer axillary nodes (<5)** have significantly higher survival chances.
- **Median nodes** for long-term survivors = **0**, for short-term survivors = **4**.
- 75% of long-term survivors have ≤3 nodes; 90% have ≤8 nodes.
- Age between **47–60** with **0–3 nodes** shows highest survival probability.

---

## 📈 Visualizations
Some of the plots generated:
- Scatter plots (colored by survival status)
- Histograms with KDE curves
- CDF curves
- Box & violin plots
- Contour density plots

---

## 📌 Conclusion
The dataset is reliable for predicting survival chances based on **age** and **number of positive nodes**.  
The number of nodes is a **critical indicator**-fewer nodes correlate strongly with better survival rates.

---

## ▶️ How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/raicty/Exploratory-Data-Analysis.git
   cd haberman-analysis
