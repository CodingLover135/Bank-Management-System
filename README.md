# Bank-Management-System
Bank Management System in C++ lets users create, deposit, withdraw, and view Savings and Current accounts. It saves data to a file, supporting persistent account management with OOP concepts.
---

## Features

- Create Savings and Current accounts with initial balance
- Deposit money into accounts
- Withdraw money from accounts (with balance checks)
- Display all existing accounts
- Persistent storage: account data is saved to and loaded from a file (`accounts.txt`)
- Handles up to 100 accounts

---

## Technologies Used

- C++
- File I/O for persistent data storage
- Object-Oriented Programming (Inheritance, Polymorphism)

---

## How to Use

1. Clone or download the repository.
2. Compile the code using a C++ compiler:
   ```bash
   g++ -o bank_system BankManagementSystem.cpp
   
Run the executable:

bash
./bank_system

Example: .........................."

:Bank Management System
        Main Menu
1. Create New Savings Account
2. Create New Current Account
3. Show All Accounts
4. Deposit Money
5. Withdraw Money
6. Exit
Enter Your Choice: 1
Enter Name: Alice
Enter Account Number: 1001
Enter Initial Balance: 5000
Savings Account Created Successfully....

Do You Want to Continue or Exit [Yes=y/No=n]? y
