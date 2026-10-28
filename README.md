Task 9: Descriptive Statistics Primer
Data Analytics Track — Veda Technology
Objective
Calculate and interpret mean, median, mode, standard deviation, and percentiles for numeric columns.
Tools
- Python
- Pandas
- Microsoft Excel
Dataset
task9_titanic_sample.csv is a small, illustrative Titanic-style sample with 20 rows and five numeric columns: Age, Fare, SibSp, Parch, and Pclass. It is not the full Titanic dataset.
Files
- Task_9_Descriptive_Statistics.xlsx — sample data, summary statistics, and interpretation guide
- Task_9_Descriptive_Statistics_Report.docx — task report
- task9_descriptive_statistics.py — Python/Pandas analysis script
- task9_titanic_sample.csv — dataset used by the script
How to Run
Install dependencies:
pip install pandas
Keep the Python script and CSV in the same folder, then run:
python task9_descriptive_statistics.py
Key Findings
- Compare mean and median to identify possible skew.
- Standard deviation describes spread around the mean and should be interpreted with the mean and units.
- The 25th and 75th percentiles define the middle 50% of the data; their difference is the interquartile range (IQR).
- Fare has a mean above its median in this sample, suggesting right-skew.
- Pclass is an ordinal category, so its numerical statistics should be interpreted cautiously.
Interview Questions
When is median better than mean? When the data is skewed or contains outliers, because the median is less affected by extreme values.

What does a large standard deviation tell you? The values are widely spread around the mean.
