# Python Coding Challenge

A hands-on Jupyter Notebook challenge covering **core Python fundamentals** and **introductory data analysis with pandas**, using a real-world loan application dataset.

Each task gives a prompt with blanks to fill in. This repository contains my completed solutions.

---

## 🎓 Course

I completed this challenge as part of the **[Introduction to Data Science](https://courses.analyticsvidhya.com/courses/introduction-to-data-science)** course by **Analytics Vidhya**.

🔗 [Python Coding Challenge (course module)](https://courses.analyticsvidhya.com/courses/take/introduction-to-data-science/texts/5859138-python-coding-challenge)

---

## 📁 Project Structure

```
Python_Challenge/
├── Python Coding Challenge.ipynb   # Notebook with all tasks and solutions
├── data_python.csv                 # Loan application dataset (614 rows × 13 columns)
└── README.md                       # Project documentation
```

---

## 🧠 Skills Demonstrated

### Part 1 — Python Basics
| Topic | What was done |
|-------|---------------|
| Variables & arithmetic | Initialized variables and computed their sum |
| Functions | Wrote a reusable `addition(x, y)` function |
| Lists | Created a list of the first 5 even numbers and accessed elements by index |
| Dictionaries | Created, accessed and updated key–value pairs |
| Loops & conditionals | Used a `for` loop with the modulo operator to print even numbers from 1–20 |

### Part 2 — Data Analysis with pandas
| Topic | What was done |
|-------|---------------|
| Loading data | Read a CSV file into a DataFrame with `pd.read_csv()` |
| Exploring data | Previewed records with `.head()` and checked dimensions with `.shape` |
| Column selection | Extracted the `Loan_Status` target variable |
| Data types | Inspected a column's dtype with `.dtype` |
| Conditional logic on data | Checked a specific record's `Education` value |
| Positional indexing | Sliced rows and columns with `.iloc[]` |

---

## 📊 Dataset

`data_python.csv` contains **614 loan applications** with the following features:

| Column | Description |
|--------|-------------|
| `Loan_ID` | Unique loan identifier |
| `Gender` | Applicant gender |
| `Married` | Marital status |
| `Dependents` | Number of dependents |
| `Education` | Graduate / Not Graduate |
| `Self_Employed` | Self-employment status |
| `ApplicantIncome` | Applicant's income |
| `CoapplicantIncome` | Co-applicant's income |
| `LoanAmount` | Loan amount (in thousands) |
| `Loan_Amount_Term` | Loan term (in months) |
| `Credit_History` | Credit history meets guidelines (1 = Yes, 0 = No) |
| `Property_Area` | Urban / Semiurban / Rural |
| `Loan_Status` | Loan approved (Y / N) — **target variable** |

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab (or VS Code with the Jupyter extension)

### Installation
```bash
# Clone the repository
git clone https://github.com/MrEugeene1/Python_Challenge.git
cd Python_Challenge

# Install dependencies
pip install pandas numpy jupyter
```

### Running the Notebook
```bash
jupyter notebook "Python Coding Challenge.ipynb"
```
Run the cells from top to bottom. Keep `data_python.csv` in the same folder as the notebook.

---

## 💡 Example Snippets

```python
import pandas as pd

mydata = pd.read_csv("data_python.csv")

# Dataset dimensions
mydata.shape                 # (614, 13)

# Rows 31 to 35
mydata.iloc[30:35]

# First 5 rows of the 2nd and 3rd columns
mydata.iloc[:5, 1:3]
```

---

## 🛠️ Tech Stack
- **Python**
- **pandas** for data manipulation
- **NumPy** for numerical computing
- **Jupyter Notebook** as the interactive environment

---

## 👤 Author
**Eugene Oppong OKYERE**\
📧 eookyere4@gmail.com

---

## 📄 License
This project is for educational purposes. Feel free to use it as a learning reference.
