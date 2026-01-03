# Goal Tracker 🚀

A premium, real-time goal tracking application built with **React Native**, **Expo**, and **Convex**. Manage your daily goals with a sleek UI, instant cloud sync, and full cross-platform support.

![Goal Tracker Banner](https://img.shields.io/badge/Goal-Tracker-blue?style=for-the-badge&logo=react)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-000000?style=for-the-badge&logo=convex&logoColor=FFCC00)

## ✨ Features

### 🎯 Goal Management
- **Add Goals**: Quickly capture new objectives with a dedicated input section.
- **Interactive Checklist**: Mark goals as completed with smooth animations.
- **Real-Time Sync**: Every change is saved instantly to the cloud using Convex, reflecting across all your devices.
- **Edit & Delete**: Full control over your goals with inline editing and quick deletion.

### 📊 Progress Tracking
- **Dynamic Header**: At-a-glance view of your daily completion progress.
- **Visual Progress Bar**: Watch your progress fill up as you check off items.
- **Statistics Dashboard**: Detailed breakdown in the Settings tab showing Total, Completed, and Active goals.

### 🎨 Premium UI/UX
- **Dark Mode Support**: Seamlessly switch between light and dark themes.
- **Glassmorphism Design**: Modern aesthetic with gradients and subtle shadows.
- **Responsive Layout**: Optimized for iOS, Android, and Web platforms.

---

## 🛠️ Tech Stack

- **Frontend**: React Native (Expo Router)
- **Backend/Database**: Convex (Real-time backend-as-a-service)
- **Styling**: Native Layouts with Expo Linear Gradient
- **Icons**: Expo Vector Icons (Ionicons)

---

## 🚀 Getting Started

Follow these steps to run Goal Tracker on your machine:

### 1. Clone & Install
```bash
# Clone the repository
git clone https://github.com/shahithkumar/GoalTracker.git

# Navigate to the project
cd GoalTracker

# Install dependencies
npm install
```

### 2. Configure Backend (Convex)
You need a Convex project to handle the real-time data:
```bash
# Initialize Convex and start the dev server
npx convex dev
```
*Note: This will prompt you to log in and create a project in the Convex dashboard.*

### 3. Run the App
```bash
# Start the Expo development server
npx expo start
```
- Press **`a`** for Android
- Press **`i`** for iOS
- Press **`w`** for Web

---

## 📂 Project Structure

- `/app`: Expo Router file-based navigation.
- `/components`: Reusable UI components (GoalInput, Header, ProgressStats, etc.).
- `/convex`: Backend schema and database functions.
- `/hooks`: Custom hooks for themes and data management.
- `/assets`: Styles, images, and fonts.

---

## 👤 Author
**Shahith Kumar**
- GitHub: [@shahithkumar](https://github.com/shahithkumar)

---

Developed with ❤️ for high-performance goal tracking.
