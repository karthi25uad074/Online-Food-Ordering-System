# Online Food Ordering System

A simple and interactive console-based **Mini Project** built using **Java (JDBC)** and **MySQL Database**. This application allows users to view a live food menu fetched from the database, place orders, and automatically calculates the total bill while storing the transaction details securely in MySQL.

---

## 🚀 Features
* **Live Menu Display:** Fetches real-time food items and prices directly from the MySQL database.
* **Dynamic Ordering System:** Takes customer name, item ID, and quantity via user input.
* **Auto-Billing:** Calculates the total price dynamically based on the quantity ordered.
* **Database Persistence:** Stores successful order details securely into an `orders` table.

---

## 🛠️ Tech Stack & Tools
* **Language:** Java (JDK 26)
* **IDE:** NetBeans
* **Database:** MySQL Command Line Client
* **Connector:** MySQL Connector/J 9.7.0

---

## 🗄️ Database Structure

### 1. Menu Table (`menu`)
Stores the available food items.
| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `item_id` | INT (Primary Key) | Unique ID for the food item |
| `item_name` | VARCHAR(100) | Name of the food |
| `price` | DECIMAL(10,2) | Cost per unit |

### 2. Orders Table (`orders`)
Stores the checkout/order transactions.
| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `order_id` | INT (Primary Key) | Unique ID for each order |
| `customer_name` | VARCHAR(100) | Name of the buyer |
| `item_name` | VARCHAR(100) | Ordered item name |
| `quantity` | INT | Number of plates/items ordered |
| `total_price` | DECIMAL(10,2) | Total calculated bill |

---

## 🔧 How to Run Locally

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/karthi25uad074/Online-Food-Ordering-System.git](https://github.com/karthi25uad074/Online-Food-Ordering-System.git)
