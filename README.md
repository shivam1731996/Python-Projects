# 🍽️ Python Restaurant Ordering System

## Overview

This is a simple **command-line restaurant ordering system** built using **Python 3**. It simulates a food ordering experience where users can:

- View a menu
- Select food items
- Enter quantities
- Receive a detailed bill with taxes, discounts, and delivery charges

It’s designed as a beginner-friendly Python project demonstrating practical use of data structures, loops, conditionals, and input/output formatting.

---

##  Working

1. The user is greeted and shown the full menu with prices.
2. They can order multiple items by entering the item name and quantity.
3. The program:
   - Validates item availability
   - Adds each item to the order list
4. At checkout, the system calculates:
   - ✅ Subtotal
   - ✅ 5% GST tax
   - ✅ 10% discount if subtotal > ₹200
   - ✅ ₹20 delivery charge if subtotal < ₹150
5. Displays a complete bill summary in a clear, formatted layout.

---

## Technical Details

| Component       | Description                                      |
|----------------|--------------------------------------------------|
| Language        | Python 3.x                                       |
| Menu Storage    | `Dictionary` for item-price mapping              |
| Order Handling  | `List` or `Tuple` to manage ordered items        |
| Loop Control    | `while` loop for continuous ordering             |
| Billing Logic   | `if-else` conditions for tax, discount, delivery |
| UI              | Terminal/CLI (text-based interface)              |

---

##  User Interface (CLI)

- Prompts for menu selection and quantity input
- Validates input and confirms selections
- Shows item-wise pricing and final bill
- Fully interactive via terminal/command prompt

---

## Future Enhancements

- [ ] Edit/remove items before final billing
- [ ] Save order summary to a `.txt` or `.csv` file
- [ ] GUI version using **Tkinter** or **PyQt**
- [ ] Web version using **Flask** or **Django**
- [ ] Integrate mock **payment gateway** functionality

---

##  How to Run

1. Clone this repository or download the `.py` file.
2. Open the script in any Python-supported IDE or terminal.
3. Run the script:

```bash
python restaurant_order.py
