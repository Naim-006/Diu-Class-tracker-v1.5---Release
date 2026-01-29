# DIU CSE Academic Tracker 🎓📱

![Version](https://img.shields.io/badge/version-2.2-blue.svg) ![Platform](https://img.shields.io/badge/platform-Android%20%7C%20Web-green.svg) ![License](https://img.shields.io/badge/license-MIT-orange.svg)

**DIU CSE Academic Tracker** is a comprehensive academic management application designed for students and faculty of Daffodil International University (CSE Department). This mobile-responsive application helps users track classes, manage academic calendars, view notices, and stay organized with their academic schedule.

Built with **React (Vite)**, **TypeScript**, and **Capacitor**, this project runs seamlessly as a web application and a native Android app.

---

## ✨ Key Features

*   **📅 Dynamic Class Routine**: Real-time class schedules and routine tracking.
*   **🔔 Instant Notices**: Integrated with Supabase to deliver real-time academic notices.
*   **📊 Academic Calendar**: view upcoming events, exams, and holidays.
*   **🔐 Authentication**: Secure user login and management (Class Representatives & Admins).
*   **📱 Mobile Optimized**: Fully responsive UI designed for a native-like experience on Android.
*   **🎨 Modern UI**: Beautifully designed with **TailwindCSS** and **Framer Motion** for smooth animations.
*   **📂 Offline Support**: (Mention if applicable, or remove).

---

## 🛠️ Tech Stack

*   **Frontend**: [React.js](https://react.dev/) (v19), [Vite](https://vitejs.dev/)
*   **Language**: [TypeScript](https://www.typescriptlang.org/)
*   **Styling**: [TailwindCSS](https://tailwindcss.com/)
*   **Mobile Engine**: [Capacitor](https://capacitorjs.com/) (v8)
*   **Backend / Database**: [Supabase](https://supabase.com/)
*   **Icons**: [Lucide React](https://lucide.dev/)
*   **Animations**: [Framer Motion](https://www.framer.com/motion/)

---

## 📸 Screenshots

| Dashboard | Class Routine | Notices |
|:---------:|:-------------:|:-------:|
| <img src="screenshots/dashboard.jpg" alt="Dashboard" width="200"/> | <img src="screenshots/routine.jpg" alt="Routine" width="200"/> | <img src="screenshots/notices.jpg" alt="Notices" width="200"/> |
*(Note: Add screenshots to an `screenshots` folder in your repository)*

---



## 📂 Project Structure

```bash
diu-cse-academic-tracker/
├── android/              # Android native project files
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # App pages (Dashboard, Login, etc.)
│   ├── context/          # React Context (Auth, etc.)
│   ├── services/         # API services (Supabase)
│   ├── App.tsx           # Main application entry
│   └── main.tsx
├── public/               # Static assets
├── capacitor.config.ts   # Capacitor configuration
└── package.json          # Dependencies and scripts
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

<p align="center">
  Made with ❤️ for DIU Students
</p>
