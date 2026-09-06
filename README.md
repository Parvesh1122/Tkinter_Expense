💰 Expense Tracker

A desktop Expense Tracker application built with Python and Tkinter
to help users record, manage, filter, analyze, and export their daily
expenses.

✨ Features

Add new expense records

Record date, category, amount, and notes

Expense categories:

Food

Travel

Shopping

Bills

Other

Automatic validation for dates and amounts

View expenses in a table

Filter expenses by date range

Filter expenses by category

Calculate total expenses

Calculate average expense

Display total number of records

Generate a spending distribution pie chart

Load expenses from CSV files

Automatically save expenses to expenses.csv

Export filtered expenses to CSV

Delete selected expense records

Clear all expense records

Simple graphical user interface

🛠️ Technologies Used

Python

Tkinter -- GUI development

Pandas -- data management and CSV operations

NumPy -- numerical calculations

Matplotlib -- expense visualization

The project imports these libraries directly in the application.
fileciteturn4file0L1-L7

📊 Expense Data

Each expense record contains:

Field      Description

Date       Expense date in YYYY-MM-DD format
Category   Expense category
Amount     Expense amount
Note       Optional description

The application stores these fields in a Pandas DataFrame.
fileciteturn4file0L12-L17

📁 Project Structure

Expense-Tracker/
│
├── project.py
├── expenses.csv
├── project.spec
└── README.md

⚙️ Installation

1. Install Python

Make sure Python 3 is installed on your computer.

2. Install Required Libraries

Open a terminal in the project folder and run:

pip install pandas numpy matplotlib

Tkinter is normally included with standard Python installations.

▶️ Run the Application

Run the following command:

python project.py

The Expense Tracker window will open.

📝 How to Use

Enter or select the expense date.

Select an expense category.

Enter the amount.

Add an optional note.

Click Add Expense.

Use the filters to view expenses for a specific date range or
category.

Click Show Pie Chart to view spending distribution.

Use Load CSV to import existing expense data.

Use Export Filtered CSV to save the current filtered records.

Select records and click Delete Selected when needed.

📈 Summary & Analysis

The application displays:

Total -- sum of all displayed expense amounts

Average -- average expense amount

Records -- number of expense records

It also provides a pie chart showing spending distribution by category.
fileciteturn4file0L169-L195

💾 CSV Support

The application can load CSV files containing at least:

Date, Category, Amount

The Note column is optional and will be added when it is missing.
fileciteturn4file0L197-L217

New expenses and changes are automatically saved to expenses.csv.
fileciteturn4file0L121-L130

🔮 Possible Improvements

Monthly and yearly expense reports

Budget limits and alerts

More chart types

Income tracking

Savings calculation

Search functionality

Dark mode

Database support

User login system

👨‍💻 Project Purpose

This project is designed as a practical Python application for managing
and analyzing daily expenses. It demonstrates GUI development, data
handling, CSV file operations, and data visualization using Python.
