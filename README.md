# FinTrackPro 💸

**A personal finance tracker built with the MERN stack.**

FinTrackPro helps users manage their income and expenses, track their balance, and understand their spending through an interactive dashboard.

<img width="1920" height="1755" alt="fullpage_snapshot_localhost_2026-10-21-16-42-37" src="https://github.com/user-attachments/assets/44a93bc5-5c94-4ebb-85be-5425c4797783" />


## ✨ Features

- **Authentication** — User registration, login, logout, and access/refresh token-based authentication.
- **Dashboard Analytics** — Track current balance, total income, expenses, and total transactions.
- **Transaction Management** — Create, view, edit, and delete transactions.
- **Search & Filtering** — Search transactions and filter them by category or transaction type.
- **Cash Flow Analysis** — Visualize income and expenses using charts.
- **Category-wise Spending** — Analyze expenses across different categories.
- **Profile Settings** — Update your name and preferred currency.
- **Responsive UI** — Clean interface built with React and Tailwind CSS.

## 🛠️ Tech Stack

**Frontend**
- React.js
- React Router
- Tailwind CSS
- Lucide React
- React Hook Form
- Axios
- Chart.js
- react-chartjs-2

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt
- Cookie-based refresh tokens
- Express Validator

## ⚙️ Getting Started

### Prerequisites

- Node.js and npm
- MongoDB database
- Git

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd FinTrackPro
```

### 2. Set up the backend

```bash
cd server
npm install
```

Create a `.env` file in the backend directory:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_ACCESS_SECRET=your_access_token_secret
JWT_REFRESH_SECRET=your_refresh_token_secret
NODE_ENV=development
```

Use the environment variable names expected by your actual backend code. Never commit real secrets or database credentials.

Start the backend:

```bash
npm run dev
```

### 3. Set up the frontend

Open a new terminal:

```bash
cd client
npm install
npm run dev
```

Open the local URL displayed by Vite in your terminal.

## 📊 Dashboard

The dashboard provides an overview of your finances, including:

- Current balance
- Total income
- Total expenses
- Number of transactions
- Income vs. expense analysis
- Spending breakdown by category
- Recent transaction history

## 🔐 Authentication

FinTrackPro uses access and refresh tokens to manage authenticated sessions. The access token is used for protected API requests, while the refresh token is stored in an HTTP-only cookie to support session renewal.

Protected routes restrict access to authenticated users, and transactions are associated with their respective users.

## 💱 Currency Preferences

Users can choose their preferred currency symbol:

- ₹ — Indian Rupee
- $ — US Dollar
- € — Euro
- £ — British Pound
- ¥ — Japanese Yen

## 🚀 Future Improvements

- Monthly budgets and spending limits
- Recurring transactions
- Export transactions to CSV
- Monthly financial reports
- Improved analytics and spending insights

## 👨‍💻 Author

**Rudresh Shukla**

Computer Science student focused on full-stack development and building practical web applications.

---

*FinTrackPro — Take control of your finances, one transaction at a time.*
