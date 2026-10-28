# Task 9: Descriptive Statistics Primer

## Data Analytics Track – Veda Technology

### Objective
Calculate and interpret mean, median, mode, standard deviation, and percentiles to understand the center, spread, and distribution of data.

### Tools Used
- Python
- Pandas
- Microsoft Excel

### Dataset
A small Titanic-style sample dataset containing 20 rows and five numeric columns:
- Age
- Fare
- SibSp
- Parch
- Pclass

*Note: This is an illustrative sample dataset, not the complete Titanic dataset.*

### Tasks Completed
- Calculated mean, median, and mode.
- Calculated standard deviation to understand data spread.
- Calculated the 25th and 75th percentiles.
- Calculated the interquartile range (IQR).
- Compared mean and median to identify possible skewness.
- Interpreted the results using Excel and Python.

### Key Findings
- Mean and median help identify possible skewness.
- A large standard deviation indicates greater variation around the mean.
- The 25th and 75th percentiles describe the middle 50% of the data.
- Fare values show signs of right-skewness because the mean is higher than the median.
- Median is useful when data contains outliers or is strongly skewed.

### Interview Questions

**1. When is median a better measure of center than mean?**

Median is better when the dataset contains outliers or is strongly skewed because extreme values affect the mean more than the median.

**2. What does a large standard deviation tell you?**

A large standard deviation indicates that values are more spread out around the mean.

### Files Included
- `Task_9_Descriptive_Statistics.xlsx` – Sample data and summary statistics.
- `Task_9_Descriptive_Statistics_Report.docx` – Task completion report.
- `task9_descriptive_statistics.py` – Python analysis script.
- `task9_titanic_sample.csv` – Dataset used for analysis.

### How to Run the Python Script

Install Pandas:

```bash
pip install pandas
```

Keep the Python script and CSV file in the same folder and run:

```bash
python task9_descriptive_statistics.py
```

### Conclusion
This task helped develop practical knowledge of descriptive statistics and how they can be used to understand data distribution, central tendency, variability, and skewness.
