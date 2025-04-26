# Data cleaning project - Titanic dataset
# Overview
This project focuses on data cleaning using the titanic dataset. It demonstrate my ability to handle real-world messy data using python and pandas. The goal is to prepare the data for further analysis or machine learning by cleaning missing values, fixing data types and removing duplicates.
----
# Dataset
- **Name:** Titanic- Machine learning from disaster
- **Source:** [Click here to view/download dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- **Shape:** 891 rows × 12 columns

---

## Tools Used

- Python  
- Pandas  
- Google Colab

---

## Cleaning Steps Performed

1. **Loaded the dataset using a public URL in Colab.**  
2. **Explored the dataset** to identify issues like missing values and wrong data types.  
3. **Handled missing values**:
   - Filled missing `Age` with mean.
   - Filled missing `Embarked` with mode.
   - Dropped the `Cabin` column due to too many missing values.
4. **Removed duplicate rows** to avoid redundancy.
5. **Converted columns to appropriate data types** (e.g., `Pclass`, `Sex`, and `Embarked` to categorical).
6. **Exported the cleaned dataset** as a new CSV file for further analysis.

---

## Final Output

- `cleaned_titanic.csv` – Clean version of the dataset
- Colab notebook – Full step-by-step cleaning process with explanations

---

## How to Run This Project

1. Open the [Colab Notebook](https://colab.research.google.com/drive/1djLIA8sWSjlmdmo_00mLwiRh1w-LW7Hr?usp=sharing).
2. Run the notebook step by step.
3. Cleaned dataset will be saved and downloadable from the end of the notebook.

---

## Author

**ISHA SHARMA**  
Python & Data Analytics Enthusiast  
GitHub: [IshaSharma0724]  

---

