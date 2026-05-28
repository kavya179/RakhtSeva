# 🩸 RakhtSeva - Blood Donation Management Platform

[![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JS%20(ES6%2B)-red)](https://github.com/kavya179/RakhtSeva)
[![UI Framework](https://img.shields.io/badge/UI-Bootstrap%205-7952b3)](https://getbootstrap.com/)
[![Theme Control](https://img.shields.io/badge/Theme-Dark%20Mode%20Supported-212529)](#)

**RakhtSeva** is an advanced, client-side persistent web platform designed to streamline voluntary blood donation workflows, empower healthcare administrators, and provide rapid communication systems during critical medical emergencies. Built with an optimized, responsive interface, the application bridges the gap between active blood donors and patients in urgent need.

---

## 📌 Key System Modules & Features

### 🚨 1. Emergency Broadcast System
- **Time-Bound Requests:** Allows users or hospitals to dispatch high-priority blood alerts with customizable active windows (2, 6, 12, or 24 Hours).
- **Live Alert Feed:** Dynamically populates matching, location-aware alert badges to notify nearby matching blood groups instantly.

### 🔔 2. Smart Donor Recovery Reminders
- **Automated Alerts:** Implements chronological calculations checking days elapsed since a user's last logged donation.
- **Recovery Gateway:** Populates friendly, automated notification cards ("Time to Donate Again! 🎉") once the safe recovery period is cleared.

### 👑 3. Advanced Admin Command Dashboard
- **Roster & Record Auditing:** Complete data-grid tables allowing administrators to register, monitor, update, and remove accounts securely.
- **Dynamic Charting:** Features responsive data visualization via **Chart.js** to map available blood group volumes and camp registration turnouts.
- **Secure Sessions:** Protected admin state controllers preventing unauthenticated routing to management utilities.

### 🏆 4. Interactive Gamification & Engagement
- **Verified Certificate Engine:** Renders stylized, print-ready donation appreciation certificates with high-fidelity font integrations (`Great Vibes`).
- **Conditional Claims:** Prevents early claims by programmatically unlocking downloads only after successful confirmation of donation records.

---

## 🛠️ Core Tech Stack & Implementation

- **Frontend Interface:** HTML5, Modern CSS3 variables (custom semantic theme engines), and **Bootstrap 5.3.2** for responsive design.
- **Scripting & Business Logic:** Vanilla JavaScript (ES6+ modular architecture, custom event tracking, DOM token lists).
- **State Management & Caching:** Persistent client-side indexing leveraging browser `localStorage` structures with isolated registry schemas for session handling, emergency logs, and core user records.
- **Theme Engine:** Full global **Dark Mode** switcher with localized persistence across user sessions.

---

## 📂 Project Architecture

```text
├── index.html          # Landing page with emergency feeds & platform overview
├── signup.html         # Onboarding gateway for voluntary donors
├── login.html          # Secure entry point for registered users
├── donate.html         # User dashboard, appointment booking & certificates
├── admin.html          # Protected administrative management command center
├── css/
│   └── style.css       # Global stylesheets, custom properties & dark mode configurations
└── js/
    ├── script.js       # Core logic, client data layer, and registration flows
    └── admin.js        # Admin auth, user monitoring, and chart rendering frameworks
