# StudentInfoFormW‑database  
A web app for submitting and viewing student enrollment data, backed by a Firebase Realtime Database.  

---

## 🔍 Overview  
This project allows students (or users) to submit their information (name, student ID, email, major) via a web form, and view a publicly accessible list of all submissions in real time. An **admin interface** is also provided to verify or delete entries.

### Key features  
- Submission form for student enrollment  
- Public list of enrolled students, updated in real time  
- Admin interface: view all entries, verify students, and delete records  
- Built with HTML, JavaScript + Firebase SDK for front‑end; uses Firebase Realtime Database as the backend  

---

## 🛠️ Technologies  
- HTML & CSS (vanilla)  
- JavaScript (Firebase Web SDK)  
- Firebase Realtime Database  
- (Optional) Tailwind CSS or custom CSS for styling  

---

## 🚀 Getting Started  

### Prerequisites  
- A Google Firebase account  
- A Firebase Project with a Realtime Database instance  

### Setup Steps  
1. Create (or open) a Firebase project in the Firebase Console.  
2. In the project settings, register a web app and copy the Firebase config object, e.g.:  
   ```js
   const firebaseConfig = {
     apiKey: "...",
     authDomain: "YOUR‑PROJECT.firebaseapp.com",
     databaseURL: "https://YOUR‑PROJECT‑default‑rtdb.firebaseio.com",
     projectId: "YOUR‑PROJECT",
     storageBucket: "YOUR‑PROJECT.appspot.com",
     messagingSenderId: "...",
     appId: "..."
   };
