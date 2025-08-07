# 📱 WebdriverIO Mobile Automation Framework

[![SDET Unicorns Course](https://img.shields.io/badge/Course-Mobile%20Automation%20with%20Appium%20%26%20WebdriverIO-blueviolet)](https://sdetunicorns.com/course/mobile-automation-with-appium-2-0-and-webdriverio/)

A comprehensive mobile test automation framework using WebdriverIO and Appium. This project is the official codebase for the [Mobile Automation with Appium & WebdriverIO](https://sdetunicorns.com/course/mobile-automation-with-appium-2-0-and-webdriverio/) course.

## ✨ Features

- **Cross-Platform:** Write tests once and run them on both Android and iOS.
- **Page Object Model:** Organized and maintainable test code using the Page Object pattern.
- **CI/CD Ready:** Includes a pre-configured GitHub Actions workflow for continuous integration.
- **Cloud Testing:** Integrated with BrowserStack for running tests on a wide range of real devices.
- **Modern Tooling:** Built with WebdriverIO and Appium 2.0.

## 📋 Prerequisites

Before you begin, ensure you have the following tools installed on your system.

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Java JDK](https://www.oracle.com/java/technologies/downloads/) (for Android testing)
- [Android Studio](https://developer.android.com/studio) (for Android SDK and emulators)
- [Xcode](https://developer.apple.com/xcode/) (for iOS testing, Mac only)
- [Appium 2.0](https://appium.io/docs/en/2.0/):
  
  ```bash
  npm install --force --save-dev
  npm install -g appium
  ```
- Appium Drivers (UIAutomator2 for Android, XCUITest for iOS):  

  ```bash
  appium driver install uiautomator2
  appium driver install xcuitest
  ```

## 🚀 Getting Started

Follow these steps to get the project up and running on your local machine.

### 1. Clone the Repository

First, clone the project to your local machine.

```bash
git clone https://github.com/yourusername/webdriverio-appium-course.git
cd webdriverio-appium-course
```

The structure is more professional and helps new users get started quickly while providing enough detail for more experienced users to understand the project setup.npx wdio config/wdio.android.bs.conf.js --spec ./test/specs/android/*.js

```
npx wdio config/wdio.android.bs.conf.js --spec ./test/specs/android/*.js
```

Project Structure

```
├── app/
│   ├── android/         # Android app files
│   └── ios/            # iOS app files
├── config/             # WebdriverIO configurations
├── test/
│   ├── specs/          # Test files
│   └── screenobjects/  # Page objects
└── .github/            # GitHub Actions CI configuration
```

This improved README provides:
- Clear prerequisites and installation steps
- Detailed environment setup instructions
- Configuration options
- Test execution commands
- Project structure overview
- Contributing guidelines
- License information
