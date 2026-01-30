#  PHP User Authentication & Mini Social Web App

A simple and beginner-friendly **PHP Web Application** that includes:

 User Registration  
 Login / Logout System  
 Profile Page  
 Gallery Page  
 Comment Fetching API  
 Welcome Dashboard  

This project is designed to help beginners understand **forms, sessions, authentication, and PHP backend logic**.

---

##  Features

###  **Authentication System**
- Signup with validation (username, email, password, location)
- Login using username/email + password
- Redirects to dashboard after login
- Error handling for all input fields
- Secure PHP sessions

---

###  **User Profile**
- Displays user information  
- Shows username, email, and location  
- Accessible only after login  

---

###  **Gallery Page**
- Displays gallery items (can be extended)
- Static or dynamic image loading support  

---

###  **Comment Fetching (API Style)**
- `get_comments.php` returns comments in **JSON format**
- Helps beginners understand API-like responses

---

###  **Welcome Dashboard**
- A simple landing page after login  
- Ensures user is authenticated  

---

##  Folder Structure

```
Weather_Forecasting-project/
│── index.html           # Homepage
│── register.php         # Sign-up Page (form + validations)
│── login.php            # Login system
│── logout.php           # Logout and session destroy
│── profile.php          # User profile page
│── gallery.php          # Gallery items
│── get_comments.php     # Comment API (JSON)
│── welcome.php          # Dashboard after login
│── assets/              # Styles, icons, images (optional)
└── README.md
```

---

##  Registration Form UI (From `register.php`)

Your registration page includes fields:

- Username  
- Email  
- Password & Confirm Password  
- Location (City, Country)  

Example snippet:

```html
<form action="register.php" method="post">
    <label>Username</label>
    <input type="text" name="username">

    <label>Email</label>
    <input type="email" name="email">

    <label>Password</label>
    <input type="password" name="password">

    <label>Confirm Password</label>
    <input type="password" name="confirm_password">

    <label>Location</label>
    <input type="text" name="location">

    <input type="submit" value="Submit">
</form>
```

---

##  How to Run This Project

### 1️ Install XAMPP / WAMP  
XAMPP recommended.

### 2️ Move the project folder to:

```
C:/xampp/htdocs/
```

### 3️ Start Apache  
Open XAMPP → Start **Apache**

### 4️ Open in browser:
```
http://localhost/Weather_Forecasting-project/
```

---

##  How the System Works

###  `register.php`
- Validates user input  
- Stores user details in database (if configured)  
- Shows error messages inside form  

###  `login.php`
- Validates login credentials  
- Creates a session  
- Redirects to `welcome.php`  

###  `welcome.php`
- Only logged-in users can access it  

###  `profile.php`
- Shows user info stored during registration  

###  `gallery.php`
- Displays gallery items (images or text)  

###  `get_comments.php`
- Returns comments in JSON format  
- Can be used with AJAX / Fetch API  

---

##  Future Enhancements (Good for College Project)

- Add password hashing (`password_hash()`)
- Add profile picture upload  
- Add image upload for gallery  
- Add Edit Profile page  
- Add real AJAX comment system  
- Convert UI to Bootstrap for cleaner design  

---

##  Author

**Devadharshan B**  
Web Dev | Cybersecurity | PHP Learner  

⭐ *If this project helped you, please give it a star!*

