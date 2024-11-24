# Banking Management System

A simple, console-based **Banking Management System** built in Python to handle basic banking operations such as account creation, transaction processing, and viewing transaction history. The project includes data persistence to ensure that account and transaction details are saved between sessions.

---

## Features

1. **Account Management**:
   - Open new accounts with personal details, including PAN card verification.
   - Automatically generate account numbers, usernames, and passwords.

2. **User Authentication**:
   - Secure login using username, password, and PAN card.

3. **Transaction Operations**:
   - Deposit funds.
   - Withdraw funds with balance checks.
   - Transfer money between accounts.

4. **Transaction History**:
   - View detailed transaction history for each account.

5. **Data Persistence**:
   - Accounts and transaction histories are stored using Python's `pickle` module in `accounts.pkl` and `transactions.pkl`.

---

## Prerequisites

- Python 3.x installed on your system.
- Basic knowledge of running Python scripts.

---

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/banking-management-system.git
   cd banking-management-system
