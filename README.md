# 🧮 React Calculator

A clean, responsive calculator built with React and powered by a custom useReducer setup.
This project demonstrates state management, user input handling, formatting logic, and component-based UI design — all wrapped in a sleek, gradient-themed interface.

[🌐 Live Demo](https://netflix-clone-fhwh.onrender.com/)

--- 

## 📸 Screenshot

![React Calculator Screenshot](screenshot.JPG)

---

## 🎯 Features

- 🔢 Fully Functional Calculator — Supports addition, subtraction, multiplication, and division
- 🧮 Accurate Evaluations — Computation handled by a dedicated evaluate() function
- 🧠 Advanced State Management — Built entirely using useReducer()
- 📝 Input Validation — Prevents invalid inputs (multiple decimals, leading zeros, etc.)
- ↩️ Delete Function — Remove last digit
- 🧼 Clear All (AC) — Reset calculator state with a single click
- 🎨 Beautiful UI — Gradient background and clean button layout
- 📱 Responsive Design — Works on both desktop and mobile

---

## 🛠️ Tech Stack

- React 19
- Vite
- useReducer Hook
- CSS3

---

## 🚀 Getting Started

### 1. Clone the Repository

git clone git@github.com:zandernh/react_calculator.git

cd react-calculator

### 2. Install Dependencies

npm install

### 3. Start Development Server

npm run dev

### 4. Access the app at:

http://localhost:5173

---

## 🧠 How It Works

This calculator uses a central reducer to manage all actions:

### 🔹 ACTIONS.ADD_DIGIT
- Adds digits to the current operand
- Prevents invalid input like multiple decimals or leading zeroes

### 🔹 ACTIONS.CHOOSE_OPERATION
- Handles switching between operations
- Moves current operand to previous when appropriate

### 🔹 ACTIONS.DELETE_DIGIT
- Removes the last digit from the current operand
- Handles overwrite mode after evaluation

### 🔹 ACTIONS.EVALUATE
- Calls the evaluate() function to compute results
- Resets state and displays solution

### 🔹 evaluate() Logic
- Converts operands via parseFloat()
- Computes based on selected operation
- Returns a clean string value

### 🔹 Operand Formatting
- Uses Intl.NumberFormat for nicely formatted numbers

---

## 🌐 Deployment

This project is deployed using Netlify.

---

## 📄 License

This project is open-source and released under the MIT License.

---

## 🙋‍♂️ Author

Developed by Zander Harding.
