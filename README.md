
# 📘 Facebook GUI Clone in Python (Tkinter)

This project is a **Facebook-style graphical user interface (GUI)** desktop application built using **Python and Tkinter**. It simulates basic functionalities such as **user registration (signup), login, profile display, and password recovery** in a clean and beginner-friendly interface.

---

## 🎯 Project Objective

To help beginners understand GUI development using **Tkinter**, event handling, widget layout management, form validation, and modular code structure through a real-world styled application.

---

## 🧰 Tech Stack

- **Python 3.12+**
- **Tkinter** – for GUI interface
- **PIL (Pillow)** – optional, for image processing (if used)
- **OS / Filesystem** – for reading/writing user data locally (if applicable)

---


---

## 🚀 Features & Functionalities

### 1. 🧍 Signup System
- Collects user information:
  - First name, Last name
  - Email address
  - Mobile number
  - Password and password confirmation
  - Gender selection
  - Date of birth (using combo boxes)
- Performs field validation
- Displays error messages on missing/invalid input
- On success, stores user credentials locally (likely using file I/O or in-memory storage)

### 2. 🔐 Login System
- Accepts email/username and password
- Verifies credentials with saved user data
- On successful login, displays a welcome/profile screen
- Invalid login attempts are handled with proper messages

### 3. 🔄 Forgot Password
- Users can recover password by providing their registered email or username
- If found, the password is revealed or reset (depending on implementation)

### 4. 👤 Profile Page / Welcome Screen
- Shows:
  - User’s full name
  - Welcome message
  - Possibly other details (DOB, gender, etc.)
- Option to log out and return to the login screen

### 5. 🧹 Form Reset Options
- All forms (login, signup, recovery) have reset buttons to clear fields

### 6. 🎨 GUI Styling
- Uses `ttk` and `tkinter` widgets
- Custom fonts, colors, and layout (grid/pack/place)
- Structured window switching (e.g., signup ➜ login ➜ profile)

---

## 💻 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Facebook_Tkinter_Python.git
cd Facebook_Tkinter_Python
```

### 2. Run the Application

```bash
python Facebook.py
```

Make sure you're using **Python 3.12+**.

---


## 📌 Notes

- This is a beginner-level project, and **no real database** is used.
- User data is likely **stored in excel files sheets**, whcih was unique and diffefrent expeirence.
- You can easily **extend** the app with:
  - SQLite or Firebase for backend
  - Profile pictures using `PIL`
  - Session handling and role management

---





