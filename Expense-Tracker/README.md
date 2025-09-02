# Flask Expense Tracker

A simple expense tracking web application built with **Flask**, **SQLAlchemy**, and **Flask-Admin**.  
This app allows users to register, log in, add, edit, and delete expenses, as well as view a dashboard with expense statistics.

## 🚀 Features
- User authentication (Register, Login, Logout)
- Add, edit, delete expenses
- Dashboard with daily and monthly expense tracking
- Profile page
- Admin panel using Flask-Admin
- SQLite database

## 📂 Project Structure
```
.
├── app.py              # Main Flask application
├── requirements.txt    # Dependencies
├── README.md           # Project documentation
├── templates/          # HTML templates (Jinja2)
│   ├── index.html
│   ├── dashboard.html
│   ├── expenses.html
│   ├── create_expense.html
│   ├── edit_expense.html
│   ├── profile.html
│   └── auth/
│       ├── login.html
│       └── register.html
└── static/             # CSS, JS, and images
```

## ⚙️ Installation

1. Clone this repository or download the source code.
2. Navigate to the project folder.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the app:
   ```bash
   python app.py
   ```

## 🖥️ Usage
- Visit `http://127.0.0.1:5000/` in your browser.
- Register a new account or log in with existing credentials.
- Use the dashboard to track your expenses.

## 🔑 Default Admin
You can manage users and expenses from the **Flask-Admin** panel at `/admin`.

## 🛠️ Technologies Used
- Flask
- Flask-SQLAlchemy
- Flask-Admin
- SQLite
- Jinja2 Templates
- Bootstrap (for styling, optional)

## 📜 License
This project is for educational purposes only. You can modify and use it freely.
