# Amortization Project

This Python project calculates loan amortization schedules and generates various output files.

## Installation

**1. Python Version:**

Make sure you have Python version 3.10 or later installed. You can check your version by running `python --version` or `python3 --version` in your terminal.

**2. Install Dependencies:**

Install the required packages using `pip`:

```bash
pip install -r requirements.txt
```
This command installs all the packages listed in the requirements.txt file.

**3. Run the Script:**

Locate the Jupyter Notebook file (usually named *.ipynb).
Open it in a Jupyter Notebook environment or a compatible web-based notebook viewer.
Execute the code cells in the notebook to run the amortization calculations.
Data Management
data_lake Folder: This directory stores the original Excel files containing loan data.

Output Files
The project generates various CSV files categorized by their content:

consolidated_daily: Daily amortization schedules for all loans (one CSV file per date).
consolidated_monthly: Monthly amortization schedules for all loans (one CSV file per date).
periodic_data_amortization: Loan-specific amortization schedules (one CSV file per loan).
daily_data_amortization: Daily amortization schedules for each loan (one CSV file per loan).
monthly_data_amortization: Monthly amortization schedules for each loan (one CSV file per loan).
This structure allows you to easily access the specific amortized loan data you need.

