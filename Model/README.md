# Personal Expense Tracker with Visual Reports

## Project Overview
The **Personal Expense Tracker** is a Python application designed to help users record, manage, and analyze their daily expenses. Users can add expenses, view all records, filter by category or date, generate visual charts, and export data for reporting. This project demonstrates Python programming, file handling, data analysis using `pandas`, and data visualization with `matplotlib` and `plotly`.

## Features
1. **Add Expense**: Record the expense **amount**, **date**, **category**, and **note**.  
2. **View All Expenses**: Display all stored expense records.  
3. **Filter Expenses**: Filter by **category** or **specific date**.  
4. **Generate Charts**:  
   - **Bar Chart** → Total expenses by category (`bar_chart.png`).  
   - **Pie Chart** → Expense distribution by category (`pie_chart.png`).  
   - **Line Chart** → Monthly expense trend (`monthly_trend_line.png`).  
5. **Export Expenses**: Save all expenses to **CSV** for external analysis (`expenses.csv`).  
6. **Reset All Data**: Delete all previous expense records safely.  

## Requirements
- Python 3.x
- pandas library (`pip install pandas`)
- matplotlib library (`pip install matplotlib`)

## How to Run
1. Place `expense_tracker.py` and `expenses.json` (or `.csv`) in the same folder.
2. Open terminal/command prompt and navigate to the folder.
3. Run the program:
    python expense_tracker.py
4. Follow the menu to add, view or filter expenses, generate charts, export expenses to CSV,exit program or Reset all data.

## Files
- `expense_tracker.py` → Python program
- `expenses.json` → Stores expense records permanently.
- `expenses.csv` → Exported CSV file for reporting.
- `User_Guide.docx` → Short guide for users
- Graphs will be saved as PNG files in the same folder.
