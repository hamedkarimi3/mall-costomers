
# 🛍️ Mall Customer Segmentation & Spending Score Analysis

This project performs a spending behavior analysis on the **Mall Customers dataset** using **Apache PySpark** within a professional **WSL-based environment**. It focuses on understanding customer segmentation by analyzing **spending scores** across different **age groups, income levels, and gender**, and applies clustering techniques for better insights.

This project was developed as part of an internship assignment.

---

## 🚀 Technologies Used

- **PySpark 3.5.5** – For scalable DataFrame processing
- **Python 3.11.8 (via pyenv)** – Managed inside WSL
- **WSL 2 (Ubuntu 24.04)** – Linux environment on Windows
- **VSCode + Remote - WSL** – Development setup
- **Jupyter Notebook** – Interactive analysis
- **Pandas & Seaborn** – Optional for visualization
- **Scikit-learn** – For KMeans clustering (optional)

---

## 📂 Project Structure

```
Mall_Customers_Analysis/
│
├── data/
│   └── Mall_Customers.csv             # Raw dataset
│
├── notebooks/
│   └── analysis.ipynb                 # Full Jupyter analysis notebook
│
├── src/
│   ├── load_data.py                   # Load dataset using Spark
│   ├── spending_score_analysis.py     # Grouping and visual analysis
│
├── reports/
│   ├── Analysis_Report.docx           # Word report with insights
│   └── Challenges_Faced.docx          # Challenges & resolutions
│
├── outputs/
│   ├── charts/                        # Exported visualizations
│   └── cleaned_data.csv               # Optional cleaned output
│
├── requirements.txt                   # All required Python packages
└── README.md                          # Project overview (this file)
```

---

## 🧠 Analysis Focus

- 🔍 Spending Score vs. Age
- 💸 Spending Score vs. Annual Income
- 👩‍🦰 Gender-based behavior
- 🔄 Customer Clustering (KMeans - optional)

---

## 📈 Deliverables

- ✅ Spark-based analysis in Jupyter Notebook
- ✅ Word report with summary and challenges
- ✅ Cleaned data and visualizations (optional)
- ✅ Documented environment and setup steps

---

## ▶️ How to Run

1. Activate virtual environment:
   `source venv/bin/activate`

2. Run analysis script:
   `python3 src/spending_score_analysis.py`

3. Or launch notebook:
   `jupyter notebook notebooks/analysis.ipynb`

---

## ⚙️ Environment Summary

- OS: Ubuntu 24.04 via WSL2
- Python: 3.11.8 (via pyenv)
- Spark: 3.5.5 (local mode)
- Editor: VSCode with Remote - WSL
- Notebook: Jupyter in WSL, using correct venv kernel

---

## 🗃️ Dataset Source

[📦 Mall Customers Dataset (Google Drive)](https://drive.google.com/file/d/1k6A8r1cCdt0Ft0mPtvnYckruaTn2XXz0/view?usp=share_link)

---

## 📝 Author

**Team4**  
Intern – Mall Customer Segmentation Project  

---
