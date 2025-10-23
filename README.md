# ATM Simulation System — Python Project

## Overview
The ATM Simulation System is a console-based Python application that emulates the basic functionalities of a real Automated Teller Machine (ATM).  
It allows users to perform secure banking operations such as deposits, withdrawals, balance inquiries, PIN changes, and mini-statements — all in a simple, interactive command-line interface.

Designed for learning and demonstration, this project helps beginners understand fundamental programming concepts like:
- Loops and conditionals  
- User input handling  
- Data structures (dict, list)  
- Basic authentication  
- Transaction management  

## Concepts and Technologies

### Core Concepts
- User Authentication (Account Number + PIN)
- Session Management (Lock after 3 failed attempts)
- Transaction Recording (Deposit/Withdraw)
- PIN Validation and Change
- Mini Statement Generation

### Technologies Used
| Category | Technology |
|-----------|-------------|
| Programming Language | Python 3.x |
| Data Structure | Dictionary, List |
| Interface | Command-Line (CLI) |
| File Type | .py Script |

## Features
- Login System — Authenticate with account number and PIN  
- Deposit — Add funds to your account  
- Withdraw — Withdraw cash securely with balance check  
- Balance Enquiry — View your current balance instantly  
- PIN Change — Change your PIN safely after verification  
- Mini Statement — View your last three transactions  
- Account Lock — After three invalid PIN attempts  
- Session Memory — Keeps track of transactions during login  

## Dependencies
This project uses only standard Python libraries — no external modules are required.  
Works out-of-the-box with Python 3.7 or higher.


## How to Run

### Step 1: Clone or Download
```bash
git clone https://github.com/yourusername/atm-simulation.git
cd atm-simulation
````

### Step 2: Run the Script

```bash
python atm.py
```

### Step 3: Follow On-Screen Instructions

You’ll be asked to:

* Enter your account number
* Enter your PIN
* Choose operations from the menu


## Future Enhancements

* Persistent Storage: Save user data and transactions in a database or JSON file
* Transaction Time Tracking: Add timestamps to each deposit or withdrawal
* GUI or Web Interface: Build a simple front-end using Tkinter or Flask
* Enhanced Security: Hash and store PINs securely
* User Registration System: Allow new users to create accounts


## License

This project is licensed under the MIT License.
