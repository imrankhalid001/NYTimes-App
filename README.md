![GitHub Cards Preview](https://github.com/TheCodeMonks/TechBytes/blob/master/screenshots/nytimes_card.jpg?raw=true)

# 🗞 NY Times

**NY Times** is a Minimal News 🗞 Android application built to describe the use of JSoup with Modern Android development tools. *Made with love ❤️ by [Spikeysanju](https://github.com/Spikeysanju)*

> **⚡ Updated for Android 15** - This fork has been updated with the latest dependencies and is now fully compatible with Android 15. All known crashes have been resolved.

***Try latest NY Times app apk from below 👇***

[![NY Times](https://img.shields.io/badge/NYTimes🌈-APK-black.svg?style=for-the-badge&logo=android)](https://github.com/TheCodeMonks/NYTimes-App/releases/download/v1.4.3/nytimes.apk)
![Android 15](https://img.shields.io/badge/Android%2015-Compatible-green.svg?style=for-the-badge)
![Updated](https://img.shields.io/badge/Status-Updated%202025-blue.svg?style=for-the-badge)

## 🔄 Recent Updates

This is an updated fork of the original NY Times app with the following improvements:

- ✅ **Android 15 Compatibility** - Fully tested and compatible with Android 15
- ✅ **Updated Dependencies** - All libraries upgraded to their latest stable versions
- ✅ **Bug Fixes** - Resolved critical crashes and stability issues
- ✅ **Improved Performance** - Enhanced app performance and reliability

> **Note:** This fork maintains the original project's architecture and design philosophy while ensuring modern Android compatibility.

### Changes from Original

- Updated Kotlin and Android Gradle Plugin versions
- Migrated to latest AndroidX libraries
- Fixed Room database migration issues
- Resolved deprecated API usage
- Enhanced error handling in JSoup parsing
- Updated target SDK to Android 15 (API 35)
- Fixed lifecycle-aware component issues
- Improved Jetpack DataStore implementation

**Original Project:** [TheCodeMonks/NYTimes-App](https://github.com/TheCodeMonks/NYTimes-App)

## Built With 🛠

- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
- [JSoup](https://jsoup.org/) - Open source Java HTML parser, with the best of HTML5 DOM methods and CSS selectors, for easy data extraction.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous and more..
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
- [Flow](https://kotlinlang.org/docs/reference/coroutines/flow.html) - A flow is an asynchronous version of a Sequence, a type of collection whose values are lazily produced.
- [Jetpack DataStore](https://developer.android.com/topic/libraries/architecture/datastore) - Jetpack DataStore is a data storage solution that allows you to store key-value pairs or typed objects with protocol buffers. DataStore uses Kotlin coroutines and Flow to store data asynchronously, consistently, and transactionally
    - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) - Data objects that notify views when the underlying database changes.
    - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes.
    - [Room](https://developer.android.com/topic/libraries/architecture/room) - SQLite object mapping library.
    - [Jetpack Navigation](https://developer.android.com/guide/navigation) - Navigation refers to the interactions that allow users to navigate across, into, and back out from the different pieces of content within your app
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.

## Package Structure

    www.thecodemonks.techbytes   # Root Package
    .
    ├── data                # For data handling.
    │   ├── db              # Local Persistence Database. Room (SQLite) database
    |   │   ├── dao         # Data Access Object for Room   
    |   |   |── database    # Database Instance
    |
    ├── model               # Model classes
    |
    |
    ├── ui                  # Activity/View layer
    │   ├── |── base        # Base Activity
    |   │   ├── adapter     # Adapter for RecyclerView
    |   │   └── viewmodel   # Viewmodels for Articles   
    |   │   ├── articles    # Articles Fragment
    |   │   ├── details     # Details Fragment
    |   │   ├── bookmarks   # Bookmarks Fragment
    |
    |
    |── utils               # Utils for URLs

## Architecture

This app uses [***MVVM (Model View View-Model)***](https://developer.android.com/jetpack/docs/guide#recommended-app-arch) architecture.

![](https://github.com/TheCodeMonks/Notes-App/blob/master/screenshots/ANDROID%20ROOM%20DB%20DIAGRAM.jpg)

## 📋 Requirements

- Android Studio Arctic Fox or higher
- Minimum SDK 21 (Android 5.0)
- Target SDK 35 (Android 15)
- Kotlin 1.9+
- Gradle 8.0+

## 🚀 Getting Started

1. Clone this repository
```bash
git clone https://github.com/yourusername/NYTimes-App.git
```

2. Open the project in Android Studio

3. Sync Gradle and build the project

4. Run the app on an emulator or physical device

## Contribute

If you want to contribute to this library, you're always welcome!
See [Contributing Guidelines](https://github.com/TheCodeMonks/Notzz-App/blob/master/CONTRIBUTION.md).

## 👥 Contributors

This project is maintained by:

- **Original Creator:** [Spikeysanju](https://github.com/Spikeysanju) - Initial development and architecture
- **Android 15 Update:** [ImranKhalid001](https://github.com/imrankhalid001) - Dependency updates and compatibility fixes

Special thanks to all contributors who help maintain this project!

## Contact

Have a project? DM us at 👇

Drop a mail to: thecodemonksorg@gmail.com

## Donation

If this project helps you reduce time to develop, you can give me a cup of coffee :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/paypalme2/spikeysanju)

## 📄 License

```
MIT License

Copyright (c) 2020 TheCodeMonks

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## ⭐ Show your support

Give a ⭐️ if this project helped you!

**Original Repository:** [TheCodeMonks/NYTimes-App](https://github.com/TheCodeMonks/NYTimes-App)
