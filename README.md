# PyBank-OOP: Secure Banking System in Python

**Author:** K. Sai Sindhu

## 🚀 Project Story
Inspired by the challenges faced in modern banking, I designed this Python OOP banking system to ensure data safety, code reusability, and easy extensibility for multiple account types.

## Features
- 🔐 Encapsulation: Balance is fully guarded, accessed only by methods
- 💰 Deposit & Withdraw with input validation
- 🏦 Automated interest calculation for savings accounts
- ⚡ Overdraft control for current accounts
- 🛠 Easily add new account types!

## Quickstart
Clone the repo and run `OOPS-Banking-System.ipynb` to see interactive demos of each feature.

Example usage
ravi = SavingsAccount(101, "Ravi", 2000)
ravi.add_interest()
print("Ravi's Balance after interest:", ravi.get_balance())

## What Makes This Project Unique
- Real-world analogies and code comments for easier understanding
- Test functions for edge cases included (see below)
- Modular design: customize interest rates, overdraft limits

## Test Functions: Ensuring Safety

