# Food Ordering Web Application

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Database Schema](#database-schema)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the Food Ordering Web Application! This project is a dynamic and stylish web application designed to provide a seamless food ordering experience. It features user authentication, restaurant and menu management, an ordering system, and both user and admin dashboards.

## Features

- **User Authentication**:
  - User registration and login system
  - Secure password storage and validation

- **Restaurant and Menu Management**:
  - Admin panel for adding, editing, and deleting restaurants and their menus
  - Each restaurant includes a list of food items with details such as name, description, price, and image

- **Ordering System**:
  - Users can browse restaurant menus and add items to their cart
  - Users can place orders with multiple items
  - Order confirmation and summary display

- **User Dashboard**:
  - Users can view their order history
  - Order status tracking (e.g., pending, confirmed, delivered)

- **Admin Dashboard**:
  - View and manage all orders
  - Update order status

## Tech Stack

- **Frontend**:
  - HTML5, CSS3 (with Bootstrap)
  - JavaScript (vanilla JavaScript and jQuery)

- **Backend**:
  - PHP 7 or higher (following MVC architecture)
  - MySQL 5.7 or higher

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/food-ordering-app.git
   cd food-ordering-app
   Set up the database:

Import the sql/schema.sql file into your MySQL database.
Update the database configuration in config/config.php.
Install dependencies:

Make sure you have PHP and MySQL installed on your server.
No additional dependencies are required.
Start the application:

Place the project in your web server directory (e.g., htdocs for XAMPP).
Navigate to http://localhost/food-ordering-app/public in your browser.
Database Schema
The database schema includes the following tables:

users: Stores user information.
restaurants: Stores restaurant details.
menu_items: Stores menu items for each restaurant.
orders: Stores order information.
order_items: Stores details of each item in an order.
You can find the detailed schema in the sql/schema.sql file.

Usage
Home Page: Browse featured restaurants and dishes.
Restaurant Page: View restaurant details and menu items, and add items to your cart.
Cart Page: View selected items, update quantities, and proceed to checkout.
Checkout Page: Provide delivery details and place your order.
User Profile Page: View user information and past orders.
Admin Panel: Manage restaurants, menu items, and orders.
Project Structure# Food Ordering Web Application

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Database Schema](#database-schema)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the Food Ordering Web Application! This project is a dynamic and stylish web application designed to provide a seamless food ordering experience. It features user authentication, restaurant and menu management, an ordering system, and both user and admin dashboards.

## Features

- **User Authentication**:
  - User registration and login system
  - Secure password storage and validation

- **Restaurant and Menu Management**:
  - Admin panel for adding, editing, and deleting restaurants and their menus
  - Each restaurant includes a list of food items with details such as name, description, price, and image

- **Ordering System**:
  - Users can browse restaurant menus and add items to their cart
  - Users can place orders with multiple items
  - Order confirmation and summary display

- **User Dashboard**:
  - Users can view their order history
  - Order status tracking (e.g., pending, confirmed, delivered)

- **Admin Dashboard**:
  - View and manage all orders
  - Update order status

## Tech Stack

- **Frontend**:
  - HTML5, CSS3 (with Bootstrap)
  - JavaScript (vanilla JavaScript and jQuery)

- **Backend**:
  - PHP 7 or higher (following MVC architecture)
  - MySQL 5.7 or higher

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/food-ordering-app.git
   cd food-ordering-app
2. **Set up the database**:
   - Import the sql/schema.sql file into your MySQL database.
   - Update the database configuration in config/config.php.
   - 
2. **Install dependencies**:
   - Make sure you have PHP and MySQL installed on your server.
   - No additional dependencies are required.
     
3. **Start the application**:
   - Place the project in your web server directory (e.g., htdocs for XAMPP).
   - Navigate to http://localhost/food-ordering-app/public in your browser.

## Database Schema
   - The database schema includes the following tables:
   - users: Stores user information.
   - restaurants: Stores restaurant details.
   - menu_items: Stores menu items for each restaurant.
   - orders: Stores order information.
   - order_items: Stores details of each item in an order.
   - You can find the detailed schema in the sql/schema.sql file.
## Usage
- Home Page: Browse featured restaurants and dishes.
- Restaurant Page: View restaurant details and menu items, and add items to your cart.
- Cart Page: View selected items, update quantities, and proceed to checkout.
- Checkout Page: Provide delivery details and place your order.
- User Profile Page: View user information and past orders.
- Admin Panel: Manage restaurants, menu items, and orders.

## Project Structure
food-ordering-app/

├── config/

│   └── config.php

├── public/

│   ├── css/

│   │   └── styles.css

│   ├── js/

│   │   └── scripts.js

│   ├── images/

│   ├── index.php

│   ├── login.php

│   ├── register.php

│   ├── restaurant.php

│   ├── cart.php

│   ├── checkout.php

│   └── profile.php

├── admin/

│   ├── dashboard.php

│   ├── manage_restaurants.php

│   ├── manage_menus.php

│   └── manage_orders.php

├── includes/

│   ├── header.php

│   ├── footer.php

│   ├── navbar.php

│   ├── db_connect.php

│   ├── auth.php

│   └── functions.php

├── models/

│   ├── User.php

│   ├── Restaurant.php

│   ├── MenuItem.php

│   └── Order.php

└── sql/

    └── schema.sql
    

## Contributing
We welcome contributions to enhance this project! To contribute:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes.
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature-branch).
- Open a Pull Request.

## License
- This project is licensed under the MIT License. See the LICENSE file for more details.
