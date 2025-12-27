# Simple ATM System (C++)

A lightweight and efficient **Automated Teller Machine (ATM)** simulation built with C++. This project demonstrates the core concepts of Procedural Programming, File Handling, and Data Management.

## 🚀 Features
- **Secure Login:** Validates account number and PIN against a data file.
- **Transaction Management:** Supports Deposits and Withdrawals.
- **Quick Withdraw:** Fast access to common withdrawal amounts.
- **Data Persistence:** All client data and balances are stored and updated in a text file (`Clients.txt`).
- **Input Validation:** Robust handling of user inputs to prevent system crashes.

## 🛠️ Technical Skills Demonstrated
- **File Stream (fstream):** Reading and writing records.
- **Data Structures:** Using `struct` and `vector` for efficient data manipulation.
- **String Processing:** Custom string splitting and record parsing logic.
- **Clean Code:** Organized into modular functions for better readability and maintenance.

## 📂 File Format
The system uses a `#//#` delimiter to store data:
`AccountNumber#//#Name#//#Pincode#//#Balance#//#Phone`

## 🖥️ How to Run
1. Clone the repository.
2. Ensure you have a `Clients.txt` file in the same directory.
3. Compile using any C++ compiler (e.g., g++, Visual Studio):
   ```bash
   g++ main.cpp -o ATM_System
   ./ATM_System
