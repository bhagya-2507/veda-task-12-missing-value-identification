# VEDA Technology – Missing Value Identification

## 📌 About the Project

This project was completed as part of the VEDA Technology Data Analytics task.

The objective is to identify missing values in a Titanic dataset, summarize their occurrence, calculate missing-value percentages, and visualize the missing data.

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 📊 Dataset

The project uses the Titanic dataset containing passenger information such as:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Family information
- Fare
- Cabin
- Embarked port

## 🔍 Analysis Performed

1. Loaded the Titanic dataset using Pandas.
2. Inspected the dataset structure and data types.
3. Identified missing values column-wise.
4. Calculated the percentage of missing values.
5. Created a bar chart to visualize missing values.
6. Documented the key findings.
7. Explained why blindly deleting missing records can be risky.

## 📈 Missing Value Summary

| Column | Missing Values |
|--------|---------------:|
| Age | 177 |
| Cabin | 687 |
| Embarked | 2 |

## 💡 Key Findings

- The `Cabin` column has the highest number of missing values.
- The `Age` column also contains a significant number of missing values.
- The `Embarked` column has only a small number of missing values.
- Missing values should be handled according to the purpose and context of the analysis.
- Rows should not be deleted blindly because useful information may be lost.

## 📁 Project Files

- `Missing_Value_Identification.ipynb` – Jupyter Notebook containing the complete analysis.
- `Titanic-Dataset.csv` – Dataset used for analysis.
- `missing_value_summary.csv` – Summary of missing values.

## 🎯 Learning Outcome

This project helped strengthen practical knowledge of data cleaning, missing-data analysis, Pandas, and basic data visualization.

## 👩‍💻 Author

Bhagya  
B.Tech Computer Science & Engineering
