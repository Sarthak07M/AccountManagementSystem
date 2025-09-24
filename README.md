# AccountManagementSystem
This is a menu-driven Account Management System in Java. It allows users to create, delete, view individual accounts, and view all accounts. Account data is stored persistently using file serialization, so all information is saved across program runs.

# Account Management System in Java

![Java](https://img.shields.io/badge/Language-Java-red)
![License](https://img.shields.io/badge/License-MIT-green)

## Description
A simple Java program to create, view, and manage bank accounts with persistent storage.

This is a menu-driven Account Management System in Java. It allows users to create, delete, view individual accounts, and view all accounts. Account data is stored persistently using file serialization, so all information is saved across program runs.

---

## Features
- **Create Account:** Add a new account with account number, name, and balance.  
- **Delete Account:** Remove an existing account using the account number.  
- **View Account:** Display details of a specific account.  
- **View All Accounts:** List all stored accounts.  
- **Persistent Storage:** Accounts are stored in a file (`Accounts.txt`) using Java Object Serialization.  
- **Menu-Driven Interface:** Easy-to-use console interface for interacting with accounts.  

---

## File Structure
- `menu.java` – Main program file containing the menu system and logic.  
- `Accounts.txt` – File used to store account objects persistently (created automatically on first run).  

---

## Demo

**Sample Console Output:**
Menu

Create Account

Delete Account

View Account

View All Accounts

Save Accounts

Exit
Enter your choice:
1
Enter Details Accno, Name ,balance
101
John Doe
5000
Account Created for John Doe

Menu

Create Account

Delete Account

View Account

View All Accounts

Save Accounts

Exit
Enter your choice:
4
Account No:101
Name :John Doe
Balance :5000.0


*Note:* This shows creating an account and viewing all accounts. You can run the program to see the full menu-driven interaction.

---

## How to Run
1. Clone the repository:  
   ```bash
   git clone <repository-url>
2.Navigate to the project directory:

cd <repository-folder>

3.Compile the Java file:

javac menu.java

4.Run the program:

java menu

5.Follow the console menu to manage accounts.
