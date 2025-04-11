
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


## 📸 Screenshots 

> Add screenshots or a GIF demo of:
> - Product browsing
> - ![Screenshot 2025-04-11 at 4 01 05 PM](https://github.com/user-attachments/assets/7752c08c-6c63-4789-b337-70db195da27c)

> - Cart queueing animation
> - ![Screenshot 2025-04-11 at 4 01 34 PM](https://github.com/user-attachments/assets/9cdd97a1-37e8-4a84-b1bf-21b5552df4ce)

> - Purchase success screen
> - ![Screenshot 2025-04-11 at 4 02 05 PM](https://github.com/user-attachments/assets/8870cd9a-edf2-4520-85f7-fd5f374bcc56)


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

