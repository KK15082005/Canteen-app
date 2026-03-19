# 🍽️ CanteenHub – School Canteen Ordering System

A clean, responsive web app for a school canteen — browse snacks, place orders, manage students.

---

## 🚀 Setup Instructions

**No installation needed!**

1. Download all files into one folder
2. Open `index.html` in any browser (Chrome, Firefox, Edge)
3. Done — the app works immediately

> Needs an internet connection the first time (to load React from CDN).

---

## 📁 File Structure

```
canteenhub/
├── index.html      ← The main HTML file (loads everything)
├── style.css       ← All styles and CSS variables
├── data.js         ← Mock data + helper functions
├── store.js        ← Global state (React Context)
├── components.js   ← Reusable small components
├── pages.js        ← Full page components
├── app.js          ← Root App + mounts React
├── README.md
└── PROMPTS_USED.md
```

---

## 📦 Libraries Used

| Library | Purpose |
|--------|---------|
| **React 18** (CDN) | UI components & state |
| **ReactDOM** (CDN) | Renders React into the browser |
| **Babel Standalone** (CDN) | Lets us write JSX without a build step |
| **Google Fonts** | Syne + DM Sans fonts |

No npm, no webpack, no Node.js needed.

---

## 🗄️ Mock Data Approach

All data lives in `data.js` as plain JavaScript arrays.
A `fakeDelay()` function simulates real API loading times (shows spinners).
State is managed with React Context in `store.js`.

**Mock endpoints simulated:**
- `GET /snacks` → reads `INITIAL_SNACKS`
- `GET /students` → reads `INITIAL_STUDENTS`
- `GET /students/:id` → `.find()` on students array
- `POST /students` → `createStudent()` in store.js
- `POST /orders` → `placeOrder()` in store.js

---

## ✨ Features

- ✅ Snacks page with price, emoji, order count
- ✅ Order modal with student selector + quantity stepper
- ✅ Students list with search
- ✅ Create student form with auto referral code
- ✅ Student detail page with stats + order history
- ✅ Quick-order buttons on student detail
- ✅ Loading spinners on every page
- ✅ Form validation with error messages
- ✅ Toast notifications on actions
- ✅ Responsive design for mobile
