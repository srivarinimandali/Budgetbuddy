
# 💰 BudgetBuddy — Empowering Financial Clarity for Students

**BudgetBuddy** is a personal finance management application tailored to simplify expense tracking and budgeting—especially for international students adjusting to new financial systems. Built with Java and JavaFX, it delivers a visually intuitive UI and robust backend functionality for effective money management.

![Java](https://img.shields.io/badge/Java-Backend-brightgreen?style=for-the-badge&logo=java)
![JavaFX](https://img.shields.io/badge/JavaFX-GUI%20Framework-orange?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql)
![JDBC](https://img.shields.io/badge/JDBC-Database%20Connector-yellowgreen?style=for-the-badge)
![Data Structures](https://img.shields.io/badge/Data%20Structures-HashMap%2C%20BST%2C%20Queues-red?style=for-the-badge)
![Secure Auth](https://img.shields.io/badge/Security-Hashed%20Auth%20%7C%20Validation-critical?style=for-the-badge)

---

## 📌 Key Features

- ✍️ **Expense Tracking** — Add daily transactions by category.
- 📊 **Budget Monitoring** — Set limits per category and get alerts when nearing them.
- 💼 **Investment Oversight** — Track income, savings, and financial growth.
- 📈 **Financial Reports** — Visual charts for budgets, spending trends, and balance breakdown.
- 🔐 **Secure Login System** — Password hashing and validation ensure data privacy.
- 📂 **Modular Architecture** — JavaFX GUI, Java backend, and MySQL database integration.
- ⚙️ **Data Structures** — Uses Queues, HashMaps, Binary Search Trees, and more for efficiency.

---

## 🧱 Tech Stack

- **Frontend**: JavaFX
- **Backend**: Core Java, REST APIs
- **Database**: MySQL (via JDBC)
- **Data Handling**: Java Collections (Queue, HashMap, TreeMap)
- **Security**: MessageDigest for password hashing, validation rules
- **Libraries**: JDBC, JavaFX, Java.util, Java.security, Java.time

---

## 🛠️ Installation & Setup

### 1. Download Eclipse IDE
Get it from the [Eclipse official site](https://www.eclipse.org/downloads/).

### 2. Install MySQL
Install from [MySQL Downloads](https://dev.mysql.com/downloads/). Create a local schema for the app.

### 3. Import the Project
- Open Eclipse → `File` → `Import` → `Existing Projects into Workspace`
- Browse to the project folder and click **Finish**

### 4. Configure MySQL Connector
- Download the MySQL Connector/J `.jar` file.
- Right-click on project → `Build Path` → `Configure Build Path` → `Libraries` → `Add External JARs` → select the connector.

### 5. Update DB Credentials
In your code, locate DB config (`URL`, `username`, `password`) and replace with your local MySQL values.

### 6. Run the App
- Right-click `ExpenseTracker.java` → `Run As → Java Application`
- Set VM arguments (JavaFX SDK path) in `Run Configurations > Arguments`

---

## ▶️ How to Use

1. **Register**: Sign up with your details.
2. **Login**: Access your financial dashboard.
3. **Add Transactions**: Use `+ Income` or `+ Expense` buttons to enter data.
4. **Track & Analyze**: View summaries, alerts, and graphs under `Dashboard` and `Reports`.

---

## 📊 Visual Features

- Pie chart of financial distribution
- Budget vs. actual expense graph
- Alert when expense > savings
- Warning on high transaction amounts



## 🧠 References

- Java Collections & API Docs
- Effective Java – Joshua Bloch
- Data Structures in Java – Robert Lafore
- JDBC & JavaFX Docs

---

## 👨‍💻 Developer

**Srivarini Mandali**  
🔗 [GitHub](https://github.com/srivarinimandali)
