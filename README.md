# ⏱️ Stopwatch Timer App

A simple and intuitive stopwatch Android application built using Kotlin. This app allows users to start, stop, resume, and restart a timer with a minimal and clean UI.

## 📱 Features

- **Start Timer**: Begins counting seconds from zero.
- **Stop Timer**: Pauses the current count without resetting.
- **Resume Timer**: Continues from where it left off.
- **Restart Timer**: Resets the timer back to `00:00:00`.

## 🛠 Tech Stack

- **Language**: Kotlin
- **UI**: XML layout with `LinearLayout` and `RelativeLayout`
- **View Binding**: `ActivityMainBinding` used for view references
- **Threading**: Uses `Handler` and `Runnable` for time updates

  ## 🎬 Demo

https://github.com/user-attachments/assets/041296e2-bc4a-4846-8c9d-cf7ce3f7623f


## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/StopwatchApp.git
2. Open the project in Android Studio
3. Build and run on an emulator or Android device


## 📌 Notes- Timer is updated every second using a Handler on the main thread
- UI disables/enables buttons based on timer state for intuitive interaction

## 💡 Created by me with love for clean code and clean timekeeping
