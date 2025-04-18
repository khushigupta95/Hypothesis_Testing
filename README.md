# 🧪 Hypothesis Testing Project

## 📌 Project Overview
This project is an end-to-end guide to **Hypothesis Testing**, a fundamental concept in statistics used for data-driven decision-making. It walks through defining hypotheses, selecting appropriate tests, performing statistical analysis, and interpreting results.

## 🎯 Objectives
- Understand the concept of **Null & Alternative Hypotheses**
- Learn when to apply different **Hypothesis Tests**
- Use statistical methods to validate assumptions and make inferences
- Perform **Hypothesis Testing using Python** (or Excel, if applicable)

## 🛠️ Tools & Libraries
- **Python** (Jupyter Notebook )
- **Libraries:** `pandas`, `numpy`, `scipy.stats`, `matplotlib`, `seaborn`

│── 📄## 📥 Dataset
You can download the dataset from the following link:
[NYC Taxi Data - January 2020](https://data.world/vizwiz/nyc-taxi-jan-2020/workspace/file?filename=yellow_tripdata_2020-01.csv) # Raw dataset

│── 📄-<a href="https://github.com/khushigupta95/Hypothesis_Testing/blob/main/MaximizingRevenue.ipynb">Jupyter Notebook</a> # Jupyter Notebook with step-by-step guide


## 📂 Project Structure
```
## 📖 Step-by-Step Guide
### 1️⃣ Define the Hypothesis
- **Null Hypothesis (H₀):** Statement assuming no effect or difference (e.g., "There is no difference beacause of payment method")
- **Alternative Hypothesis (H₁):** Contradicts H₀ (e.g., "There is a difference because of payment method.")

### 2️⃣ Choose the Right Hypothesis Test
- **T-Test:** Compare means between two groups
- **ANOVA:** Compare means among multiple groups
- **Chi-Square Test:** Check relationships between categorical variables
- **Z-Test:** Compare proportions when sample size is large


### 3️⃣ Load & Explore Data
- Import dataset (`pandas`)
- Check missing values, outliers, and basic statistics
- Visualize distributions (`seaborn`, `matplotlib`)

### 4️⃣ Data Cleaning & Preparation
- Handle missing values by **imputation or deletion**
- Remove **outliers** using statistical methods (IQR, Z-score)

### 5️⃣ Perform Hypothesis Testing
- Select the appropriate statistical test (`scipy.stats`)
- Calculate **p-value** (probability of obtaining observed results under H₀)
- Compare with significance level (**α = 0.05**) to accept/reject H₀

### 6️⃣ Visualizing Results
- Use **Boxplots, Histograms,** to compare distributions
- Plot **confidence intervals** to assess uncertainty
- Display **bar charts** for categorical comparisons


### 5️⃣ Interpret the Results
- **If p-value < 0.05** → Reject H₀ (significant effect)
- **If p-value > 0.05** → Fail to reject H₀ (no significant effect)


