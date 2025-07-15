# 🏦 Bank Management System (Java + MySQL)

This is a Java-based GUI application for simulating core banking operations, such as creating a new account, managing transactions (withdrawals, deposits), checking mini-statements, and more. The interface is designed using **Java Swing**, and all data operations are handled via **MySQL** using **JDBC**.

---

## 📌 Features

- 🔐 Multi-step account creation with form validation
- 💰 Deposit & Withdraw money (with ATM-like interface)
- 🧾 Mini statement viewing
- 🏧 Fast cash option
- 🔁 PIN change
- 📁 Account data stored securely in MySQL database

---

## 🧱 Tech Stack

- **Frontend:** Java Swing (GUI)
- **Backend:** Java (OOP + JDBC)
- **Database:** MySQL

---

## 🖥️ Screenshots

### 🔹 Page 1: Personal Details Form  
![Personal Details](https://www.linkedin.com/in/dipa-mondal-675a77344/)

### 🔹 Page 2: Additional Details  
![Additional Details](https://github.com/dipa129/BankManagementSystem/blob/main/Screenshot/Screenshot%202025-07-14%20185614.png)

### 🔹 Page 3: Account Setup  
![Account Details](https://github.com/dipa129/BankManagementSystem/blob/main/Screenshot/Screenshot%202025-07-14%20185638.png)

### 🔹 ATM Withdraw Screen  
![ATM Withdraw](https://github.com/dipa129/BankManagementSystem/blob/main/Screenshot/Screenshot%202025-07-14%20185654.png)

### 🔹 ATM PIN Change Screen  
![ATM PIN Change](https://github.com/dipa129/BankManagementSystem/blob/main/Screenshot/Screenshot%202025-07-14%20185709.png)

> All UI components are interactive and connected to the database. Data is inserted in real time and secured via backend validations.

---

## ⚙️ How to Run

1. Clone this repo or download ZIP.
2. Set up MySQL and create a database (name it something like `bankdb`).
3. Import the provided `.sql` file or manually create required tables.
4. Open the project in **IntelliJ IDEA**.
5. Configure your MySQL JDBC driver in the project.
6. Set your DB username and password inside the database connection class (e.g., `Connn.java`).
7. Run `main_Class.java` to start the application.

---

## 📚 Learnings

- GUI design using Java Swing  
- Backend logic integration with MySQL  
- JDBC connection handling and error catching  
- Multi-step form submission and data validation  
- Real-time user interaction (like ATM simulation)

---

## 📌 Project Status

✅ Fully functional and tested.  
🚀 Future plan: Add encryption for sensitive data and login authentication with user roles.

---

## 📬 Contact

**Developer:** [Dipa Mondal]  
📧 Email: [mondaldipa0108@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/dipa-mondal-675a77344/]

---

## 📄 License

This project is open-source and available under the MIT License.

