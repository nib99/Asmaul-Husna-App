# Asmaul-Husna-App
“A Python/Kivy Android app displaying the 99 Names of Allah.”
# Asmaul Husna App

A mobile application built with Python and Kivy to display the 99 Names of Allah (Asmaul Husna) with their meanings, packaged for Android.

## Features
- Displays Arabic names, transliterations, and English meanings.
- Search functionality to filter names.
- Scrollable, user-friendly interface.
- Deployed as an Android APK.

## Tech Stack
- **Python**: Core programming language.
- **Kivy**: Cross-platform GUI framework.
- **Buildozer**: Android packaging tool.

## Screenshots
![Home Screen](screenshots/home.png)
![Search Example](screenshots/search.png)

## Installation
1. **Prerequisites**:
   - Python 3.7+
   - Kivy (`pip install kivy`)
   - Buildozer (`pip install buildozer`)
   - Android SDK/NDK (via Buildozer or Android Studio)

2. **Build Instructions**:
   ```bash
   git clone https://github.com/yourusername/Asmaul-Husna-App.git
   cd Asmaul-Husna-App
   buildozer init  # Edit buildozer.spec as needed
   buildozer -v android debug
