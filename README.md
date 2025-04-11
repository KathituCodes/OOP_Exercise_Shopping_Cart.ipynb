

# 🛒 Object Oriented Shopping Cart - Lab

Welcome to the **Object Oriented Shopping Cart Lab**! This project is designed to help you strengthen your Python object-oriented programming (OOP) skills by simulating the functionality of a basic shopping cart.

## 📚 Introduction

In this lab, you’ll build and modify a simple Python-based shopping cart system. You’ll use object-oriented programming principles to define a `ShoppingCart` class capable of:

- Adding items with specific quantities and prices  
- Calculating discounts  
- Keeping track of cart contents  
- Voiding the most recent transaction  

This hands-on lab will help reinforce core OOP concepts like instance methods, attributes, and class structure, while building a fun and practical use case.

---

## 🎯 Objectives

By the end of this lab, you will be able to:

- Define and call instance methods  
- Define and access instance attributes  
- Call instance methods inside other instance methods  
- Create methods that compute statistics from object attributes  
- Model a real-world scenario using OOP principles  

---

## 🛠️ Instructions

The main logic of the shopping cart lives in the `shopping_cart.py` file. Your tasks are to implement and modify this file to complete the functionality described in the lab.

### To Get Started:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/object-oriented-shopping-cart-lab.git
   cd object-oriented-shopping-cart-lab
   ```
2. Open the lab in your code editor or Jupyter Notebook.

3. Be sure to enable **autoreload** in Jupyter so updates in `shopping_cart.py` reflect without restarting the kernel:
   ```python
   %load_ext autoreload
   %autoreload 2
   ```

4. Import your `ShoppingCart` class and initialize it:
   ```python
   from shopping_cart import ShoppingCart

   cart = ShoppingCart()
   ```

5. Start implementing features like:
   - `add_item()`
   - `apply_discount()`
   - `void_last_transaction()`

---

## 📁 Project Structure

```
object-oriented-shopping-cart-lab/
│
├── shopping_cart.py       # Your main class definition goes here
├── test_shopping_cart.py  # Optional: Add test cases for your class here
└── README.md              # This file
```

---

## ✅ Example Features to Implement

- **Add Item**: `add_item(title, price, quantity=1)`
- **Apply Discount**: `apply_discount()`
- **Void Last Transaction**: `void_last_transaction()`

---

## 🧪 Example Usage

```python
cart = ShoppingCart()
cart.add_item("Apple", 0.99, 3)
cart.add_item("Banana", 0.50, 2)
cart.apply_discount()
cart.void_last_transaction()
```

---

## 🧠 Learning Outcome

By the end of this lab, you’ll have a stronger grasp of OOP fundamentals, understand how to build class-based logic, and feel more confident working with real-world simulations in Python.

---

## 📌 Notes

- Be sure to test your methods as you go.
- Practice writing clean, reusable code.
- Think of how this simple class could scale into a larger e-commerce application.

---

## 👨‍💻 Author

**Urbanus Peter Kathitu**  
Instructor @ GOMYCODE | Data Scientist | AI/ML Enthusiast

---

