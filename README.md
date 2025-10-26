# Bakery-Management-System

## 📘 Overview

This C++ program helps manage a bakery’s inventory and customer orders.
It allows **admins** to add or view bakery items and **customers** to order and get receipts with discounts.

---

## 👨‍💼 Admin Features

* Login (username: `admin`, password: `123`)
* Add new items (cookies or cakes) with names and prices
* Display all available items from `bakery_items.txt`

---

## 🛍️ Customer Features

* View available items
* Select items and quantity to order
* Generate receipt with discounts
* Orders saved in `order.txt`

---

## 💰 Discount Policy

| Total Price | Discount |
| ----------- | -------- |
| > RM100     | 5%       |
| > RM200     | 10%      |

---

## 🗂️ Files Used

* **bakery_items.txt** → Stores item list
* **order.txt** → Stores customer orders

---

## ⚙️ How to Run

1. Make sure `bakery_items.txt` exists with some data.
2. Compile and run:
!g++ main.cpp bakery.cpp bakery.h -o output.a

!./output.a

3. Choose menu: Admin or Customer
4. Follow on-screen instructions

---

## 🧾 Example Output

```
----- RECEIPT -----
Item           Qty   Price(RM)
Cookie Choc    2     6.00
Cake Velvet    1     45.00
-------------------
Subtotal: RM51.00
Discount: 0%
Total: RM51.00
-------------------
Thank you!
```

---

## 🧠 Concepts Used

* Classes and objects
* Inheritance and encapsulation
* File handling
* Basic validation and discounts

---

Would you like me to help make this version into a **clean PDF** for submission?
