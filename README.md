# 🧮 Calculator App

[![Kotlin](https://img.shields.io/badge/Kotlin-1.8.0-blueviolet?logo=kotlin)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)](https://www.android.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A sleek and functional calculator application built with ❤️ using Kotlin for Android. This app provides basic arithmetic operations with a clean, intuitive user interface and smooth user experience.

## ✨ Features

- ➕➖✖️➗ **Basic Arithmetic**: Addition, Subtraction, Multiplication, and Division
- 🔢 **Decimal Support**: Full floating-point calculations with proper decimal handling
- 🔄 **State Management**: Tracks calculation state for smooth user experience
- 🎨 **Clean UI**: Modern Material Design with responsive layout
- 🚫 **Error Handling**: Gracefully handles edge cases and invalid operations
- ✨ **Smart Formatting**: Automatically removes unnecessary decimal points and trailing zeros
- 📱 **Responsive Design**: Works on various screen sizes and orientations

## 🚀 Getting Started

### Prerequisites

- 🛠️ Android Studio (Flamingo or newer recommended)
- 📱 Android SDK 21 (Android 5.0) or higher
- 🐘 Kotlin 1.8.0 or higher
- 🚀 Gradle 7.4.0 or higher

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/calculator-app.git
   cd calculator-app
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select 'Open an existing project'
   - Navigate to the cloned directory and select it

3. **Build and Run**
   - Connect an Android device or start an emulator
   - Click 'Run' (▶️) or press `Shift + F10`

## 🎮 Usage Guide

### Basic Operations
- Tap number buttons (0-9) to input values
- Use operator buttons (+, -, ×, ÷) to perform calculations
- Press '=' to see the result
- Press 'C' to clear the current calculation

### Advanced Features
- **Decimal Numbers**: Use '.' button for floating-point calculations
- **Negative Numbers**: Start with '-' or use after an operator
- **Chained Calculations**: Continue calculations with the previous result
- **Error Handling**: Invalid operations show 'Error' and can be cleared

## 🏗️ Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/krishhh/calculatorapp/
│   │   │   └── MainActivity.kt    # Main application logic
│   │   └── res/
│   │       ├── layout/            # UI layouts
│   │       │   └── activity_main.xml
│   │       ├── values/            # Resources
│   │       │   ├── colors.xml
│   │       │   ├── strings.xml
│   │       │   └── themes.xml
│   │       └── mipmap/            # App icons
└── build.gradle                   # Project configuration
```

## 🛠️ Implementation Details

### Key Components

- **MainActivity.kt**
  - `onDigit()`: Handles numeric input and updates display
  - `onOperator()`: Manages operator input with validation
  - `onDecimalPoint()`: Handles decimal input with state tracking
  - `onEqual()`: Performs calculations and formats results
  - `isOperatorAdded()`: Validates operator placement
  - `removeZeroAfterDot()`: Cleans up decimal formatting

### Technical Highlights

- **State Management**: Tracks input state to prevent invalid operations
- **Error Handling**: Comprehensive handling of edge cases
- **Performance**: Efficient calculation logic with minimal overhead
- **Accessibility**: Supports screen readers and large text

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 🔀 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🎉 Open a Pull Request

## 🙏 Acknowledgments

- Built as part of the Complete Kotlin Course
- Inspired by the Android developer community

---

<div align="center">
  Made with ❤️ by Krish Patel
</div>
