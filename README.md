# Banking Application (Java)

A simple console-based banking application built in Java that simulates basic bank account operations for a single customer.

### Features

- Create a bank account with customer name and ID  
- Check current balance  
- Deposit money  
- Withdraw money  
- View the last transaction (credit/debit)  
- Menu-driven interface using a `do-while` loop and `switch` case  

### Tech Stack

- Language: Java  
- Input/Output: `java.util.Scanner` for console input  
- Structure: OOP design with a `BankAccount` class and constructor-based initialization  

### How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <repo-folder>
   ```
2. Compile and run:
   ```bash
   javac Projects/BankingApplication.java
   java Projects.BankingApplication
   ```
3. Follow the on-screen menu options (A–E).

### Usage

On running the program, you’ll see a welcome message with the customer name and ID, followed by a menu:

- `A` – Check Balance  
- `B` – Withdraw  
- `C` – Deposit  
- `D` – Previous Transaction  
- `E` – Exit  

Enter the corresponding option to perform operations until you choose to exit.
