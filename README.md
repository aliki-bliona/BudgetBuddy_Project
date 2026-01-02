# 💰 Budget Buddy

Budget Buddy is a Java Desktop Application designed to simplify shared expense management for teams, households, or trips. It allows users to track expenses, manage groups, and automatically calculate debts between members using a smart splitting algorithm.

## 🚀 Features

* **User Authentication:** Secure Login and Registration system.
* **Team Management:**
    * Create new teams with unique access codes.
    * Join existing teams using a code.
* **Expense Tracking:**
    * Add expenses with details (Amount, Date, Payer).
    * Select specific beneficiaries for each expense ("Paid For" list).
* **Smart Debt Calculation:** Automatically calculates who owes whom based on shared expenses.
* **Visual Interface:** User-friendly GUI built with Java Swing.
* **Persistent Data:** Uses MySQL database to store all users, teams, and transactions.

## 🛠️ Technologies Used

* **Language:** Java (JDK 8+)
* **GUI Framework:** Java Swing
* **Database:** MySQL
* **Connectivity:** JDBC (Java Database Connectivity)
* **Server:** XAMPP (Apache/MySQL)
* **Libraries:**
    * `mysql-connector-j` (Database Driver)
    * `jdatepicker` (Calendar Component)

## 📂 Project Structure

* **`src/`**: Contains the Java source code (`.java` files).
* **`database/`**: Contains the `budgetbuddy.sql` file to set up the database.
* **`lib/`**: External libraries required for the project.
* **`resources/`**: Images and assets used in the application.
* **`documentation/`**: Detailed project analysis, including:
    * Requirements (MoSCoW, Functional/Non-functional)
    * UML & Use Case Diagrams
    * Gantt Chart & Role Definitions
    * Installation Guide

## ⚙️ Setup & Installation

To run this project locally, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/aliki-bliona/BudgetBuddy_Project.git](https://github.com/aliki-bliona/BudgetBuddy_Project.git)
    ```
2.  **Database Setup:**
    * Open **XAMPP** and start Apache and MySQL.
    * Go to `localhost/phpmyadmin`.
    * Create a new database named `budgetbuddy`.
    * Import the `database/budgetbuddy.sql` file provided in this repository.
3.  **Configure Connection:**
    * The application connects to `jdbc:mysql://localhost:3306/budgetbuddy` with user `root` (no password).
    * If your MySQL config is different, update `src/XAMPPConnection.java`.
4.  **Run the App:**
    * Open the project in VS Code or Eclipse.
    * Ensure the `.jar` files in `lib/` are added to your Build Path.
    * Run `src/Main.java`.
      
## 👥 Authors

This project was created by the collaboration of  **Aliki Bliona** and a team of briliant fellow students as part of a University Project.