# 🛒 Online Shopping Discount Calculator

## 📌 Description
This is a simple Python program that calculates the final amount of an online shopping purchase based on the shopping amount and Premium Membership status. The program uses `if-elif-else` statements to calculate the regular discount and a nested `if` statement to provide an additional discount to Premium Members.

---

## ✨ Features
* 🛍️ Takes the total shopping amount from the user.
* 👑 Checks whether the customer is a Premium Member.
* 💰 Calculates the regular discount using conditional statements.
* 🎁 Provides an additional 5% discount to Premium Members.
* 🧮 Calculates the total discount and final amount to pay.

---

## 💸 Discount Rules

| Shopping Amount | Regular Discount Rate |
| :--- | :--- |
| **Rs. 10,000 or above** | 20% Discount |
| **Rs. 5,000 – Rs. 9,999** | 10% Discount |
| **Rs. 2,000 – Rs. 4,999** | 5% Discount |
| **Below Rs. 2,000** | No Discount |

* **👑 Premium Member Benefit:** Premium Members receive an **additional 5% discount** on top of their regular discount.

---

## 🛠️ Technologies Used
* Python 3
* `if-elif-else` & Nested `if` Statements
* User Input Handling (`input()`, `float()`)
* Basic Arithmetic Operations

---

## ▶️ How It Works
1. The user enters the total shopping amount.
2. The program asks whether the customer is a Premium Member (`Yes/No`).
3. The regular discount is calculated according to the shopping amount tier.
4. If the customer is a Premium Member, an additional 5% discount is applied.
5. The total discount and final amount to pay are calculated and displayed.

## 📝 Example

**Console Output:**
```text
Enter total shopping amount: Rs. 12000
Are you a Premium Member? (Yes/No): Yes

----- Shopping Bill -----
Original Shopping Amount: Rs. 12000.0
Regular Discount: Rs. 2400.0
Premium Discount: Rs. 600.0
Total Discount: Rs. 3000.0
Final Amount to Pay: Rs. 9000.0

---

