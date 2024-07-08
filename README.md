# banks_project

## Description
This project performs ETL (Extract, Transform, Load) operations to compile a list of the top 10 largest banks in the world ranked by market capitalization in billion USD. It then transforms the data into different currencies (USD, GBP, EUR, and INR) based on exchange rates provided in a CSV file. The processed data is saved locally in a CSV format and as a database table, which can be queried. The progress of the code at different stages is logged in a file named `code_log.txt`.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)

### Installation
To run this project, ensure you have the following installed:
- Python 3.x
- pandas
- sqlite3

### **Usage**
```markdown
1. Ensure you have the exchange rate CSV file named exchange_rate.csv in the project directory.
2. Run the script.
3. The output will be:
   1. A CSV file containing the processed information.
   2. A database file with the processed data stored in a table.
   3. A log file (code_log.txt) recording the progress of the ETL process.
```

### **File Descriptions**
```markdown
 - `banks_project.py`: The main script performing the ETL operations.
 - `exchange_rate.csv`: A CSV file containing the exchange rates.
 - `Largest_banks_data.csv`: The output CSV file with the processed bank data in multiple currencies.
 - `Banks.db`: The SQLite database file containing the processed bank data table.
 - `code_log.txt`: A log file capturing the progress of the ETL operations.
 ```
