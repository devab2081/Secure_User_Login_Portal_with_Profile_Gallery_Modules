# 🌐 PHP User Authentication & Mini Social App

This is a simple **PHP-based user system** that includes user registration, login, logout, profile viewing, gallery display, and comment retrieval.  
It is designed as a beginner-friendly PHP project to understand **sessions, authentication, forms, and basic UI handling**.

---

## 🚀 Features

### 🔐 **User Authentication**
- User Registration (Sign Up)
- Login using username/email + password
- Logout using session destroy
- Form validation & error handling

### 👤 **User Profile Management**
- Profile page for logged-in users
- Stores user details like Name, Email, Location

### 🖼️ **Gallery Module**
- View gallery images
- Backend file: `gallery.php`

### 💬 **Comments Fetcher**
- Loads comments dynamically
- Backend endpoint: `get_comments.php`

### 🎉 **Welcome Dashboard**
- Simple dashboard (welcome page) after login

---

## 📂 Project Structure

```
/Weather_Forecasting-project (your folder name)
│── index.html               # Homepage
│── register.php             # Sign-up form (UI + validation)
│── login.php                # Login form + handling
│── logout.php               # Ends user session
│── profile.php              # Shows user profile
│── gallery.php              # Displays gallery items
│── get_comments.php         # Returns comments (backend)
│── welcome.php              # Logged-in homepage
│── assets/ (optional)       # CSS, images, icons
└── README.md                # Documentation
```

---

## 🛠️ Technologies Used

- **PHP** (Core backend logic)
- **HTML / CSS** (Frontend UI)
- **Sessions** (Authentication)
- **MySQL** (If database is used – optional)
- **AJAX / JSON** (For comments fetching)

---

## 📝 Registration Form UI (From `register.php`)

This page includes:
- Username  
- Email  
- Password + Confirm Password  
- Location  
- Validation messages  

Snippet from the UI:  
```html
<form action="register.php" method="post">
  <label>Username</label>
  <input type="text" name="username">
  <label>Email</label>
  <input type="email" name="email">
  <label>Password</label>
  <input type="password" name="password">
  <label>Location</label>
  <input type="text" name="location">
</form>
```  
(Source: register.php) :contentReference[oaicite:1]{index=1}

---

## ▶️ How to Run This Project (Localhost)

### 1️⃣ Install XAMPP / WAMP / MAMP  
XAMPP recommended.

### 2️⃣ Move project folder into:
```
htdocs/
```

Example:
```
C:/xampp/htdocs/Weather_Forecasting-project/
```

### 3️⃣ Start Apache server  
Open XAMPP → Start **Apache**

### 4️⃣ Run in browser:
```
http://localhost/Weather_Forecasting-project/
```

---

## 🧪 How It Works

### ✔ Registration (`register.php`)
- User fills form  
- Validation happens  
- User stored in DB (if configured)

### ✔ Login (`login.php`)
- Checks username/email + password  
- Creates `$_SESSION` values  

### ✔ Profile (`profile.php`)
- Shows user information

### ✔ Gallery (`gallery.php`)
- Displays image list

### ✔ Comments (`get_comments.php`)
- Returns comments using JSON  

---

## 📌 Future Enhancements

- Add password hashing  
- Add profile picture upload  
- Add edit profile option  
- Add Create Post (upload image)  
- Add Like/Comment system  

---

## 👨‍💻 Author

**Devadharshan B**  
Cybersecurity | PHP | Web Development Enthusiast  

⭐ If you find this project useful, please give it a **GitHub star!**

