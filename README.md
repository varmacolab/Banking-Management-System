# Bank Management System - Object-Oriented Programming (OOP) Documentation

The Bank Management System is designed using Object-Oriented Programming (OOP) principles to manage bank accounts and transactions efficiently.

## Classes

### 1. BankAccount Class

The `BankAccount` class represents an individual bank account with attributes and methods to manage account details and transactions.

#### Attributes:

- **name:** Stores the account holder's name.
- **accountNum:** Represents the unique account number.
- **balance:** Holds the current balance in the account.

#### Methods:

- **`__init__(self, name, accountNum, balance):`** Constructor method to initialize a new bank account with the given details.

- **`getName(self):`** Returns the account holder's name.

- **`getAccountNum(self):`** Returns the account number.

- **`getBalance(self):`** Returns the current balance.

- **`deposit(self, amount):`** Deposits the specified amount into the account.

- **`withdraw(self, amount):`** Withdraws the specified amount from the account if sufficient balance is available.

### 2. BankManagement Class

The `BankManagement` class manages a collection of bank accounts and provides methods to perform operations on multiple accounts.

#### Attributes:

- **accounts:** A vector to store instances of the `BankAccount` class.

#### Methods:

- **`AddAccount(self, name, accountNum, balance):`** Adds a new bank account to the system.

- **`showAllAccounts(self):`** Displays details of all bank accounts.

- **`searchAccount(self, accountNum):`** Searches and displays details of a specific bank account.

- **`findAccount(self, accountNum):`** Finds and returns the instance of a bank account based on the account number.

## Main Function

The `main()` function serves as the program's entry point and provides a menu-driven interface for users to interact with the bank management system.

### Design Considerations

1. **Encapsulation:** Each class encapsulates related attributes and methods, promoting modular and organized code.

2. **Composition:** The `BankManagement` class contains a vector of `BankAccount` instances to manage the association between accounts.

3. **Abstraction:** Methods like `deposit` and `withdraw` abstract the details of transactions, providing a clean interface.

4. **User Interaction:** The `main()` function orchestrates user interactions through a menu-driven approach.

## Usage

1. Create instances of the `BankAccount` and `BankManagement` classes to represent accounts and manage the bank system.

2. Interact with the system using the `main()` function, selecting options to perform various banking operations.

This Bank Management System demonstrates the effective application of OOP principles, offering a scalable and maintainable solution for managing bank accounts.



