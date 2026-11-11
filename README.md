# Salary & Tax Calculator App 📱💰

Welcome to **Project 1** for the **Mobile Application** course! This is a Flutter-based mobile application designed to quickly and accurately calculate net salaries and taxes based on predefined brackets.

## 👨‍💻 Author
**Oday naboush**

## ✨ Core Features
- **Dynamic Tax Calculation:** Instantly calculates tax and net salary based on user input.
- **Tax Bracket Logic:**
  - `Up to $500`: 0% Tax.
  - `$501 - $1500`: 5% Tax on the amount exceeding $500.
  - `Over $1500`: 10% Tax on the amount exceeding $1500 (plus the 5% from the previous bracket).
- **Intuitive Navigation:** Uses a Bottom Navigation Bar to switch smoothly between the main "Calculator" screen and the "About" page.
- **State Management:** Utilizes `StatefulWidget` and `setState()` for real-time UI updates.
- **Robust Error Handling:** Safely parses text input using `TextEditingController` to prevent crashes if fields are left empty.

## 🛠️ Technologies Used
- **Framework:** Flutter
- **Language:** Dart
- **Architecture:** Material Design standard components (`Scaffold`, `SingleChildScrollView`, etc.)

## 🚀 How to Run the Project
The source code is provided in the repository as a compressed archive (`tax_calculator.zip`).

1. Download and extract the `tax_calculator.zip` file.
2. Open the extracted folder in your preferred IDE (e.g., VS Code or Android Studio).
3. Open the terminal and run `flutter pub get` to install any necessary dependencies.
4. Run the command `flutter run` to launch the application on your connected device or emulator.
