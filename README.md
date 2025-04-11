# 🥤 Vending Machine Web Portal

A full-stack vending machine system built with **Flask**, **MySQL**, **HTML/CSS**, and **JavaScript**, designed to simulate a real-world vending experience — including user authentication, live cart queueing, product browsing, purchase confirmation with animations, and detailed account settings.

---

## 🚀 Features

### 👤 User Module
- User authentication (Sign up, Login, Logout)
- Session-based access
- Personal dashboard

### 🛜️ Product & Cart
- Product browsing with live stock
- Real-time cart queueing system
- Quantity selection with price updates
- Floating mini cart
- Purchase confirmation with success animation

### 📦 Purchase System
- Secure checkout
- Purchase records stored in database
- Out-of-stock handling & validation

### ⚙️ Admin Dashboard
- Add, edit, and delete products
- View all purchases
- Manage inventory

### 🧾 Account Settings
- Personal info update with profile picture
- Change password securely
- Purchase insights & summaries (planned)

---

## 🧠 Tech Stack

| Frontend  | Backend    | Database | Others             |
|-----------|------------|----------|--------------------|
| HTML/CSS  | Flask      | MySQL    | Jinja2 Templating  |
| JavaScript | Flask-WTF |          | Flask-Session      |

---

## 📃 Folder Structure

```
📁 vending-machine-portal/
🗁️ static/
🗁️ templates/
🗋 login.html
🗋 buy.html
🗋 cart.html
🗋 account_settings/
    🗋 personal_info.html
    🗋 change_password.html
    🗋 purchase_insights.html
app.py
requirements.txt
README.md
```

---

## 📸 Screenshots (Recommended to Add)

> Add screenshots or a GIF demo of:
> - Product browsing
> - Cart queueing animation
> - Purchase success screen
> - Account settings with profile picture

---

## 📦 Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/vending-machine-portal.git
cd vending-machine-portal
```

### 2. Set up virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Set up MySQL database
- Import the database schema (provided separately)
- Configure DB credentials in `app.py` or `config.py`

### 5. Run the app
```bash
python app.py
```
Visit: [http://localhost:5000](http://localhost:5000)

---

## 💡 Future Improvements
- Add Stripe/UPI integration
- Enable email notifications for purchase receipts
- Purchase insights with charts
- Make PWA (Progressive Web App) support

---

## 🙌 Acknowledgments
Built with ❤️ by Abhishikth Tom Clements as a part of real-world web development practice and integration with database systems.

---

