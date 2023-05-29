# ATM-machine

## Overview
The ATM simulator is a Python application that simulates an ATM machine.The application allows users to withdraw, deposit, and transfer funds between accounts, view their account balance and transactions.
## Implementation

The ATM simulator is built using object-oriented programming (OOP) principles. The application
is based on a single class: ATM.
#### ATM class:
The ATM class represents the ATM machine itself.
The class has the following properties:

&#9679; accounts: a dictionary that stores the account numbers and their corresponding account objects

&#9679; transactions: a dictionary that stores all transactions

The ATM class has the following methods:

&#9679; create_account(account_number, initial_balance): creates a new account with the specified
account number and initial balance

&#9679; login(account_number): logs in to the specified account

&#9679; logout(): logs out of the current account

&#9679; deposit(amount): deposits the specified amount into the current account and creates a new transaction

&#9679; withdraw(amount): withdraws the specified amount from the current account and creates a new transaction

&#9679; transfer(amount, destination_account_number): transfers the specified amount from the current
account to the specified destination account and creates a new transaction

&#9679;view_transactions(): displays a list of all transactions made on the current account
