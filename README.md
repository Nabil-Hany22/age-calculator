# 🧮 Simple Age Calculator

A basic age calculator built using **HTML**, **CSS**, and **Vanilla JavaScript**. This version calculates **age in years** based on the
user's input (day, month, year).

---

## 🚀 Live Demo

🔗 [View Website](https://nabil-hany22.github.io/age-calculator/)

---

## 📌 Features

- Validates day, month, and year before calculating the age.
- Prevents invalid or impossible dates.
- Highlights invalid inputs with an error style.
- Calculates the user's age **in years**.
- Supports pressing **Enter** to trigger the calculation.

---

## 💻 Project Preview

<p align="center">
  <img src="./preview/age-calculator-preview.png" alt="age calculator project" width="80%">
</p>

---

## 🔍 How It Works

### 1️⃣ Input Validation

Each input (day, month, year) has its own validation function:

- `validateDay()` → Accepts **1--31**
- `validateMonth()` → Accepts **1--12**
- `validateYear()` → Ensures the year is **less than or equal to the
  current year**

If an input is invalid, the field gets an **error border**.

### 2️⃣ Date Checking

The function `isDateValid()` makes sure:

- All inputs are valid
- Error classes are added or removed dynamically
- It returns `true` only if all three inputs are correct

### 3️⃣ Age Calculation

The function `calculateAge(year, month, day)`:

- Creates a `Date` object for **today**
- Creates a `Date` object for the **birth date**
- Calculates the difference in years
- Adjusts the age if the user has not reached their birthday yet

> This version does **not** calculate months or days --- only **full
> years**.

## 🖥️ Project Structure

    project-folder/
    │── index.html
    │── style.css
    └── script.js

## 🚀 How to Use

1.  Enter **day**, **month**, and **year**.
2.  Click the **Calculate** button (or press Enter).
3.  Your **age in years** will appear.

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

---

## 📬 Contact

📧 Email: [nhany474@gmail.com](mailto:nhany474@gmail.com)  
🔗 LinkedIn: [Nabil El-Amrawy](https://www.linkedin.com/in/nabil-el-amrawy/)  
🐦 Twitter: [@Nabil_Hany22](https://x.com/Nabil_Hany22)  
📸 Instagram: [@nabil.hany22](https://www.instagram.com/nabil.hany22/)  
💻 GitHub: [Nabil-Hany22](https://github.com/Nabil-Hany22)
