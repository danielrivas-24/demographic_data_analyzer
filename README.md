# Demographic Data Analyzer

This project is part of the **freeCodeCamp Data Analysis with Python** certification.  
The goal is to analyze demographic data extracted from the 1994 U.S. Census database using **Pandas**.

---

## 📊 Dataset

The dataset used is the [Adult dataset from the UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult).  

It contains demographic information such as age, education, occupation, and salary.  
For convenience, the dataset has been saved as `data/adult.data.csv` with headers.

---

## 🚀 Project Structure
demographic_data/
│
├── data/
│   └── adult.data.csv         # Dataset with headers
├── demographic_data_analyzer.py  # Main analysis code
├── main.py                       # Entry point to run analysis
├── test_module.py                # Unit tests
└── README.md                     # Project documentation
---

## 📝 Tasks

The script `demographic_data_analyzer.py` answers the following questions:

1. How many people of each race are represented in the dataset?
2. What is the average age of men?
3. What is the percentage of people with a Bachelor's degree?
4. What percentage of people with advanced education (Bachelors, Masters, Doctorate) earn >50K?
5. What percentage of people without advanced education earn >50K?
6. What is the minimum number of hours a person works per week?
7. What percentage of people who work the minimum number of hours per week have a salary of >50K?
8. What country has the highest percentage of people that earn >50K, and what is that percentage?
9. What is the most popular occupation for those who earn >50K in India?

All results are rounded to **1 decimal place** when necessary.

---

## ⚙️ Installation

Clone this repository and install the dependencies:

```bash
git clone <YOUR_REPO_URL>
cd demographic_data
pip install -r requirements.txt
