# ❤️ HeartHealth Insights: Risk Factors & Trends in Heart Disease

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-008080?style=for-the-badge&logo=gnuplot&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-FF6F00?style=for-the-badge&logo=apacheairflow&logoColor=white)

---

## 📊 Project Overview
**HeartHealth Insights** is a data analytics project focused on understanding **heart disease patterns and risk factors** using real-world patient data. By analyzing diagnostic and lifestyle indicators, this project provides actionable insights for healthcare professionals to understand heart disease prevalence and correlations in patient populations.

The project uses the **Heart Disease UCI Dataset** to perform:  
- **Data Cleaning**  
- **Exploratory Data Analysis (EDA)**  
- **Statistical Analysis**

---

## 📁 Dataset
**Title:** Heart Disease UCI Dataset  
**Source / Download Link:** [Kaggle – Heart Disease Cleveland UCI](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)

**Dataset Description:**  
- Health metrics include **age, gender, chest pain type, cholesterol, fasting blood sugar, maximum heart rate**, and more.  
- The **target variable** indicates the **presence or absence of heart disease**.

---

## 📂 Directory Structure
HeartHealth-Insights/
├─ data/             # Raw & processed datasets  
├─ notebooks/        # Jupyter notebooks for EDA & analysis  
├─ scripts/          # Python scripts for preprocessing & analysis  
└─ README.md


---

## 🎯 Project Objectives / Questions Explored
- 🔹 Identify factors (age, gender, cholesterol, etc.) associated with heart disease.  
- 🔹 Compare heart disease prevalence between **male** and **female** patients.  
- 🔹 Explore how **maximum heart rate (thalach)** varies across age groups or disease status.  
- 🔹 Determine if **fasting blood sugar** is related to heart disease.  
- 🔹 Examine the relationship between **chest pain type** and heart disease risk.

---

## 🛠️ Methodology

### 1️⃣ Data Cleaning
- Renamed technical columns to **meaningful labels** (`cp` → **Chest Pain Type**, `thalach` → **Max Heart Rate`).  
- Handled **missing or abnormal values**.  
- Converted **categorical variables** into interpretable formats (e.g., chest pain types, gender).

### 2️⃣ Exploratory Data Analysis (EDA)
- Libraries: **Seaborn, Matplotlib, Plotly**  
- Graph types:  
  - Count plots for categorical features  
  - KDE plots and histograms for continuous features  
  - Box plots for comparing features across disease status  
  - Pair plots for feature relationships  
- Analyzed **distribution of target variable** for disease prevalence.

### 3️⃣ Insight Generation
- Identified **correlations and patterns** between patient attributes and heart disease.  
- Performed **grouping and aggregation** to compare subgroups (age, gender, chest pain type).  
- Applied **basic statistical tests** (T-test, Chi-square) to validate findings.

### 4️⃣ Optional Enhancements
- 🔹 SQL queries for subgroup analysis (e.g., average cholesterol by age/gender)  

---

## 💡 Key Insights 
- ❤️ Chest pain type strongly correlates with heart disease risk.  
- 👨 Males show a higher prevalence of heart disease than females.  
- 💓 Maximum heart rate decreases with age and varies between patients with and without heart disease.  
- 🍬 Fasting blood sugar has minor correlation with heart disease.

---

## 💻 Tech Stack
- **Programming Languages:** Python, SQL  
- **Libraries / Tools:** Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook  
- **Techniques:** EDA, Statistical Analysis, Data Cleaning, Visualization  

---

## 👥 Team Members & Roles
- 👨‍💻 **Suraj Mate** – Data Cleaning, Preprocessing  
- 👨‍💻 **Akash Khushwaha** – Exploratory Data Analysis (EDA)  
- 👨‍💻 **Honey Mathur** – Insight Generation, Visualization  
- 🌏 **Location:** India  

---

## 📫 Connect With Us
- ✉️ Email: **smate4986@gmail.com**  
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suraj-mate12/) **Suraj_Mate**


---

## 🙏 Thank You
Thank you for visiting the repository!  
We are passionate about **Data Analysis, Machine Learning, Deep Learning, and Healthcare Analytics**.  
Feel free to explore, connect, and collaborate!

---

## ⚙️ Installation & Usage
1. Clone the repository:  
```bash
git clone <repo-link>
