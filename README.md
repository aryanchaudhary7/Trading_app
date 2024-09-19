# Trading App

## 📝 Overview
This Python program is a part of a **Stock Market Management System**. It provides functionality for users to:

- **Register**: Users can sign up with details like full name, PAN card, Aadhar number, phone number, and initial balance.
- **Log In**: Authenticate using a phone number and password.
- **View Wallet Balance**: Display the current balance of the user's wallet.
- **Buy and Sell Shares**: Transactions are made based on stock prices fetched from a MySQL database.
- **Manage Portfolio**: View and manage the number of shares owned for each company.

The system uses a graphical user interface (GUI) created with the `customtkinter` library and displays images using the Python Imaging Library (PIL). It interacts with a MySQL database to handle user registration, login, and management of user wallets and shares.

## ✨ Features
- **User Registration**: Sign up with comprehensive details and an initial balance.
- **User Login**: Secure authentication for accessing the system.
- **Wallet Management**: View and update your wallet balance.
- **Stock Transactions**: Buy and sell shares with real-time price updates.
- **Portfolio Management**: Track and manage shares owned in different companies.

## 📋 Requirements
- 🐍 **Python 3.x**
- 🛠️ **customtkinter**: For building the GUI.
- 🖼️ **Pillow (PIL)**: For image handling.
- 🗃️ **MySQL Connector**: For database interactions.
