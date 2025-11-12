🎓 StudentInfoFormW-database

📍 Live Demo: View App Here

A simple web app for submitting and managing student enrollment data — built using HTML, JavaScript, and Firebase Realtime Database.

🔍 Overview

This project enables students to submit their enrollment information (Name, ID, Email, Course, Year) and view a public list of all submitted records in real time.
An admin interface is also provided for verifying or deleting student entries.

✨ Features

✅ Student form submission
✅ Real-time database updates
✅ Public student list view
✅ Admin panel for verification & deletion
✅ Firebase Realtime Database integration

🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Firebase Realtime Database

Hosting: GitHub Pages

(Optional) Tailwind CSS for responsive UI

🚀 Getting Started
📦 Prerequisites

A Google account

Access to Firebase Console

Basic understanding of HTML and JavaScript

🧩 Setup Instructions

Clone the repository

git clone https://github.com/Luigibarte4563/StudentInfoFormW-database.git
cd StudentInfoFormW-database


Create a Firebase project

Go to Firebase Console → Add Project

Enable Realtime Database

Register a Web App

In Project Settings → General → Your Apps, click </> Add app (Web)

Copy your Firebase config object, e.g.:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  databaseURL: "https://YOUR_PROJECT-default-rtdb.firebaseio.com",
  projectId: "YOUR_PROJECT",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};


Paste your Firebase config
Replace the placeholder in your firebase-config.js file with the values from Firebase.

Run locally (optional)
Open index.html in your browser, or use VS Code Live Server to preview the project.

👩‍💻 Admin Panel

To access the admin view:

Open the /admin.html page in your browser.

You can verify or delete student records directly from the table.

The form is hidden on the admin side for a cleaner management view.

📁 Project Structure
StudentInfoFormW-database/
│
├── index.html          # Main page with student form
├── admin.html          # Admin interface
├── firebase-config.js  # Firebase setup file
├── script.js           # Form logic and database functions
├── admin.js            # Admin-specific logic
├── style.css           # Custom styles
└── README.md           # Documentation

💡 Future Improvements

Add authentication for admin users

Include search/filter for the student list

Add pagination for large datasets

🧑‍🎓 Author

Luigi Barte
