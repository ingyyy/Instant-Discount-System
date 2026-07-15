# 💰 Instant Discount System

A clean Python CLI application that calculates the final price of a product by applying dynamic, tiered discounts based on the user's purchase value. This project demonstrates foundational programming concepts such as conditional logic (`if-elif-else`), dynamic user input handling, and clean code principles.

---

## 🎯 Project Objectives
* **Conditional Logic:** Implement straightforward conditional statements to route different discount rates.
* **Data Type Casting:** Handle floating-point numbers (`float`) smoothly to support decimal prices.
* **DRY Principle:** Avoid redundant mathematical operations by calculating and storing variables efficiently.

---

## 📊 Discount Logic

The application automatically evaluates the total purchase amount and applies one of the following tiers:

| Purchase Amount (EGP) | Discount Rate |
| :--- | :---: |
| Less than 100 | **0%** |
| From 100 up to (but excluding) 500 | **10%** |
| 500 or more | **20%** |

---

## 🚀 How It Works
1. **Welcome Message:** Greets the user and explains the tool.
2. **Input:** Prompts the user to enter their total purchase amount (accepts decimals, e.g., `150.5`).
3. **Processing:** Evaluates the logic tier, calculates the exact discount value, and subtracts it from the original total.
4. **Output:** Prints the total discount saved and the final amount due in a clean, user-friendly format.

---

## 💻 Sample Output

```text
Hello, this is an 'Instant Discount System'
Please enter the total purchase amount: 250.5

Your available discount value is: 25.05 EGP
The total amount due after discount is: 225.45 EGP
