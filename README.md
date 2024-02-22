# Bank Management System Project

## Overview

This project is a simple bank management system implemented in Java using object-oriented programming principles. The system provides functionality for managing different types of bank accounts, including savings and current accounts, through a user-friendly command-line interface.

## Features

- Creation of new savings and current accounts
- Deposit and withdrawal operations for accounts
- Enforcement of minimum balance and credit limit rules for savings and current accounts respectively
- Display of account details including account number, account name, and account balance

## Project Structure

The project consists of the following main components:

1. **BankAccount Classes**: Includes abstract classes (`BankAcc`, `SavingAcc`, `CurrentAcc`) and concrete classes (`MMSavingAcc`, `MMCurrentAcc`) representing different types of bank accounts.

2. **BankFactory**: An abstract factory class (`BankFactory`) responsible for creating instances of `SavingAcc` and `CurrentAcc`. Concrete subclasses (`MMBankFactory`) provide implementations for creating specific types of accounts.

3. **Main Application**: Contains the entry point (`Main` class) for the bank management system. It demonstrates the functionality of the system by creating instances of accounts, performing deposit and withdrawal operations, and displaying account details.

4. **Dependencies**: The project utilizes Spring Boot framework for dependency injection and application configuration.

## Usage

To run the bank management system:

1. Ensure you have Java Development Kit (JDK) installed on your system.
2. Clone the project repository to your local machine.
3. Open the project in your preferred Integrated Development Environment (IDE).
4. Compile and run the `Main` class to start the application.
5. Follow the prompts in the command-line interface to interact with the system (e.g., create accounts, deposit/withdraw funds).

## Contributing

Contributions to this project are welcome. If you have any suggestions for improvements or new features, feel free to fork the repository, make your changes, and submit a pull request.

Thank you for your interest in the bank management system project. Happy banking! 🏦🚀
