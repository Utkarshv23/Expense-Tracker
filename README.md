# 💰 Expense Tracker

A full-stack web app to track your income and expenses with beautiful analytics. Built with React, Node.js, and MongoDB.

## ✨ Features

- Secure Authentication - Sign up, log in, and keep your data private
- Transaction Management - Add, edit, delete income and expenses
- Smart Analytics - Visual charts showing spending patterns by category
- Time Filtering - View data by week, month, year, or custom dates
- Responsive Design - Works perfectly on all devices

## 🛠 Tech Stack

Frontend: React 18, Ant Design, Redux, React Router  
Backend: Node.js, Express, MongoDB, Mongoose  
Tools: Axios, Moment.js, JWT

## 🚀 Quick Start

1. Clone & Install
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   npm install
   cd client && npm install && cd ..
   ```

2. Setup Environment
   ```bash
   # Create .env file
   echo "MONGODB_URL=your_mongodb_connection_string" > .env
   ```

3. Run the App
   ```bash
   npm run dev
   ```
   Visit http://localhost:3000

## 🎯 How It Works

1. Sign up and create your account
2. Add transactions - income (salary, tips) or expenses (food, bills)
3. View analytics - see your spending patterns with beautiful charts
4. Filter data - analyze specific time periods or transaction types

## 🔌 API Endpoints

- POST /api/v1/users/register - Create account
- POST /api/v1/users/login - Sign in
- POST /api/v1/transactions/add-transaction - Add transaction
- POST /api/v1/transactions/get-transaction - Get filtered transactions
- POST /api/v1/transactions/edit-transaction - Update transaction
- POST /api/v1/transactions/delete-transaction - Delete transaction

## 🗄 Data Models

User: { name, email, password, timestamps }  
Transaction: { userid, amount, type, category, date, reference, description, timestamps }

## 🔧 Key Features

- Real-time Analytics - Progress circles and category breakdowns
- Advanced Filtering - Time-based and type-based filters
- Responsive UI - Mobile-first design with Ant Design components
- State Management - Redux for organized data flow

## 👨‍💻 About

Hi, I'm Utkarsh Vijay, a full-stack web developer passionate about building scalable, user-focused applications. I love combining clean UI with efficient backend logic to create meaningful digital tools.


- GitHub: https://github.com/Utkarshv23
- LinkedIn: https://www.linkedin.com/in/utkarsh-vijay-82269032b/

---
