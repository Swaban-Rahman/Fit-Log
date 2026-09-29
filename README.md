# 🏋️ FitLog — Workout Library & Plan Tracker

> **Train with intent. Log every set.**

FitLog is a modern, responsive workout library and planning application built with **Next.js**. It allows users to explore workouts, view detailed exercise information, build a daily workout plan, save workouts for later, and track completed exercises through a clean dark-themed interface.

---

## ✨ Key Features

### 🏋️ Workout Library
Browse a collection of workouts with detailed information including categories, equipment, duration, calories, and ratings.

### 🔎 Search & Sort
Search workouts by name or category and sort the workout library by **Duration, Calories, or Rating**.

### 📋 Today's Plan
Add workouts to your daily plan with a maximum limit of **5 exercises**. Manage your planned workouts from one place.

### 💾 Saved Workouts
Save exercises for later and easily access them from the **Saved** section of the My Plan page.

### ✅ Workout Tracking
Mark planned workouts as completed, remove exercises from your plan, and receive instant toast notifications for your actions.

### 💾 Local Storage Persistence
Your Today's Plan, saved workouts, and completion status are stored in the browser's `localStorage`, allowing your data to remain available after refreshing the page.

### 📊 Workout Metrics
Track your current plan with dynamic statistics for:

- Exercises
- Total Minutes
- Total Calories

### 📱 Fully Responsive
Designed to work smoothly across:

- 📱 Mobile
- 📟 Tablet
- 🖥️ Desktop

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Next.js** | Application framework and routing |
| **React** | Building the user interface |
| **Tailwind CSS** | Styling and responsive design |
| **JavaScript / TypeScript** | Application logic |
| **Lucide React** | Interface icons |
| **Sonner** | Toast notifications |
| **LocalStorage** | Client-side data persistence |
| **FitLog API** | Workout data source |

---

## ⚙️ How It Works

1. Browse available workouts from the **Workout Library**.
2. Search or sort workouts to find a suitable exercise.
3. Open a workout to view its detailed information.
4. Add exercises to **Today's Plan** or save them for later.
5. Manage planned workouts from the **My Plan** page.
6. Mark completed workouts as done or remove them from the plan.
7. Your plan and saved workouts remain available after refreshing the browser.

---

## 🔌 API

FitLog uses the provided workout API.

### All Workouts

```text
https://api.abcz.workers.dev/api/fitlog
