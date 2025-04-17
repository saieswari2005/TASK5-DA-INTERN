# TASK5-DA-INTERN
# 🚢 Task 5 - Exploratory Data Analysis (EDA) on Titanic Dataset

This project is part of a Data Analyst internship focused on performing **Exploratory Data Analysis (EDA)** using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 📌 Objective

To understand and explore the dataset using various visualization techniques, find patterns, identify missing data, and analyze relationships between variables.

---

## 📁 Files

- `EDA_Titanic.ipynb` – Jupyter Notebook with step-by-step EDA
- `titanic.csv` – Dataset file (to be manually uploaded)
- `EDA_Report.pdf` – Optional PDF report export from the notebook

---

## 🧪 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab (for cloud-based execution)

---

## ▶️ Steps to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook (`task5(DA intern).ipynb`) and your dataset (`titanic.csv`).
3. Run each cell in order:
    - Upload file using:
      ```python
      from google.colab import files
      uploaded = files.upload()
      ```
    - Load the dataset using Pandas.
    - Perform basic data checks.
    - Visualize univariate and bivariate relationships.
    - Create a correlation heatmap (numeric features only).
4. Optionally export results as a PDF or CSV.

---

## 📊 Key Analyses

- Missing value detection (heatmap)
- Distribution of age, fare, etc.
- Count plots for gender, class, and survival
- Survival analysis by gender
- Correlation matrix for numeric features

---

## 📝 Notes

- Make sure to upload the dataset before running the notebook.
- Use `.select_dtypes()` to filter only numeric columns for correlation matrix to avoid errors.

---
