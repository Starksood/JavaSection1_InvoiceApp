# What This Program Does

This is an **Invoice Total Calculator** that helps create itemized receipts with automatic discounts. Here's how it works:

When you run the program, it greets you and then enters a loop where you can add items to your purchase. For each item, you enter three pieces of information: a description (like "Laptop" or "Coffee Mug"), how many you're buying, and the price per item.

After entering each item, the program asks if you want to add another one. You can keep adding items until you're done, at which point you answer "n" (no) to exit the loop.
<img width="1710" height="1107" alt="Screenshot 2026-02-01 at 11 33 35" src="https://github.com/user-attachments/assets/6a93f0ec-0992-43f5-9428-2cc500c59bb1" />


Once you're finished entering items, the program generates a formatted receipt. It automatically applies tiered discounts based on each item's subtotal (quantity × price). The discount structure is:
- 25% off if the item subtotal is $50 or more
- 20% off for $40-$49.99
- 15% off for $30-$39.99
- 10% off for $20-$29.99
- 5% off for $10-$19.99
- No discount below $10

The receipt shows each item with its calculations, any discounts applied, the total savings across all discounted items, and the final receipt total.
<img width="1710" height="1107" alt="Screenshot 2026-02-01 at 11 33 44" src="https://github.com/user-attachments/assets/73c6fe06-e59a-4157-93c3-29af1af150f7" />


---

# Java Concepts Used

- **Classes and Objects** - The `InvoiceApp` class encapsulates all functionality
- **Data Types** - `int`, `double`, `boolean`, `String`
- **Loops** - `while` loops for input validation and main program flow; `for` loop for iterating through items
- **Conditional Statements** - `if-else if-else` chains for discount calculation and validation
- **Exception Handling** - `try-catch` blocks for input validation
- **Comments/Documentation** - Javadoc-style comments with `@author`, `@version`, `@param`, `@return`
