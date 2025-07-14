I've created a comprehensive banking program in Java that includes:

# Key Features:

Account Management: Create new accounts with unique account numbers
Deposits: Add money to any account
Withdrawals: Remove money (with insufficient funds checking)
Balance Inquiry: Check current account balance
Account Information: Display full account details
All Accounts: View all accounts in the system

## Program Structure:

BankAccount class: Represents individual bank accounts with account number, holder name, and balance
Bank class: Manages multiple accounts using a HashMap for fast lookups
BankingProgram class: Main class with user interface and menu system

## How to Use:

Compile: javac BankingProgram.java
Run: java BankingProgram
Follow the menu prompts to create accounts and perform transactions

## Safety Features:

Prevents duplicate account numbers
Validates positive amounts for deposits/withdrawals
Checks for sufficient funds before withdrawals
Handles account not found scenarios

The program uses a simple text-based menu system and stores all data in memory (data will be lost when the program exits). For a production system, you'd want to add file persistence or database integration.
