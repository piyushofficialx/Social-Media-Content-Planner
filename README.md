# **Social Media Content Planner — Premium SaaS Web App**

A minimal, premium, modern Social Media Planner built using **HTML**, **TailwindCSS**, **JavaScript**, and **Firebase**.  
Manage your content, schedule posts, generate ideas with AI tools, track analytics, store data in cloud, and access your planner anywhere.

---

### **📌 Overview**
This project is a fully working SaaS-style platform for creators and social media managers.  
It includes a complete authentication system, content planning dashboard, calendar scheduling, AI helper tools, and cloud backup.

---

### **⭐ Key Features**

#### **✔ Authentication System**
- Email & Password Login  
- Google Login (optional)  
- Password Reset  
- Automatic User Session  
- All data saved per user in Firestore  

---

### **✔ Content Planner**
- Create posts with title, caption, tags, platform, and schedule  
- Upload images (Firebase Storage)  
- Color labels for organizing  
- Duplicate posts  
- Autosave  
- Drag & drop sorting  

---

### **✔ Calendar View**
- Monthly calendar  
- View all scheduled posts  
- Drag posts to new dates  
- Quick-add popup  
- Color-coded information  

---

### **✔ Saved Library**
- Save generated captions  
- Save hooks and templates  
- Filter by platform  
- One-click copy to clipboard  

---

### **✔ AI Tool Suite (Placeholder)**
- Caption Generator  
- Hook Generator  
- Hashtag Generator  
- SEO Title Generator  
- Caption Rewriter  
- Keyword Extractor  

Each generated card includes:
- **Copy button**  
- **Save button**  

---

### **✔ Analytics Dashboard**
- Total posts created  
- Completed posts  
- Platform-based stats  
- Monthly posting trend  
- Charts (Chart.js or custom SVG)  

---

### **✔ Settings**
- Change username  
- Change profile photo  
- Theme: Dark / Light mode  
- Export data as JSON  
- Import backup JSON  
- Delete account  
- Full UI sync with theme  

---

### **🎨 UI & Design**
- Minimal and premium style  
- Black/white aesthetic  
- Rounded corners  
- Soft shadows  
- Clean typography  
- Smooth animations  
- Fully responsive  
- Dashboard-style layout with sidebar  

---

### **🛠 Tech Stack**
- **HTML**  
- **TailwindCSS**  
- **JavaScript**  
- **Firebase Auth**  
- **Firebase Firestore**  
- **Firebase Storage**  
- **Chart.js** (optional)  

---

### **📂 Project Structure**
```
root/
│── index.html
│── dashboard.html
│── planner.html
│── calendar.html
│── library.html
│── analytics.html
│── settings.html
│── auth/
│   ├── login.html
│   ├── signup.html
│   └── reset.html
│── assets/
│   ├── css/
│   ├── js/
│   ├── icons/
│   └── images/
│── firebase/
│   ├── config.js
│   └── auth.js
│── backup/
│   └── example.json
```

---

### **💾 Installation**

#### **1. Clone the Repository**
```
git clone https://github.com/your-username/social-media-planner.git
cd social-media-planner
```

#### **2. Set Up Firebase**
Inside `firebase/config.js`:

```js
const firebaseConfig = {
  apiKey: "",
  authDomain: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
  appId: ""
};
firebase.initializeApp(firebaseConfig);
```

#### **3. Run the App**
You can open `.html` files directly  
or run a local dev server:

```
npx serve
```  
or  
```
live-server
```

---

### **🚀 Future Updates**
- Real AI integration (OpenAI/Gemini API)  
- Auto-posting system  
- Team collaboration  
- Notification reminders  
- Mobile app version  

---

### **🤝 Contributing**
Pull requests are welcome!  
Open an issue for bugs or feature requests.

---

### **📄 License**
MIT License — free to use.

---

### **👑 Author**
**Piyush · Accurex Studio**  
Designed with precision, delivered with purpose.  
© 2025 — All rights reserved.
