# FinZPT-Personal-Budget-Manager

FinZPT — Personal Budget Manager

A command-line personal finance tracker built with core Python. Track your income, manage your expenses by category, and stay on top of your budget — all from the terminal.

---

## Features

- Add multiple income sources with amounts
- Track expenses by category (food, health, rent, entertainment, etc.)
- View a full financial summary at any time
- Automatically saves data and loads it on next use

---

## How to Use

**1. Clone the repository**
```bash
git clone https://github.com/your-username/FinZPT.git
cd FinZPT
```

**2. Run the program**
```bash
python3 FinGPT.py
```

**3. Navigate the menu**
```
-------- FinZPT --------

1. Income
2. Expenses
3. View Summary
4. Exit
```

- Choose **1** to add an income entry (source + amount)
- Choose **2** to add an expense (category + item + amount)
- Choose **3** to view your full financial summary
- Choose **4** to save and exit

---

## Example Output

```
 -- Income --
Job = 45825.0
Others = 60000.0

 -- Expenses --
Basic - Groceries = 34110.0
Health Care - Medical = 17105.0
Enjoyment - Travel = 6430.0

 --- Summary ---
Total Income :  105825.0
Total Expenses :  57645.0
Balance        :  48180.0
```

---

## Tech Stack

- **Language:** Python 3
- **Storage:** JSON file (`data.json`)
- **Concepts used:** Lists, dictionaries, loops, `input()`, `float()`, `sum()`, `json` module, file I/O, exception handling

---

## Project Status

Active — being developed step by step as a learning project.

**Planned features:**
- Budget limits with warnings
- Savings and investment tracking
- Monthly reports
- AI-powered financial suggestions (FinGPT)

---

## Author

**Tasnim Al-Hasan**  
BS in Computer Science & Engineering  
Building toward a career in tech and finance.

---

*Built from scratch as a real learning project — no tutorials copied, every line understood.*
