# 🎓 ScholarSpot

A modern, cloud-based platform designed to connect **students, professors, and administrators** — enabling seamless collaboration, resource sharing, and communication within academic institutions.

🌐 **Live Demo:** [https://ssprototype.web.app/](https://ssprototype.web.app/)

💻 **GitHub Repository:** [https://github.com/VishnuV2309/ScholarSpot](https://github.com/VishnuV2309/ScholarSpot)

---

## 👥 Team Details

**Team Name:** Mind_Mesh
**Institution:** REVA University, Bangalore

| Role      | Name          | Email                                                               |
| --------- | ------------- | ------------------------------------------------------------------- |
| Developer | **Vishnu V**  | [vishnuv2309@gmail.com](mailto:vishnuv2309@gmail.com)               |
| Developer | **Amrutha D** | [amruthadandigimath@gmail.com](mailto:amruthadandigimath@gmail.com) |

---## 👥 Team Details


## 🚀 Overview

**ScholarSpot** is a dynamic academic management and collaboration platform that integrates communication, course material sharing, and administration in one digital ecosystem.
It simplifies academic workflows, strengthens student-teacher connections, and promotes a smart learning environment.

Currently, the platform hosts resources for **1st and 2nd semesters of REVA University**, including materials, announcements, and chat functionality.

⚠️ **Important Notice:**
The live demo will remain functional **only for a few days** due to **Uploadcare database and storage charges**.
After this period, file uploads and certain dynamic features may stop working.
However, users can still **visit and explore the live website** to experience the interface and features.

---

## 🧩 Features

✅ **Multi-role Access** – Separate dashboards for Student, Professor, and Admin
✅ **Secure Authentication** – Powered by Firebase Authentication
✅ **Realtime Chat System** – Instant communication between users
✅ **Upload & Share** – File management powered by **Uploadcare**
✅ **Firestore Integration** – Real-time database for user data and content
✅ **Announcements & Resources** – Professors can post and manage materials
✅ **Admin Panel** – Manage users, permissions, and monitor platform usage
✅ **Single Page Application (SPA)** – Smooth and dynamic navigation
✅ **Fully Responsive** – Works across all devices

---

## 🖥️ Live Demo

🎯 **Production Site:** [https://ssprototype.web.app/](https://ssprototype.web.app/)

💻 **GitHub Repository:** [https://github.com/VishnuV2309/ScholarSpot](https://github.com/VishnuV2309/ScholarSpot)

---



## 🔑 Demo Login Credentials

| Role            | Name         | Email                                                 | Password |
| --------------- | ------------ | ----------------------------------------------------- | -------- |
| 🧑‍🎓 Student   | Vishnu V     | [vishnuv2309@gmail.com](mailto:vishnuv2309@gmail.com) | `123456` |
| 👨‍🏫 Professor | Keshav Reddy | [vishnuv0656@gmail.com](mailto:vishnuv0656@gmail.com) | `123456` |
| 👨‍🏫 Professor | Shiva Ram    | [vishnuv9697@gmail.com](mailto:vishnuv9697@gmail.com) | `123456` |
| 🛠️ Admin       | GVS Vishnu V | [gvs.vishnuv@gmail.com](mailto:gvs.vishnuv@gmail.com) | `123456` |

---

## ⚙️ Tech Stack

**Frontend:**

* HTML5, CSS3, JavaScript
* Firebase SDK
* Uploadcare API

**Backend / Services:**

* Firebase Authentication
* Firestore Database
* Firebase Hosting
* Uploadcare File Management

**Tools & Deployment:**

* Vercel CLI
* Firebase CLI
* PowerShell / Terminal

---

## 🧠 Architecture Overview

```
Frontend (HTML, JS)
       ↓
Firebase Authentication → Secure login & role-based access
       ↓
Firestore Database → User, Chat, and Material storage
       ↓
Uploadcare → File uploads & sharing
       ↓
Hosting → Firebase Hosting / Vercel Deployment
```

---

## ⚡ Deployment Guide

### 🚀 Deploying to Vercel (Windows PowerShell)

1. **Install Vercel CLI:**

   ```powershell
   npm install -g vercel
   ```

2. **Login to Vercel:**

   ```powershell
   vercel login
   ```

3. *(Optional)* Install Firebase CLI for backend emulation:

   ```powershell
   npm install -g firebase-tools
   firebase login
   ```

4. **Deploy from project root:**

   ```powershell
   cd "c:\Users\VISHNU V\Downloads\ScholarSpot"
   vercel --prod
   ```

📎 **Notes:**

* Firebase and Uploadcare configurations are already integrated.
* Secure API keys via **Vercel Environment Variables** for production.

---

### 🔥 Deploying to Firebase Hosting (Windows PowerShell)

1. **Install Firebase CLI:**

   ```powershell
   npm install -g firebase-tools
   ```

2. **Login to Firebase:**

   ```powershell
   firebase login
   ```

3. **Select Firebase project:**

   ```powershell
   firebase use --add
   ```

   Choose your project ID: `ss99-a0bc7`

4. **Deploy hosting:**

   ```powershell
   cd "c:\Users\VISHNU V\Downloads\ScholarSpot"
   firebase deploy --only hosting
   ```

📎 **Notes:**

* The `firebase.json` handles SPA rewrites to `index.html`.
* Review Firestore rules for secure read/write operations.

---

## 🔒 Security Notes

* Keep all private Firebase API keys hidden (never commit to GitHub).
* Store secrets in Firebase or Vercel environment settings.
* Enforce Firestore and Uploadcare security rules for all user roles.
* Uploadcare storage usage is limited — exceeding the free tier may cause upload restrictions.

---

## 🧭 Future Scope

* AI-based student performance analysis
* Smart assistant chatbot for academic queries
* Google Classroom & Drive integration
* Admin analytics dashboard
* Peer-to-peer discussion and study rooms

---

## 🏷️ License

This project is licensed under the **MIT License** — free for use, modification, and distribution with proper credit.

---

## 📞 Contact

For queries or collaboration, reach out:

* **Vishnu V** — [vishnuv2309@gmail.com](mailto:vishnuv2309@gmail.com)
* **Amrutha D** — [amruthadandigimath@gmail.com](mailto:amruthadandigimath@gmail.com)

---

**Developed with dedication by Team Mind_Mesh | REVA University, Bangalore**
📍 *Empowering digital learning through innovation and collaboration.*

---
