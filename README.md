Bank Management System
Overview
This Bank Management System is a terminal-based project developed in C++ using Object-Oriented Programming (OOP) concepts. It simulates basic banking functionalities like account creation, deposit, withdrawal, balance inquiry, and viewing account details. The project is designed to be simple and efficient, providing a hands-on demonstration of OOP principles in action.

Features
Account Creation: Users can create new bank accounts by providing personal details and an initial deposit.
Deposit Funds: Allows users to deposit money into their accounts.
Withdraw Funds: Users can withdraw money from their accounts with validation to prevent overdrafts.
Balance Inquiry: Users can check their current account balance.
Account Details: Displays comprehensive details about the user's account.
OOP Concepts Used
Classes and Objects: The Account class is used to create objects for each bank account.
Encapsulation: Sensitive data like accountNumber, balance, and accountHolderName are encapsulated within the class and accessed via public methods.
Inheritance: Different types of accounts (e.g., savings and current) can inherit from the base Account class.
Polymorphism: Supports dynamic operations based on account type.
File Handling: Ensures data persistence by saving and retrieving account details to/from a file.
Technology Stack
Programming Language: C++
Development Environment: Terminal/Command Line Interface (CLI)
How to Run the Project
Clone the repository to your local machine:
git clone https://github.com/your-username/Bank-Management-System.git
Navigate to the project directory:
cd Bank-Management-System

Compile the project:
g++ main.cpp -o bankSystem

Run the executable:
./bankSystem

Future Enhancements
Implement transaction history for each account.
Add password protection for enhanced security.
Introduce support for multiple users.
Develop a graphical user interface (GUI) for better user interaction.
Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome!
