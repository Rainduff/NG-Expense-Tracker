# NG-ExpenseTracker

# 💰 Terminal-Based Expense Tracker (Naija Style)

This is a **Python-based terminal application** to help you track your daily expenses in a fun and relatable way—Naija-style! It stores your entries in an SQLite database, lets you view a table of expenses, and even delete entries when needed.

---

## 🚀 Features

- 🧾 **Add Expense**: Input your daily spending and amount.
- 📊 **View Expenses**: See all expenses in a neat table.
- ❌ **Delete Expense**: Remove an item and adjust totals automatically.
- 🗃️ **Persistent Storage** using SQLite.
- 🤠 Relatable prompts with Nigerian Pidgin expressions.

---

## 🧠 How It Works

- All expense entries are saved in a local SQLite database called `expenses.db`.
- Each record includes:
  - `Date`: Automatically recorded as today's date.
  - `Spending`: Description of the item (e.g., "Suya", "Airtime").
  - `Amount`: Amount spent.
  - `Total`: Running total of all spendings.

---

## 📂 Project Structure

expense_tracker.py.py # Main script
expenses.db # Auto-created SQLite DB after first run

yaml
Copy
Edit

---

## 🧰 Requirements

Before running the script, install the required library:

```bash
pip install prettytable
▶️ How to Run
Clone the repo or download expense_tracker.py.py.

Run the script in your terminal:

bash
Copy
Edit
python expense_tracker.py.py
Follow the menu:

pgsql
Copy
Edit
Choose your desired category by entering any number between 1 to 4:

1. Add Expense
2. View Data
3. Delete Data
4. Exit
✍️ Sample Interaction
go
Copy
Edit
Wetin you go buy, Duff?!!: Recharge Card
How much Wey you spend!!: 500

Choose your desired category...
🛠 Functions Breakdown
Function	Description
create()	Initializes the database table.
data_entry()	Collects new expense and updates total.
view_data()	Displays all records in a tabular format.
delete_data()	Deletes selected expense and recalculates total.

📌 Improvements to Consider
Input validation improvements.

Add category tagging (Food, Transport, Bills, etc.).

Export to CSV feature.

Monthly summary or analytics.

📚 Dependencies
Python 3.x

sqlite3 (built-in)

datetime (built-in)

prettytable

🙌 Author
Utomobong Duff
Passionate about building local-first, relatable software with tech.

"Make we dey track our money before e track us!" 😄
