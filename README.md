# EMS Pro - Employee Management System (Web Application)

EMS Pro is a responsive, client-side web-based Employee Management System designed to simplify HR operations such as user registration, role-based login, task assignment, and progress tracking — all without a backend server. Built using HTML, CSS, JavaScript, and LocalStorage, it supports three types of users: Admin, Manager, and Employee.

## 🔗 Live Demo

>  GitHub Pages or live URL here if hosted 
> https://kashish-008.github.io/Summer-Training-Project/

---

## 📂 Project Structure
```bash
/EMS/
│
├── index.html # Home page
├── login.html # Login page for all users
├── register.html # User registration page
├── admin-dashboard.html # Admin dashboard
├── manager-dashboard.html # Manager dashboard
├── employee-dashboard.html # Employee dashboard
├── about.html # About the project
├── contact.html # Contact form (admin sees messages)
├── admin-login.html # Separate login page for admin user
├── manager-login.html # Separate manager page for admin user
├── employee-login.html # Separate employees page for admin user
│
├── css/
│ ├── style.css # Main stylesheet
│ └── animation.css # Animations and transitions
│
├── js/
│ ├── auth.js # Role-based login and session handling
│ ├── theme.js # Dark mode toggle and persistence
│ ├── dashboard.js # Role-specific dashboard logic
│ ├── task.js # Task assignment and update logic
│ ├── animations.js # manage the animation in pages of html
```
---

## ✨ Key Features

- 🔐 Role-based login (Admin, Manager, Employee)
- 🧾 Task assignment and tracking by Admin
- 📊 Manager dashboard to view team progress
- ✅ Employees update their task statuses
- 🌙 Dark mode support (toggle saved in LocalStorage)
- 📦 LocalStorage used as client-side database (JSON format)
- 🎨 CSS animations and hover effects
- 📱 Fully responsive and mobile-friendly layout
- 📬 Contact form whose data is viewable by Admin

---

## 🧑‍💻 Technologies Used

- **HTML5** – Structure and layout
- **CSS3** – Styling, responsiveness, and animations
- **JavaScript (Vanilla)** – Functionality and logic
- **LocalStorage** – Persistent storage of user data and tasks
- **VS Code, Chrome DevTools** – Development tools

---

## 📋 How to Use

1. Clone or download this repository.
2. Open `index.html` in a browser.
3. Register users with different roles.
4. Login to experience the different dashboards:
   - Admin: Assign and manage tasks.
   - Manager: View team progress.
   - Employee: Update task status.
5. Try switching between dark/light mode.

---

## 📌 Future Scope

- Integrate Firebase or MongoDB as backend
- Add email/password authentication with OTP
- Enable real-time data sync between users
- Build mobile app version with React Native
- Add analytics and chart dashboards

---

## 📬 Contact

**Author:** Kashish Thakur  
**Trainer/Mentor:** Shaina Guru  
**College:** Chandigarh Group of College, Landran, Mohali

---

