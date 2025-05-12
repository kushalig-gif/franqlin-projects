#  E-Commerce Website Frontend

A simple e-commerce website (frontend only) built using **HTML, CSS, and JavaScript**. The website includes:

##  Project Overview

This project provides a **basic user interface (UI)** for an e-commerce website with three essential pages:

* **Home Page** – Welcomes users and provides navigation.
* **Login Page** – Allows existing users to log in.
* **Registration Page** – Lets new users sign up.
---

##  Project Structure

```
/e-commerce-ui
├── index.html         # Home Page
├── login.html         # Login Page
├── register.html      # Registration Page
├── styles.css         # CSS Styles
└── script.js          # JavaScript for validation
```

---

##  Home Page (`index.html`)

### **Purpose:**

Greets users and directs them to either the login or registration page.

### **Features:**

* Welcome message
* Two buttons:

  *  **Login** – Redirects to `login.html`
  *  **Register** – Redirects to `register.html`

---

##  Login Page (`login.html`)

### **Purpose:**

Allows existing users to log in.

### **Input Fields:**

* **Email/Username**
* **Password**

### **Validation:**

* Fields must not be empty
* Valid email format (if email is used)
* Alerts for:

  * Successful login
  * Errors (e.g., invalid input)

---

## Registration Page (`register.html`)

### **Purpose:**

Allows new users to register.

### **Input Fields:**

* Full Name
* Email
* Password
* Address
* Phone Number
* Date of Birth (DOB)
* Gender (Radio Buttons)
* State (Dropdown)

### **Validation Rules:**

* All fields are **required**
* **Email** must be valid
* **Password** must:

  * Be **at least 8 characters** long
  * Include **one uppercase** letter
  * Include **one number**
  * Include **one special character** (e.g., `@`, `#`, `$`)
* Real-time feedback on form inputs
* Alerts on success or inline error messages for correction

---

## 🛠 Technologies Used

| Technology | Purpose                         |
| ---------- | ------------------------------- |
| HTML5      | Page structure                  |
| CSS3       | Styling and responsiveness      |
| JavaScript | Form validation and interaction |

---

##  Validation Features

###  Login Page

* Checks for **empty fields**
* Validates **email format**

### Registration Page

* All fields are **mandatory**
* Valid **email address**
* Password must meet **complexity rules**:

  * Minimum **8 characters**
  * At least **1 uppercase** letter
  * At least **1 number**
  * At least **1 special character**
* Real-time error feedback for better UX

---

##  How to Run the Project

1. **Clone or Download the Repository:**

   ```bash
   git clone <repository-url>
   ```

2. **Open the project folder in your browser:**

   * Start with `index.html`
   * Navigate between pages using the buttons/links.

3. **Try it Out:**

   * Click **Register** and fill the form.
   * Then go to **Login** and use the same credentials.


