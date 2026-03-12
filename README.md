# 🛒 Shopping Cart with Sequelize

A simple **Shopping Cart web application** built using **Node.js, Express.js, Sequelize ORM, MySQL and EJS**.
This project demonstrates how to build a basic e-commerce cart system with product listing, cart management and database integration.

---

# 📌 Features

* Product listing
* Add products to cart
* Remove products from cart
* Cart quantity management
* MySQL database integration
* MVC-like project structure
* Sequelize ORM for database operations
* EJS templating for frontend views

---

# 🧰 Tech Stack

Backend

* Node.js
* Express.js

Database

* MySQL
* Sequelize ORM

Frontend

* EJS Templates
* HTML
* CSS

Development Tools

* Nodemon

---

# 📂 Project Structure

```
shopping-cart-with-sequelize
│
├── controllers
├── models
├── routes
├── views
├── public
├── util
│
├── app.js
├── package.json
└── package-lock.json
```

---

# ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/SP-9cloud/Shopping-Cart-with-Sequelize.git
```

### 2️⃣ Navigate into the project

```
cd Shopping-Cart-with-Sequelize
```

### 3️⃣ Install dependencies

```
npm install
```

---

# 🗄️ Environment Variables

Create a `.env` file in the root directory and add:

```
DB_USER=your_mysql_username
DB_DATABASE=your_database_name
DB_PWD=your_mysql_password
```

---

# 🛢️ Database Setup

1. Install **MySQL**
2. Create a database

Example:

```
CREATE DATABASE shopping_cart;
```

3. Update your `.env` credentials accordingly.

---

# ▶️ Running the Application

Start the server:

```
npm start
```

or

```
nodemon app.js
```

The application will run on:

```
http://localhost:3000
```
