# 🎓 StudentInfoFormW-database

📍 **Live Demo:** [View App Here](https://luigibarte4563.github.io/StudentInfoFormW-database/index.html)

A responsive web app for submitting, viewing, and managing student enrollment data — built using **HTML**, **CSS**, **JavaScript**, and **Firebase Realtime Database**.

---

## 🔍 Overview

The **StudentInfoFormW-database** project allows students to easily submit their enrollment information (Name, ID, Email, Program) and view a real-time list of all submissions.
It also includes an **admin interface** for verifying and deleting student records directly from the database.

---

## ✨ Features

✅ Submit student enrollment information
✅ Real-time updates using Firebase Realtime Database
✅ Public list of all submitted records
✅ Admin panel for verifying and deleting entries
✅ Hosted with GitHub Pages for instant access

---

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Firebase Realtime Database
* **Hosting:** GitHub Pages
* *(Optional)* Tailwind CSS for modern styling

---

## 🚀 Getting Started

### 📦 Prerequisites

Before you begin, make sure you have:

* A **Google Account**
* Access to [Firebase Console](https://console.firebase.google.com)
* Basic knowledge of HTML and JavaScript

---

### 🧩 Setup Instructions

1. **Clone this repository**

   ```bash
   git clone https://github.com/Luigibarte4563/StudentInfoFormW-database.git
   cd StudentInfoFormW-database
   ```

2. **Create a Firebase project**

   * Go to **Firebase Console → Add Project**
   * Enable **Realtime Database** and set the rules to public for testing:

     ```json
     {
       "rules": {
         ".read": true,
         ".write": true
       }
     }
     ```

3. **Register a Web App**

   * Navigate to **Project Settings → General → Your Apps → Add App (</>)**
   * Copy your Firebase config object, e.g.:

     ```js
     const firebaseConfig = {
       apiKey: "YOUR_API_KEY",
       authDomain: "YOUR_PROJECT.firebaseapp.com",
       databaseURL: "https://YOUR_PROJECT-default-rtdb.firebaseio.com",
       projectId: "YOUR_PROJECT",
       storageBucket: "YOUR_PROJECT.appspot.com",
       messagingSenderId: "YOUR_SENDER_ID",
       appId: "YOUR_APP_ID"
     };
     ```

4. **Add Firebase Config**
   Paste the config object into your `firebase-config.js` file inside the project.

5. **Preview the app locally (optional)**

   * Open `index.html` in your browser, or
   * Use VS Code’s *Live Server* extension to test in real time.

---

## 👩‍💻 Admin Panel

To open the **Admin Dashboard**:

* Go to `/admin.html` or click the *Admin Page* button in the navigation bar.
* Admins can:

  * ✅ **Verify** student records
  * ❌ **Delete** student records
* The submission form is hidden on the admin page to simplify management.

---

## 💡 Future Improvements

* 🔐 Add Firebase Authentication for admin login
* 🔍 Add search and filter features
* 📊 Add pagination for large datasets
* 📱 Improve responsive UI for mobile users

---

## 🧑‍🎓 Author

**Luigi Barte**
📍 [GitHub Profile](https://github.com/Luigibarte4563)
🌐 [Live Project](https://luigibarte4563.github.io/StudentInfoFormW-database/index.html)

