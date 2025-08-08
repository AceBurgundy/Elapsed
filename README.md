# ⏰ Elapsed - Smart Reminder App

**Never miss an important moment again!** Elapsed is a beautifully designed Flutter reminder app with unique time-based and calendar-based notification features.

## 🌟 Features

### ⏱ **Flexible Reminder Modes**
- **Set Date & Time Mode** ⏳
    - Set recurring reminders by years, months, days, hours, minutes, or seconds
    - Example: Remind me every 3 hours

- **Day of Month Mode** 📅
    - Set monthly or yearly reminders (e.g., "Every 15th day at 9 AM")
    - Advanced notification options (remind up to 10 days early)

### 🎨 **Beautiful UI**
- Clean Material Design interface
- Visual pie-chart timers show time progress
- Color-coded urgency indicators (green → orange → red)

### 🔔 **Smart Notifications**
- Instant notifications when time elapses
- Background service checks reminders every minute

### 🔍 **Easy Management**
- Search through all reminders
- Edit or delete reminders with one tap
- Dark mode support

## 🛠 How It Works

1. **Create a Reminder**
    - Tap the + button
    - Choose your reminder mode
    - Set your time parameters
    - Add a descriptive label

2. **Get Notified**
    - The app checks reminders every minute
    - Notifications appear when time elapses
    - Pie timer visually shows time remaining

3. **Manage Reminders**
    - Tap any reminder to edit
    - Swipe to delete
    - Use search to find specific reminders

## 📸 Screenshots

| Main Screen | Reminder Dialog | Timer Visualization |  
|------------|----------------|---------------------|  
| ![Main Screen](screenshots/main.png) | ![Dialog](screenshots/dialog.png) | ![Timer](screenshots/timer.png) |  

## ⚙️ Technical Details

**Built With:**
- Flutter 🦋 (Dart)
- SharedPreferences for local storage 💾
- Local Notifications 🔔

**Architecture:**
- Clean state management
- Custom painters for visual timers 🎨
- Responsive design for all screen sizes

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (latest version)
- Android Studio/VSCode

### Installation
```bash
git clone https://github.com/yourusername/elapsed.git
cd elapsed
flutter pub get
flutter run
```

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📜 License
[MIT](https://choosealicense.com/licenses/mit/)

## ✨ Why Elapsed?

Unlike standard reminder apps, Elapsed offers:
- **True recurring reminders** (not just one-time alerts)
- **Flexible time intervals** (from seconds to years)
- **Visual time tracking** with beautiful pie timers

Perfect for:  
✅ Medication reminders 💊  
✅ Bill payments 💵  
✅ Habit tracking 🏋️  
✅ Special occasions 🎉

**Download now and never lose track of time again!** ⏳➡️🎯
