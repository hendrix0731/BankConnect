# BankConnect
Overview:
This project implements a simple banking system in C++ that allows users to create accounts, deposit and withdraw money, change their PIN, and perform balance inquiries. It also includes an administrator interface to view the total number of accounts and details about all accounts.

Features:
Account Management: Create savings or current accounts with single or joint holders.
Deposit and Withdraw: Users can deposit and withdraw money from their accounts.
PIN Management: Users can change their account PIN.
Balance Inquiry: Check the current balance of an account.
Account Closure: Close existing accounts.
Admin Interface: Administrators can view the total number of accounts and details for all accounts.


Technologies Used:
C++
Standard Template Library (STL) for data management (vector)
Basic console I/O for user interaction
Getting Started


Prerequisites:
A C++ compiler (e.g., g++, Visual Studio)
Basic understanding of C++ programming
Compilation and Execution
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/BankConnect.git
cd BankConnect
Compile the Code:

bash
Copy code
g++ -o BankConnect banking_system.cpp
Run the Application:


Usage:
Upon running the program, users are presented with a welcome menu where they can choose to log in as an administrator, user, or exit the application.
Users can navigate through various options to create accounts, manage funds, or check their account details.
Administrators can view account statistics and details of all accounts created.
