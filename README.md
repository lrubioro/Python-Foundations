# Python COP2373: Core Programming & Algorithms

This repository contains a collection of Python applications and scripts developed to demonstrate proficiency in core computer science concepts, object-oriented programming (OOP), data analysis, and file management. 

## Tech Stack & Libraries
* **Language:** Python 3
* **Libraries:** `sqlite3`, `matplotlib`, `csv`, `re` (Regular Expressions), `random`
* **Concepts:** Object-Oriented Programming, Relational Databases, Data Visualization, Regex Validation, File I/O

## Featured Projects

### 1. Population Growth Database & Visualization 
* **File:** `LoryRubio_Chapter13_P.py`
* **Description:** An application that builds an SQLite relational database to store Florida city population statistics. It simulates a 2% annual population growth over 20 years, updates the database records, and generates a visual growth trajectory using `matplotlib`.

### 2. Poker Hand Simulator & Deck Object 
* **File:** `LoryRubio_Chapter11_P.py`
* **Description:** An object-oriented program featuring a custom `Deck` class. It deals a 5-card poker hand, processes user input to select cards for replacement, and simulates the draw phase while maintaining accurate deck state and auto-shuffling mechanics.

### 3. Bank Account Manager
* **File:** `LoryRubio_Chapter9_P.py`
* **Description:** An OOP-based banking system utilizing a `BankAcct` class. It manages account states (balances, interest rates, account numbers) and features methods for secure withdrawals, deposits, and dynamic interest calculations.

### 4. CSV Student Grade Tracker 
* **File:** `LoryRubio_Chapter8_P.py`
* **Description:** A file I/O utility that processes user inputs to track student examination scores. It dynamically creates and writes records to a `grades.csv` file, then reads and parses the data back into a cleanly formatted tabular display.

### 5. Regex Utilities: Spam Filter & Data Validation 
* **Files:** `LoryRubio_Chapter2_P.py`, `LoryRubio_Chapter6_P.py`, `LoryRubio_Chapter7_P.py`
* **Description:** A suite of text parsing tools that utilize Regular Expressions to validate sensitive data formats (SSN, Phone Numbers, Zip Codes), isolate sentence structures within large text blocks, and evaluate email payloads against a 30-keyword spam scoring algorithm.

##  How to Run
To run any of the scripts locally, ensure you have Python 3 installed. For the data visualization script, you will also need to install `matplotlib`:
```bash
pip install matplotlib
