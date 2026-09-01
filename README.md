# SmartBank Banking Application

SmartBank is a desktop banking application developed in Java using JavaFX. The project was created to apply object-oriented programming concepts while simulating common banking operations such as account creation, deposits, withdrawals, and transaction tracking.

## Features

- Create and manage different types of bank accounts
- Support for savings and credit accounts
- Deposit and withdraw funds
- View account balances and account information
- Record and display transaction history
- Validate transactions based on account requirements
- Handle insufficient balances using a custom exception
- Navigate the application through a JavaFX graphical user interface

## Technologies Used

- Java
- JavaFX
- Object-Oriented Programming (OOP)
- Eclipse IDE

## Object-Oriented Programming Concepts

This project demonstrates several core object-oriented programming concepts:

### Inheritance
`SavingsAccount` and `CreditAccount` extend the base `BankAccount` class, allowing shared account behavior to be reused while supporting account-specific functionality.

### Encapsulation
Account information and transaction data are managed through classes and methods that organize the application's data and behavior.

### Polymorphism
Different account types can implement account operations differently based on their individual requirements.

### Exception Handling
A custom `InsufficientBalanceException` is used to handle transactions that cannot be completed because of account balance requirements.

## Project Structure

```text
src/
├── module-info.java
└── application/
    ├── Main.java
    ├── BankAccount.java
    ├── SavingsAccount.java
    ├── CreditAccount.java
    ├── Transaction.java
    ├── InsufficientBalanceException.java
    └── application.css

What I Learned

Through this project, I gained hands-on experience designing a Java application using object-oriented programming principles. I also strengthened my understanding of inheritance, exception handling, collections, account validation logic, and building graphical user interfaces with JavaFX.

## Future Improvements

Some improvements I would like to explore include:

- Saving account information to a database
- Adding user authentication
- Improving input validation
- Expanding transaction filtering and account history
- Refining the user interface

## Author

**Kimberly Nguyen**

Information Systems Student interested in cybersecurity, cloud computing, and software development.
