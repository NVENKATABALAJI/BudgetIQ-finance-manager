# 💰 BudgetIQ - Full Stack Finance Management System

> A full-stack finance management application that helps users track expenses, manage budgets, analyze spending habits, and make better financial decisions through an interactive dashboard.

---

## 📌 Project Overview

BudgetIQ is a finance management platform developed to simplify personal expense tracking and budgeting.

The application allows users to record income and expenses, categorize transactions, monitor account balances, and gain financial insights through a user-friendly dashboard.

It provides a centralized system for efficiently managing daily financial activities and improving spending discipline.

---

## 🖼️ Project Screenshots

### 🏠 Dashboard

![Dashboard](images/dashboard.png)

---

### 💸 Expense Management

![Expense Management](images/expense-management.png)

---

### 📊 Financial Analytics

![Analytics](images/analytics.png)

---

### 📈 Budget Overview

![Budget Overview](images/budget-overview.png)

---

## ✨ Key Features

### 💵 Expense Management

- Add expenses
- Update expenses
- Delete expenses
- Categorize expenses
- Search expenses

### 💰 Income Management

- Add income sources
- Track income history
- Monitor available balance

### 📅 Budget Planning

- Set monthly budgets
- Track budget utilization
- Monitor remaining budget

### 📊 Financial Dashboard

- Total income summary
- Total expense summary
- Remaining balance
- Spending analytics

### 🔍 Search & Filter

- Filter by category
- Filter by date
- Search transactions

### 📱 Responsive Design

- User-friendly interface
- Mobile-friendly design
- Simple navigation

---

## 🏗️ System Architecture

```text
            React.js Frontend

                     ↓

           Spring Boot REST APIs

                     ↓

          Business Logic Layer

                     ↓

              MySQL Database
```

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | React.js, HTML5, CSS3, JavaScript |
| Backend | Java, Spring Boot |
| Database | MySQL |
| API | REST APIs |
| Build Tool | Maven |
| Version Control | Git, GitHub |

---

## 📂 Project Structure

```text
BudgetIQ-finance-manager/

├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   └── application.properties
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── images/
│   ├── dashboard.png
│   ├── expense-management.png
│   ├── analytics.png
│   └── budget-overview.png
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/NVENKATABALAJI/BudgetIQ-finance-manager.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd BudgetIQ-finance-manager
```

---

## 🖥️ Backend Setup

### Configure Database

Open:

```text
src/main/resources/application.properties
```

Update:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/budgetiq

spring.datasource.username=your_username

spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update

spring.jpa.show-sql=true
```

### Run Spring Boot Application

```bash
mvn spring-boot:run
```

Backend Server:

```text
http://localhost:8080
```

---

## 🎨 Frontend Setup

```bash
cd frontend

npm install

npm start
```

Frontend Server:

```text
http://localhost:3000
```

---

## 🎯 Core Functionalities

✅ Expense Tracking

✅ Income Tracking

✅ Budget Management

✅ Financial Dashboard

✅ Transaction History

✅ Search & Filtering

✅ Real-time Balance Monitoring

---

## 🚀 Future Enhancements

- 🔐 User Authentication
- 📄 Export PDF Reports
- 📊 Advanced Charts
- 📧 Email Notifications
- 🎯 Savings Goal Tracker
- 🔁 Recurring Transactions
- ☁️ Cloud Deployment

---

## 📈 Project Outcome

BudgetIQ helps users build better financial habits by providing a centralized platform to track expenses, manage budgets, and analyze spending patterns using real-time insights.

---

## 👨‍💻 Author

**Naga Venkata Balaji Nimmalapudi**

🔗 GitHub: https://github.com/NVENKATABALAJI

🔗 LinkedIn: Add your LinkedIn profile link here.

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
