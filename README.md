
# 🏧 ATM System

![Java](https://img.shields.io/badge/Language-Java-blue.svg)
![License](https://img.shields.io/badge/License-Educational-informational)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

A simple console-based ATM System built with Java as part of *CODSOFT Task*.

## 📌 Overview

This ATM system simulates the core functions of an ATM:
- Check account balance
- Deposit money
- Withdraw money
- Exit the system

It's a beginner-friendly project demonstrating how to use Java for console applications and handle basic banking operations.

## ✨ Features

✅ User authentication with PIN or password (if implemented)  
✅ Check current balance  
✅ Deposit money to account  
✅ Withdraw money with balance check  
✅ Simple, text-based menu system  
✅ Clean and easy-to-follow code structure

## 🧩 How It Works (Logic)

- Show a menu with options:  
  - 1️⃣ Check Balance  
  - 2️⃣ Deposit  
  - 3️⃣ Withdraw  
  - 4️⃣ Exit
- Use Scanner to get user input.
- For deposit: add the amount to balance.
- For withdraw: check if balance is sufficient → subtract if yes, otherwise show an error.
- Repeat the menu until the user chooses to exit.

> Note: This is a simulation; it doesn’t connect to a real database.

## ⚙ How to Run
Make sure you have Java installed.
# Clone the repository
git clone https://github.com/HARINISRI2907/ATM-System.git

# Go to project directory
cd ATM-System

# Compile the Java program
javac ATMSystem.java

# Run the program
java ATMSystem

> Replace ATMSystem.java with your actual file name if it’s different.

📂 Project Structure

ATMSystem.java – Java source code containing the ATM logic.
ATMScreenshot.png – Screenshot or sample image of the console interface (if you have one).

🔮 Future Improvements

🚀 Add PIN verification and multiple user accounts
🚀 Save account data to file or database
🚀 Track transaction history
🚀 Add GUI using Java Swing or JavaFX
🚀 Add transfer between accounts


🛠 Technologies Used

Java (console application)
Scanner (for user input)

✏ Author
SharmilaV19 

📄 License
This project is created for educational purposes.
