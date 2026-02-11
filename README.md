# 🧾 Java - InvoiceApp

**CSC160 – Programming Fundamentals II: Section 1 Assignment**

A console-based Java application that calculates invoice totals, applies conditional discounts, and produces a professionally formatted receipt using `printf`.

---

## 📌 Assignment Overview

The goal of this assignment was to enhance an existing Java application by:

* Adding a tiered discount calculation method
* Conditionally displaying discount and total savings
* Producing a professionally formatted receipt
* Using Java SE 17 features and proper JavaDoc documentation
* Following GitHub best practices with meaningful commits

---

## ▶️ How the Program Works

1. The program greets the user.
2. The user is prompted to enter invoice line items.
3. Each line item includes:

   * Description
   * Quantity
   * Unit price
4. The user chooses whether to add another item.
5. A discount is applied **only when conditions are met**.
6. The receipt displays:

   * Item calculations
   * Discount percentage (if applicable)
   * Total savings (if applicable)
   * Final receipt total
7. Output is formatted using `printf` for precision, alignment, and readability.

⚠ **Important Note:**
Discount-related lines only print when at least one line item qualifies for a discount.

<img width="1710" height="1107" alt="Screenshot 2026-02-01 at 11 33 35" src="https://github.com/user-attachments/assets/601c6442-53bd-49e8-aecf-10ea01d2afb0" />

---

## 💰 Discount Structure

Discounts are automatically applied based on each item’s subtotal (quantity × price):

| Item Subtotal | Discount    |
| ------------- | ----------- |
| $50.00+       | 25%         |
| $40.00–49.99  | 20%         |
| $30.00–39.99  | 15%         |
| $20.00–29.99  | 10%         |
| $10.00–19.99  | 5%          |
| Below $10     | No discount |

---

## 🧾 Sample Output

### ✅ Receipt Example With Discount

```
========================================
Welcome to the Invoice Total Calculator
========================================

Customer Receipt
----------------------------------------
Laptop         1 @ $ 799.99 = $ 799.99
Mouse          2 @ $  25.00 = $  50.00
----------------------------------------
Discount: 25%
Total Savings: $ 200.00
----------------------------------------
Receipt Total: $ 649.99
========================================

Thank you for shopping with us!
```
<img width="1710" height="1107" alt="Screenshot 2026-02-01 at 11 33 44" src="https://github.com/user-attachments/assets/86fc9cb4-5a05-4927-91b8-1889451d4f0d" />

---

### ❌ Receipt Example With NO Discount

```
Customer Receipt
----------------------------------------
apples   10 @ $ 0.75 = $  7.50
oranges   6 @ $ 1.00 = $  6.00
----------------------------------------
Receipt Total: $ 13.50
----------------------------------------

Thank you for shopping with us!
```

---

## 🆕 New Concepts Used

* ✅ Java SE 17 features
* ✅ Working with methods
* ✅ `printf` formatting:

  * Precision control
  * Alignment
  * Percent symbol (`%%`)
* ✅ JavaDoc for:

  * Class-level documentation
  * Newly added methods
* ✅ GitHub version control with meaningful commits

---

## 👤 Author

**Sanyam Sood**
GitHub: 

---

---

## 📄 License

This project is for educational use as part of **CSC160 – Programming Fundamentals II**.

---
