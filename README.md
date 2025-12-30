# Bank Account Management System (Python)

A **Python-based command-line Bank Account Management System** that allows users to create bank accounts, deposit and withdraw money, and view account balances. The system uses a CSV file as a persistent data store and leverages **Pandas** for efficient data handling.

This project is well-suited for beginners learning **Python, file handling, Pandas, and Object-Oriented Programming (OOP)**.

---

## Features

- Create a new bank account
- Deposit money into an existing account
- Withdraw money from an account
- View account balance using phone number lookup
- Persistent data storage using CSV files
- Menu-driven, interactive command-line interface

---

## Technologies Used

- **Python 3**
- **Pandas**
- **CSV file handling**
- **Object-Oriented Programming (OOP)**

---

## Project Structure

```
├── bank_account.py
├── python_bankAccount.csv
├── README.md
```

---

## Dataset Requirements

The CSV file (`python_bankAccount.csv`) must contain the following columns:

- `cust_id`
- `first_name`
- `last_name`
- `ph_num`
- `balance`

Example:

```
cust_id,first_name,last_name,ph_num,balance
1,John,Doe,1234567890,500
```

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bank-account-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd bank-account-management-system
   ```

3. Install dependencies:
   ```bash
   pip install pandas
   ```

4. Run the program:
   ```bash
   python bank_account.py
   ```

5. Follow the on-screen menu options.

---

## How It Works

- User data is loaded from a CSV file into a Pandas DataFrame
- Each operation (create, deposit, withdraw, balance check) updates the DataFrame
- All changes are saved back to the CSV file when the program exits

---

## Future Improvements

- Input validation and exception handling
- PIN/password authentication
- Transaction history tracking
- Interest calculation
- GUI or web-based interface
- Database integration (SQLite/MySQL)

---

## Learning Outcomes

- Practical use of Pandas for CRUD operations
- Understanding data persistence with CSV files
- Building menu-driven CLI applications
- Applying OOP principles in Python

---

