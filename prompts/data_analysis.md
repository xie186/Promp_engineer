# Data Analysis Prompts

## Explore a Dataset

**Use case:** Get an initial understanding of a new dataset.

**Prompt:**
```
I have a dataset with the following columns: <list column names and data types>.

It contains approximately <N> rows covering <time period or scope>.

Please suggest:
1. Key summary statistics I should compute first.
2. Potential data quality issues to check (missing values, outliers, duplicates).
3. Three exploratory analysis questions worth investigating.
4. Appropriate visualizations for the most important columns.
```

---

## Write a SQL Query

**Use case:** Generate a SQL query from a plain-English description.

**Prompt:**
```
Write a SQL query for the following request:

Database type: <PostgreSQL / MySQL / SQLite / BigQuery / etc.>
Tables available:
- <table_name_1>(<column1>, <column2>, ...)
- <table_name_2>(<column1>, <column2>, ...)

Request: <describe what data you need, e.g., "total sales per region for Q1 2024, ordered by revenue descending">

Include comments explaining each major clause.
```

---

## Interpret Statistical Results

**Use case:** Translate statistical output into plain-English findings.

**Prompt:**
```
Interpret the following statistical results in plain English for a non-technical audience:

Analysis type: <e.g., linear regression / A/B test / ANOVA>
Results:
<paste output here>

Explain:
1. What the results mean in business / practical terms.
2. Whether the findings are statistically significant and what that implies.
3. Any important caveats or limitations.
```

---

## Write a Python Data Analysis Script

**Use case:** Generate a starter script for a specific analysis task.

**Prompt:**
```
Write a Python script using pandas (and matplotlib/seaborn if needed) to perform the following analysis:

Data source: <file path or description, e.g., a CSV with columns A, B, C>
Task: <describe the analysis, e.g., compute monthly averages of column B grouped by column A and plot a bar chart>

Include:
- Loading the data
- Cleaning steps (handle missing values and wrong dtypes)
- The core analysis
- A saved output file or plot
- Clear variable names and comments
```
