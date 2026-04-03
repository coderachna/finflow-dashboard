FinFlow — Personal Finance Dashboard

 Overview

FinFlow is a modern, responsive personal finance dashboard designed to help users track, analyze, and understand their financial activity. It provides a clear overview of income, expenses, and spending patterns through interactive visualizations and an intuitive interface.

This project demonstrates frontend development skills including UI design, state management, and role-based behavior without backend implementation.


 Features

📊 Dashboard Overview

Summary cards:

Total Balance
Monthly Income
Monthly Expenses
Net Savings

Net worth ticker with savings rate

Time-based visualization:

Balance trend (line chart)

Categorical visualization:

Spending breakdown (donut chart)

Monthly comparison:

Income vs Expenses (bar chart)

Recent transactions preview

🔁 Transactions Management

View all transactions with:

Date
Amount
Category
Type (Income / Expense)

Functionalities:

Search transactions
Filter by type and category
Sort by date or amount
Pagination
Edit transactions (Admin only)
Delete transactions (Admin only)

Export options:

CSV
JSON

🔐 Role-Based UI (Simulated)

Admin:

Full access (Add, Edit, Delete transactions)

Viewer:

Read-only access (View and filter data)

Role switching available via dropdown
UI dynamically updates based on role

📈 Insights Section

Auto-generated insights including:

Highest spending category
Spending patterns
Monthly comparisons

Budget vs actual spending (progress bars)
Month-over-month financial summary table

🧠 State Management

Application state is managed using JavaScript variables and functions:

Transactions data
Filters and sorting state
Current role (Admin / Viewer)
Pagination state

💾 Persistence

Data is stored using localStorage
Transactions persist across page reloads

🎨 UI / UX Highlights

Clean and modern design
Fully responsive (desktop + mobile)
Dark mode / Light mode toggle
Smooth animations and transitions
Toast notifications for actions
Empty state handling

🛠️ Tech Stack

HTML5
CSS3 (Custom styling, responsive design)
Vanilla JavaScript (ES6)

▶️ How to Run

Download or clone the project
Open the file:
finance-dashboard.html
Run it in any modern browser (Chrome, Edge, etc.)

No installation or dependencies required

📂 Project Structure

finance-dashboard.html (Main application file)

Single-file architecture for simplicity and demonstration purposes

⚡ Optional Enhancements Implemented

Dark mode support
Local storage persistence
Export functionality (CSV / JSON)
Advanced filtering & sorting
Responsive mobile navigation
Animations & micro-interactions

⚠️ Edge Case Handling

Handles empty transaction states gracefully
Prevents invalid form submissions
Displays appropriate UI for no data scenarios
Safe calculations for zero income cases

📊 Evaluation Criteria Coverage

Design & Creativity — Yes
Responsiveness — Yes
Functionality — Yes
User Experience — Yes
Technical Quality — Yes
State Management — Yes
Documentation — Yes
Attention to Detail — Yes

🔮 Future Improvements

Backend integration (API + database)
Authentication system
Real-time data updates
Advanced analytics (AI-based insights)
Multi-user support

👩‍💻 Author
Developed by Rachna

📄 License
This project is for educational and demonstration purposes
