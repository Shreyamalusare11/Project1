📊 Personal Finance Tracker (C Program)

A simple console-based Personal Finance Tracker built in C.
This program allows users to record income/expenses, search transactions, sort by date, filter high expenses, and visualize monthly spending using ASCII bar charts.
It also supports saving/loading transactions from a file.

🚀 Features

➕ Add Transaction: Record new income or expense.

📋 View Transactions: Display all stored transactions.

🔍 Search Transactions: Find transactions by description keyword.

💸 Filter Expenses: Show expenses greater than a given threshold.

📅 Sort by Date: Arrange transactions in ascending order by date (YYYY-MM-DD).

📊 Monthly Spending Chart: Display ASCII bar chart of expenses per month.

💾 Save & Load Data: Store all transactions in transactions.txt for persistence.

🛠️ Tech Requirements

Language: C

Data Storage: Array of struct transactions

File Handling: Saves to and loads from transactions.txt (CSV-style format)

ASCII Graphics: Simple bar chart for monthly spending

📂 File Structure
finance-tracker/
│
├── transactions.txt   # Data file (auto-generated after running)
├── finance.c          # Main source code
└── README.md          # Documentation

⚙️ How to Compile & Run
On Linux / MacOS
gcc finance.c -o finance
./finance

On Windows (MinGW)
gcc finance.c -o finance.exe
finance.exe

📌 Example Usage
Menu
📌 Personal Finance Tracker
1. Add Transaction
2. View Transactions
3. Search Transactions
4. Filter Expenses Over Amount
5. Sort Transactions by Date
6. Monthly Spending Chart
7. Save & Exit
Choose an option:

Adding Transactions
Enter date (YYYY-MM-DD): 2025-09-08
Enter category (Income/Expense): Expense
Enter description: Grocery Shopping
Enter amount: 120.50
✅ Transaction added!

Viewing Transactions
--- Transaction List ---
2025-09-08 | Expense | Grocery Shopping | $120.50

Monthly Spending Chart
--- Monthly Spending Chart ---
2025-09: ############ ($120.50)

📊 Data Format

Transactions are saved in transactions.txt in CSV format:

2025-09-08,Expense,Grocery Shopping,120.50
2025-09-09,Income,Freelance Project,500.00

✅ Future Enhancements

Add export to CSV/Excel option

Support for multiple users

Enhanced search with category/date filters

More advanced visual charts

👨‍💻 Author

Developed by Shreya Malusare

GitHub: Shreyamalusare11
