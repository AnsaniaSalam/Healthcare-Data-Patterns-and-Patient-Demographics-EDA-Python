<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D3B66&height=220&section=header&text=Healthcare%20Data%20Patterns%20%26%20Patient%20Demographics&fontSize=36&fontColor=FFFFFF&desc=Exploratory%20Data%20Analysis%20Using%20Python&descSize=18&descAlignY=68" alt="Healthcare Data Patterns and Patient Demographics banner" width="100%"/>

![Python](https://img.shields.io/badge/Python-1565C0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-0D3B66?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-1565C0?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-0D3B66?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-42A5F5?style=for-the-badge&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-1565C0?style=for-the-badge&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-42A5F5?style=for-the-badge)

**🏥 An exploratory data analysis of 55,500 hospital admission records 🩺**

</div>

---

## 📋 Overview

This project analyses hospital admission records to understand the patient profile and to study billing and length of stay across medical conditions, insurance providers and admission types. The work is done in a Jupyter Notebook using Python, from data loading and cleaning through to visualisation and insights.

**Domain:** Healthcare (hospital patient records and treatment cost analysis)

---

## 📂 Dataset

| | |
|---|---|
| 🌐 **Source** | [Kaggle: Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset) |
| 📏 **Size** | 55,500 rows and 15 columns |
| 🧾 **Each row** | One hospital admission record for one patient |
| 📅 **Period** | May 2019 to May 2024 |
| 🔢 **Column types** | 12 text, 2 integer, 1 decimal |

**Columns:** Name, Age, Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital, Insurance Provider, Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results

---

## 🎯 Objectives

1. Load the data and understand its structure and quality.
2. Clean the data and create new columns such as length of stay and age group.
3. Study the patient profile: age, gender, blood type and medical condition.
4. Find out whether billing amount and length of stay differ by medical condition, insurance provider, admission type and age group.
5. Look at how admissions change over time.
6. Summarise the main findings and suggest next steps.

---

## 🔍 Initial Data Findings

| Check | Result |
|---|---|
| ✅ Missing values | None |
| ♻️ Duplicate rows | 534 |
| 💰 Negative billing amounts | 108 |
| 📆 Date columns | Stored as text, need conversion |
| 🔤 Name column | Inconsistent capitalisation |
| ⚖️ Categories | Spread almost equally across groups |

---

## 🗺️ Project Workflow

| Phase | Stage | Status |
|---|---|---|
| 1 | 📥 Data loading and initial overview | ✅ Done |
| 2 | 🧹 Data pre-processing | ⏳ In progress |
| 3 | 📊 Exploratory data analysis and visualisations | ⬜ Upcoming |
| 4 | 💡 Insights and conclusion | ⬜ Upcoming |

---

## 🛠️ Tools and Libraries

- **Python** with **Jupyter Notebook**
- **Pandas** and **NumPy** for data handling
- **Matplotlib** and **Seaborn** for visualisation

---

## 📁 Repository Structure

```
Healthcare-Data-Patterns-and-Patient-Demographics-EDA-Python/
│
├── Healthcare_Data_Patterns_and_Patient_Demographics.ipynb   # Analysis notebook
├── healthcare_dataset.csv                                    # Original dataset
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/Healthcare-Data-Patterns-and-Patient-Demographics-EDA-Python.git
   ```
2. Install the libraries
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Open the notebook
   ```bash
   jupyter notebook Healthcare_Data_Patterns_and_Patient_Demographics.ipynb
   ```
4. Keep `healthcare_dataset.csv` in the same folder as the notebook, then run the cells from top to bottom.

---

## 👩‍💻 Author

**Ansania Salam**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D3B66?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ansania-salam)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D3B66&height=100&section=footer" alt="footer" width="100%"/>

</div>
