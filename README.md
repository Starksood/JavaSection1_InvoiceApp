# What This Program Does

This is an **Invoice Total Calculator** that helps create itemized receipts with automatic discounts. Here's how it works:

When you run the program, it greets you and then enters a loop where you can add items to your purchase. For each item, you enter three pieces of information: a description (like "Laptop" or "Coffee Mug"), how many you're buying, and the price per item.

After entering each item, the program asks if you want to add another one. You can keep adding items until you're done, at which point you answer "n" (no) to exit the loop.

Once you're finished entering items, the program generates a formatted receipt. It automatically applies tiered discounts based on each item's subtotal (quantity × price). The discount structure is:
- 25% off if the item subtotal is $50 or more
- 20% off for $40-$49.99
- 15% off for $30-$39.99
- 10% off for $20-$29.99
- 5% off for $10-$19.99
- No discount below $10

The receipt shows each item with its calculations, any discounts applied, the total savings across all discounted items, and the final receipt total.

---

# Java Concepts Used

- **Classes and Objects** - The `InvoiceApp` class encapsulates all functionality
- **Data Types** - `int`, `double`, `boolean`, `String`
- **Loops** - `while` loops for input validation and main program flow; `for` loop for iterating through items
- **Conditional Statements** - `if-else if-else` chains for discount calculation and validation
- **Exception Handling** - `try-catch` blocks for input validation
- **Comments/Documentation** - Javadoc-style comments with `@author`, `@version`, `@param`, `@return`
