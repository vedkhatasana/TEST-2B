# 🍽️ Dinner Booking Portfolio

Welcome to the Dinner Booking Form — a clean, simple, and interactive web form that lets users book a dinner reservation by entering their details, picking a time, and choosing meal preferences. It’s built entirely with HTML, CSS, and JavaScript, with smooth validation and feedback – no popups involved.

---

## 👤 Author

**Ved Patel**

---

## ✨ What It Does

This project allows users to:
- Enter their **full name**
- Input a **valid phone number**
- Pick a **dining time**
- Select one or more **meal preferences**
- Get real-time feedback if something is missing or incorrect
- See a clear success message after everything is filled correctly

---

## 🧩 Key Features

### 🔡 Input Fields
- **Full Name**: Must include both first and last name
- **Phone Number**: Must be 6 characters long and start with a number

### 🕐 Time Selection
- Choose your preferred dinner time:  
  `05:00`, `06:00`, `07:00`, or `08:00`

### 🍽️ Meal Preferences
- Select any of the following:
  - Starters
  - Main Course
  - Desserts
  - Drinks

### ✅ Smart Validation
- Real-time checks when fields lose focus (`onBlur`)
- Error messages appear if inputs are invalid
- Submit button works only when all fields are valid
- A friendly success message appears after submission

---

## 🛠️ Tech Used

- **HTML5** – For the structure
- **CSS** (inline styles) – For styling and layout
- **JavaScript** – For all interactivity and form validation

---

## 🚀 How to Use It

1. Open the `index.html` file in your browser.
2. Fill in your **full name** (make sure it includes both first and last).
3. Enter a **6-digit phone number** that starts with a number.
4. Select your **dinner time** from the available options.
5. Choose any **meals** you’d like to include.
6. Once everything looks good, hit **Submit**.
7. You'll see a confirmation message right below the form — no popups!

---

## 🔍 Validation in Detail

### Name:
- Can't be empty
- Must contain at least two words (first and last name)

### Phone:
- Can't be empty
- Must be **exactly 6 characters**
- Must start with a number

---

## ✅ Example Success Message

After a valid submission, you'll see something like this:

