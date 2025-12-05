---

# **ATM Management System (C++)**

A lightweight ATM simulation developed in C++ using core Object-Oriented Programming (OOP) principles.
The system supports secure login, basic banking operations, PIN management, and persistent data storage via file handling.

---

## **Features**

* New account creation
* Secure login with masked PIN (termios)
* Deposit and withdrawal
* Balance inquiry
* PIN reset
* Logout system
* Persistent storage in `accounts.txt`
* Clean terminal-based interface

---

## **OOP Concepts Implemented**

* **Encapsulation:** Secure handling of account data
* **Abstraction:** Simple user-facing menus
* **Inheritance:** `SavingsAccount` extends `BankAccount`
* **Polymorphism:** Overridden account functions

---

## **Project Structure**

```
ATM-Management-System/
│── main.cpp
│── accounts.txt
│── README.md
```

---

## **How to Compile and Run**

### Compile

```
g++ main.cpp -o atm
```

### Run

```
./atm
```

*Note: PIN masking works on Linux/macOS terminals.*

---

## **Data File Format (accounts.txt)**

```
<AccountNumber> <PIN> <Balance>
```

Example:

```
123456789 1234 5000
987654321 4321 10000
```

---

## **Sample Interface**

Main Menu:

```
==== ATM Management System ====
1. Create New Account
2. Login to Account
3. Exit
```

After Login:

```
==== Account Menu ====
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Reset PIN
5. Logout
```

---

## **Security Features**

* Hidden PIN input
* Backspace support
* No global PIN storage
* Session-based authentication

---

## **Planned Enhancements**

* Transaction history
* Admin panel
* GUI version
* Database (SQLite/MySQL) support

---

## **Developer**

**Khush Pithva**
B.Tech CSE,
Nirma University

---
