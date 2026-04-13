# 🏦 Banking System (C++ Project)

## Overview

This is a **menu-driven Banking System** implemented in C++ using Object-Oriented Programming concepts.
It allows users to perform basic banking operations like creating an account, depositing money, withdrawing money, and checking balance.

---

## Features

*  Open a new bank account
*  Deposit money
*  Withdraw money
*  Balance enquiry
*  Close account
*  View all accounts
*  File handling for data persistence

---

##  Concepts Used

* Object-Oriented Programming (OOP)

  * Classes & Objects
  * Constructors
  * Encapsulation
* STL (`map`)
* File Handling (`ifstream`, `ofstream`)
* Operator Overloading (`<<`, `>>`)
* Exception Handling

---

## 📂 Project Structure

```
Banking_System/
│
├── banking.cpp        # Main file (menu-driven program)
├── Bank.cpp           # Bank class implementation
├── Account.cpp        # Account class implementation
├── Bank.data          # File to store account data
```

---

## ⚙️ How to Run the Project

### Step 1: Open project in VS Code

* Open folder in VS Code
* Open terminal

---

### Step 2: Compile the code

```bash
g++ *.cpp -o banking
```

---

### Step 3: Run the program

```bash
.\banking
```

---

##  Sample Output

### ▶️ Account Creation

<img width="344" height="243" alt="image" src="https://github.com/user-attachments/assets/0b8de71b-71c0-4550-be09-55de38616f5a" />

---

### ▶️ Deposit Operation

<img width="267" height="215" alt="image" src="https://github.com/user-attachments/assets/c3f90ef6-a11a-4a64-ae93-13e695f52d9b" />


---

### ▶️ Balance Enquiry

<img width="280" height="192" alt="image" src="https://github.com/user-attachments/assets/43ebc16e-ddda-4f8d-895d-4cdeeb7d7b83" />


---

### ▶️ Show All Accounts

<img width="255" height="267" alt="image" src="https://github.com/user-attachments/assets/c7134ed7-ed9a-4b9f-b87b-696f06a4310d" />


---

## 🔄 Working Flow

```
User Input → Main Menu → Bank Class → Account Class → File Storage → Output
```

---

## 💾 File Handling

* `Bank.data` stores all account details
* Data persists even after program restart

---

## ⚠️ Known Issue

* Missing `break` in `case 5` (Close Account) may cause fall-through

---

##  Future Improvements

* Add account validation
* Improve UI (GUI version)
* Add password authentication
* Use database instead of file

---

##  Conclusion

This project demonstrates the use of **OOP concepts and file handling** to simulate a real-world banking system.

---
