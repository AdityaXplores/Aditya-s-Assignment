
# 🗓️ Interactive Calendar Component

🔗 **Live Demo: https://aditya-s-assignment.vercel.app/ ** 

🎥 **Video Walkthrough: https://drive.google.com/file/d/1iJ1gG6Sw3O4NLC4eJO55k2lEQtxi1BkP/view?usp=drivesdk ** 

---

## 📌 Overview

A highly interactive, fully responsive calendar component built using **React + Next.js**, designed to emulate a modern wall calendar experience.

This project focuses on:

* ⚡ Clean architecture
* 🧠 Advanced state management
* 🎯 High-quality user experience

---

## ✨ Features

### 📅 Smart Date Selection

* Select single dates or ranges seamlessly
* Smooth, gapless highlight between selected dates

### 📝 Persistent Notes System

* Add notes for:

  * Individual dates
  * Date ranges
  * Entire month
* Data stored using **localStorage**
* Built with a custom `useNotes` hook

### 📊 Monthly Overview Dashboard

* Displays all notes for the current month
* Smart sorting:

  * Upcoming dates first
  * Past entries pushed to bottom

### 🎨 Dynamic Theming

* Theme (colors + image) changes automatically per month
* Improves visual engagement and season-based UX

### ⭐ Indicators

* Holidays → ⭐ icon
* Weekends → visually distinct

### 📱 Fully Responsive

* Desktop → side-by-side layout
* Mobile → stacked, touch-friendly UI

---

## 🏗️ Architecture & Decisions

### ⚙️ Framework — Next.js (App Router)

* Structured folder system (`src/app`)
* Optimized rendering & performance
* Easy deployment (Vercel)

---

### 🎨 Styling — Tailwind CSS

* Utility-first → faster UI development
* Easy responsive design
* Dynamic theming via classNames

---

### 🧠 State Management — React Hooks

* Used:

  * `useState`
  * `useMemo`
  * `useCallback`

* No external state library used

* State kept local and efficient

---

### 📆 Date Handling — date-fns

* Lightweight & modular
* Avoids manual date bugs
* Used for:

  * Comparisons
  * Intervals
  * Formatting

---

### 💾 Persistence — Custom Hook (`useNotes`)

* Wraps `localStorage`
* Emits custom events → instant UI updates
* Handles hydration safely (avoids SSR mismatch)

---

## 🚀 Getting Started

### ✅ Prerequisites

* Node.js installed → https://nodejs.org/

---

### 1️⃣ Clone the repo

```bash
git clone https://github.com/AdityaXplores/Aditya-s-Assignment.git
cd Aditya-s-Assignment
```

---

### 2️⃣ Install dependencies

```bash
npm install
```

---

### 3️⃣ Run development server

```bash
npm run dev
```

---

### 4️⃣ Open in browser

```bash
http://localhost:3000
```

---

## 🛠️ Tech Stack

* ⚛️ React 18
* ⚡ Next.js 14
* 🎨 Tailwind CSS
* 📆 date-fns
* 🎯 lucide-react (icons)

---

## 💡 Highlights

* Clean separation of concerns
* Scalable component structure
* Smooth animations & UX
* Real-world product-level UI thinking

---

## 📌 Future Improvements

* 🌐 Add backend (Firebase / Supabase)
* 🔔 Notifications & reminders
* 📅 Google Calendar sync
* 🎭 Dark mode support

---

## 🙌 Author

**Aditya**
Frontend Developer | Building better every day 🚀

---
